### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
## Buying:
![image](https://github.com/naren2704/WDM_EXP2/assets/118706984/3f2b2c00-30c0-4efb-88a1-5bec1e9c3482)

## Employee:
![image](https://github.com/naren2704/WDM_EXP2/assets/118706984/90c6b48f-29f6-4ac3-a7b7-c11a318f8b18)

## Bank:

![image](https://github.com/naren2704/WDM_EXP2/assets/118706984/b2a3dfc6-2bb7-450d-bf4b-b3ec4bb7c322)


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
## Buying:
![image](https://github.com/naren2704/WDM_EXP2/assets/118706984/74185200-a2e6-46f4-8f0e-8859631a2621)

## Employee:
![image](https://github.com/naren2704/WDM_EXP2/assets/118706984/0671139c-43ac-4e16-a05e-55b00140aaee)

## Bank:
![image](https://github.com/naren2704/WDM_EXP2/assets/118706984/01341269-dcef-4eae-a2ed-dee8cc7d5450)


### RESULT: 
Thus this program has been successfully executed.
