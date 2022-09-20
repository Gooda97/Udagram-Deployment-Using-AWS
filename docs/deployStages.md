# Deploy proccess stages

### 1) Database
testing the database connection at aws RDS
[![](https://burham.ml/snp/01.png)](https://burham.ml/snp/01.png)

----

### 2) s3 Bucket
After S3 Bucket creation and setting the Static website Enabled
[![](https://burham.ml/snp/02.png)](https://burham.ml/snp/02.png)

----

### 3) ElasticBeanstalk
#### Adding Environment variables to the ElasticBeanstalk after creation
Include all the needed variables to connect DB
[![](https://burham.ml/snp/03.png)](https://burham.ml/snp/03.png)

----

#### Checking the ElasticBeanstalk health after adding all variables
checking the EB health after adding the Environemts to connect DB
[![](https://burham.ml/snp/04.png)](https://burham.ml/snp/04.png)

----

### 4) BackEnd Runtime
Checking the URL of the BackEnd server ( **[Live link to server](http://udagram-api-dev.eba-q6dgcvjf.us-east-1.elasticbeanstalk.com/)** )
[![](https://burham.ml/snp/05.png)](https://burham.ml/snp/05.png)

### 5) FrontEnd connected with BackEnd
Connecting to the S3 website after connecting API with FrontEnd and DB
[![](https://burham.ml/snp/06.png)](https://burham.ml/snp/06.png)

### 6) Create the Github Repo
Add all files into repo after build and commit it to github 
[![](https://burham.ml/snp/07.png)](https://burham.ml/snp/07.png)

### 7) CircleCi
Added all files to the CircleCi and setup the project with the needed Environment variables
#### Checking CircleCi Environment list
[![](https://burham.ml/snp/11.png)](https://burham.ml/snp/11.png)

#### Checking CircleCi Build
[![](https://burham.ml/snp/08.png)](https://burham.ml/snp/08.png)

#### Checking CircleCi Deploy
[![](https://burham.ml/snp/09.png)](https://burham.ml/snp/09.png)

#### Last CircleCi Status
[![](https://burham.ml/snp/10.png?123)](https://burham.ml/snp/10.png?123)
