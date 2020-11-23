# PViewer
PViewer is a tool which is going to find overlapping permissions between two AWS IAM policies.\
\
#### Example
Two policies allowing you to write objects in the same S3 bucket. It will plot a graph and connecting overlapping policies as edges. 
![Alt text](https://github.com/ankitsaini2609/PViewer/blob/master/demo.gif "demo")  

## Installation
```sudo pip3 install -r requirements.txt```

## How to use
1. Set ```AWS_PROFILE``` as environment variable<br/>
2. ```python3 PViewer.py -u username```<br/>
Where username is IAM username in AWS.

## Output
![Alt text](https://github.com/ankitsaini2609/policy_viewer/blob/master/output.png "Graph of Conflicting Policy")
