# The Udagram Running server

[Click Here](http://udagram-bucket123987.s3-website-us-east-1.amazonaws.com/) to get the URL of the Udagram deployed API

[__Diagram of APP process__]

( Client ) - Send Request ->[ S3 Bucket ] - Send Data ->[ EB Server ] - Check data and connect to DB ->[ Database ] - Response Back to ->
[ EB Server ] - Return Data ->[ S3 Bucket ] - Vieweing to ->( Client )

![](https://github.com/Gooda97/udigram/blob/master/Drawings/App-process.png)
