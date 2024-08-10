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

Employee Table

![WhatsApp Image 2024-08-10 at 08 58 52_ea807729](https://github.com/user-attachments/assets/e3c31152-8a6e-44d6-a33f-62770fd575b3)


Weather Table

![WhatsApp Image 2024-08-10 at 09 05 40_23ebe0ed](https://github.com/user-attachments/assets/ceaff833-4da7-4ed7-bc80-70457ed1467e)


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

Weather Table after adding new attribute CLIMATE:

![WhatsApp Image 2024-08-10 at 09 40 04_17e8329a](https://github.com/user-attachments/assets/51787ad0-5692-4f3e-a613-21cc1b9c0a66)

Employee Table after adding new attribute ADDRESS:

![WhatsApp Image 2024-08-10 at 10 03 04_432adbcd](https://github.com/user-attachments/assets/0e65a254-e808-4e14-a9aa-0ae74bb65d96)


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

Weather Table after removing attributes WINDY, PLAY:

![WhatsApp Image 2024-08-10 at 09 44 31_a830d40c](https://github.com/user-attachments/assets/e452ee3d-c0bd-41ed-b8da-3b01b2f4d9b5)

Employee Table after removing attributes SALARY, GENDER:

![WhatsApp Image 2024-08-10 at 10 06 51_a54ac48d](https://github.com/user-attachments/assets/c75de426-d38f-45ab-931f-6cc789524492)


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

Weather Table after Normalizing TEMPARATURE, HUMIDITY:

![WhatsApp Image 2024-08-10 at 09 46 58_7dc9b37d](https://github.com/user-attachments/assets/4e4b1a60-e2cd-4963-837e-fac189ebf71d)

Employee Table after Normalizing ID, EXP, PHONE:

![WhatsApp Image 2024-08-10 at 10 09 39_35c17dc7](https://github.com/user-attachments/assets/80909db5-83b6-4d5f-b60b-e4d0c5d9ba95)


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
