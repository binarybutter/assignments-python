### Given a URL for a CSV(Comma Separated Values) formatted file, please write a function that does the following:

1. Download the file fro the URL provided below and store it on disk
2. Read the contents of the file and load them into a dictionary object
3. Return the dictionary object

#### URL: https://raw.githubusercontent.com/binarybutter/assignments-input-files/master/csv-sample-data.csv

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


### Expected output format

```
{
  "c1", "a1",
  "c2", "b1",
  "c3", "c1",
  "c4", "d1"
},
{
  "c1", "a2",
  "c2", "b2",
  "c3", "c2",
  "c4", "d2"
},
{
  "c1", "a3",
  "c2", "b3",
  "c3", "c3",
  "c4", "d3"
},
.
.
{
  "c1", "an",
  "c2", "bn",
  "c3", "cn",
  "c4", "dn"
}
```

### Submission:

Please create git repo in your github account and share the link for the repo in Slack.
