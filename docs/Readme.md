# The Udagram Running server

[Click Here](http://burham.s3-website-us-east-1.amazonaws.com/) to get the URL of the Udagram deployed API

[__Diagram of APP process__]

( Client ) - Send Request ->
[ S3 Bucket ] - Send Data ->
[ EB Server ] - Check data and connect to DB ->
[ Database ] - Response Back to ->
[ EB Server ] - Return Data ->
[ S3 Bucket ] - Vieweing to ->
( Client )

[__Diagram of Deploy Process__]

(CircleCi) - Connect to GitHub -> ( Github ) - Send Data -> ( CircleCi ) - Build Data & Deploy -> [AWS S3] & [EB Environment] -> Return Data to servers

