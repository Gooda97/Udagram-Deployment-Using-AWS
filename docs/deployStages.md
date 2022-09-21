# Deploy proccess stages

### 1) Database
testing the database connection at aws RDS
[![](https://github.com/Gooda97/udigram/blob/master/images/1.png)](https://github.com/Gooda97/udigram/blob/master/images/1.png)

----

### 2) s3 Bucket
After S3 Bucket creation and setting the Static website Enabled
[![](https://github.com/Gooda97/udigram/blob/master/images/2.png)](https://github.com/Gooda97/udigram/blob/master/images/2.png)

----

### 3) ElasticBeanstalk
#### Adding Environment variables to the ElasticBeanstalk after creation
Include all the needed variables to connect DB
[![](https://github.com/Gooda97/udigram/blob/master/images/3.png)](https://github.com/Gooda97/udigram/blob/master/images/3.png)

----

#### Checking the ElasticBeanstalk health after adding all variables
checking the EB health after adding the Environemts to connect DB
[![](https://github.com/Gooda97/udigram/blob/master/images/4.png)](https://github.com/Gooda97/udigram/blob/master/images/4.png)

----

### 4) BackEnd Runtime
Checking the URL of the BackEnd server ( **[Live link to server](http://udagram-api-dev.eba-q6dgcvjf.us-east-1.elasticbeanstalk.com/)** )
[![](https://github.com/Gooda97/udigram/blob/master/images/5.png)](https://github.com/Gooda97/udigram/blob/master/images/5.png)

### 5) FrontEnd connected with BackEnd
Connecting to the S3 website after connecting API with FrontEnd and DB
[![](https://github.com/Gooda97/udigram/blob/master/images/6.png)](https://github.com/Gooda97/udigram/blob/master/images/6.png)

### 6) Create the Github Repo
Add all files into repo after build and commit it to github 
[![](https://burham.ml/snp/07.png)](https://burham.ml/snp/07.png)

### 7) CircleCi
Added all files to the CircleCi and setup the project with the needed Environment variables
#### Checking CircleCi Environment list
[![](https://github.com/Gooda97/udigram/blob/master/images/8.png)](https://github.com/Gooda97/udigram/blob/master/images/8.png)

#### Checking CircleCi Build
[![](https://github.com/Gooda97/udigram/blob/master/images/9.png)](https://github.com/Gooda97/udigram/blob/master/images/9.png)

#### Checking CircleCi Deploy
[![](https://github.com/Gooda97/udigram/blob/master/images/10.png)](https://github.com/Gooda97/udigram/blob/master/images/10.png)

#### Last CircleCi Status
[![](https://github.com/Gooda97/udigram/blob/master/images/11.png)](https://github.com/Gooda97/udigram/blob/master/images/11.png)
