### Given a URL for a CSV(Comma Separated Values) formatted file, please write a function that does the following:

1. Download the file fro the URL provided below and store it on disk
2. Read the contents of the file and load them into a dictionary object
3. Return the and Array of dictionary objects

### PART I: Fixed Column input file

#### URL: https://raw.githubusercontent.com/binarybutter/assignments-input-files/master/csv-sample-data.csv


### Assumptions to be made about the input file:

1. Can contain any arbitrary number of lines
2. Each lines contains exactly 4 columns
3. All the four columns have String type values. Refer to the sample format of input and sample output

#### Format of the input CSV file:

```
a1,b1,c1,d1
a2,b2,c2,d2
...........
an,bn,cn,dn
```

### Expected output format

```
[{
  "c1":"a1",
  "c2": "b1",
  "c3": "c1",
  "c4": "d1"
},
{
  "c1": "a2",
  "c2": "b2",
  "c3": "c2",
  "c4": "d2"
},
{
  "c1": "a3",
  "c2": "b3",
  "c3": "c3",
  "c4": "d3"
},
.
.
{
  "c1": "an",
  "c2": "bn",
  "c3": "cn",
  "c4": "dn"
}]
```

### PART II: Variable Column input file

#### URL: https://raw.githubusercontent.com/binarybutter/assignments-input-files/master/csv-sample-data.csv

### Assumptions to be made about the input file:

1. Can contain any arbitrary number of lines
2. Each lines contains any arbitrary number of columns
3. Every column can have different data type data and the response object should have the closest data type. Refer to the sample format of input and sample output

#### Format of the input CSV file:

```
str1,1,3.0,str2,44,a,g1
2,22,c3.0,4
a3,b3,c3,d3,e3,f3
...........
an,bn,cn,dn....,nn
```

### Expected output format

```
[{
  "c1":"str1",
  "c2": 1,
  "c3": 3.0,
  "c4": "str2",
  "c5": 44,
  "c6": "a",
  "c7": "g1",
},
{
  "c1": 1,
  "c2": 22,
  "c3": "c3.0",
  "c4": 0.4
},
{
  "c1": "a3",
  "c2": "b3",
  "c3": "c3",
  "c4": "d3",
  "c5": "e3"
  "c6": "f3"
},
.
.
{
  "c1": "an",
  "c2": "bn",
  "c3": "cn",
  "c4": "dn"
}]
```

### Submission:

Please create git repo in your github account push the code to a feature branch and share the link for the pull request to master branch on slack.
