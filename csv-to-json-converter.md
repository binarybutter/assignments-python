### Given a URL for a CSV(Comma Separated Values) formatted file, please write a function that does the following:

1. Download the file and store it on disk
2. Read the contents of the file and load them into a dictionary object
3. Return the dictionary object

### Format of the input CSV file:

```
a1,b1,c1,d1
a2,b2,c2,d2
...........
an,bn,cn,dn
```

### Assumptions to be made about the input file:

1. Can contain any arbitrary number of lines
2. Each lines contains exactly 4 columns
3. All the four columns have String type values
