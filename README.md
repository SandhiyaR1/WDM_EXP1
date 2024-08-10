### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
* Training Data Set -> Employee Table
  
  ![WhatsApp Image 2024-08-10 at 13 31 42_eea8f8fc](https://github.com/user-attachments/assets/07a5432c-bc92-4655-add1-9f3e50af2e89)

* Training data set -> Weather Table

  ![WhatsApp Image 2024-08-10 at 09 18 47_fc744fd0](https://github.com/user-attachments/assets/e14de362-3339-46fa-ab9d-1a26f00dd186)

### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
* Employee Table after adding new attribute ADDRESS:
  
  ![WhatsApp Image 2024-08-10 at 13 32 45_60bf8751](https://github.com/user-attachments/assets/4c584051-48b0-4398-8164-8f6c696dacc7)

* Weather Table after adding new attribute CLIMATE:
  
  ![WhatsApp Image 2024-08-10 at 13 16 11_cb74bf72](https://github.com/user-attachments/assets/c3b2d4b8-bc18-4d12-bb1b-f32984bf8264)

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
* Employee Table after removing attributes SALARY, GENDER:
  
  ![WhatsApp Image 2024-08-10 at 13 33 37_6e03c5b2](https://github.com/user-attachments/assets/83dd3350-07ec-48ba-9614-419ec14db109)

* Weather Table after removing attributes WINDY, PLAY:
  
  ![WhatsApp Image 2024-08-10 at 13 25 36_159ef5cd](https://github.com/user-attachments/assets/d3c71583-7cba-472d-ae06-420380e45548)

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
* Employee Table after Normalizing ID, EXP, PHONE:
  
  ![WhatsApp Image 2024-08-10 at 13 34 37_71b089d4](https://github.com/user-attachments/assets/90d6e19c-316b-4984-8393-27ea14c6d9b0)
* Weather Table after Normalizing TEMPARATURE, HUMIDITY:
  
  ![WhatsApp Image 2024-08-10 at 13 30 57_fd2aa12a](https://github.com/user-attachments/assets/f3929a15-6c73-4305-b69e-6a09b001f1d1)

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
