10000 foot overview 
start out with storage

storage 4 different compontents
s3 almost as old as aws itself

talking about files word documents 
images
text files


not an application or a database
object based storage

not block based storage

place to put objects in the cloud
dropbox
    used s3 
    have metadata in their own storage
    objects exist in s3 today 

glacier
    requirement from the ssa or reg body
    files stored for 7years but need not instant access
    data archiving
    storing for compliance reasons

3 - 4 hours to retrieve

efs
    elastic file service
    file based storage and share it 
    could install database and applciations
    share with multiple vms

what does s3 stand for simple storage service

storage gateway 
    onpremise data center connection
    virtual machine image and communicate with s3 
    doesnt come up on developer 
    comes up on sys devops exam

s3 object based not databse or application

efs or ebs for server storage
elastic block store is ebs
virtual ec2 connenction to storage

databases 
    fundamental part of all exams
    RDS mysql postgresql mariadb sqlserver oracle
    aurora
    postgresql

    RDS in the course
    solutions architect and sys devops

developer exam
    dynamodb
    diffeernece between the 2 
really scaleable
    performant
    getting away from traditional
    dynamo db course 0 to hero 


essential for developer exam 

redshift
    datawarehousing 
    query when run a report
    dont run on a production database
    
    run query on query that is not production 
    this is calculations and analysis
    use redshift for analysis or reporting
    
for big data specialty cert 

elasticache
    cache the data in the cloud 
    shop front top 20 items 
    vacuum cleaner
        image and name does not change

    take a load off the database by caching the data that does not change

    mostly in the devloper exam

    take a load off of the databse
    use elasticache

migration services
    snowball 
    import export

    
net profit for a toaster in asiapacific

redshift for big data speciality cert

click on a vacuum cleaner 
    take the data out of the database 
    take a load off of the DB

take oracle database and migrate to oracle

minute 640

services part 2


compute 
------------------------------
    ec2 
        one of the first services 
    ec2 container service 
        manage docker containers atscale
    elastic bean stalk
        without knowledge of aws 
        focus only on code 
    lambda
        serverless
        only worry about your code 
    light sail 
        dont want to understand anything about aws 
        about access and networks 
        vps service 
        provision with server and fixed ip address
        watered down version of ec2 

batch 
    batch computing 


storage 
------------------------------
    s3 is oldest 
        simple storage service 
        buckets in the cloud 
    efs 
        elastic file system 
        network attached storage 
    glacier 
        data archival 
    snowball 
        write physically to a disk and import it manually
    storage gateway 
        virtual machines on premise 
        
    
databases
------------------------------
RDS
    relational database service 
DynamoDB
    nonrelational database service 
Elasticache
    caching commonly queried data 
    for performance increase
Red Shift
    database warehousing 
    querying complex
        a lot of joins etc 
    data warehousing 

migration 
------------------------------
aws migration hub 
    tracking service 
    during migration 
app discovery service 
    automated detect applications and dependencies 
db migration service 
    visualize
    during migration 
    onpremise to cloud 

server migration service 
    similar to db 
    virtual and physical to aws 

snowball
    storage and migration 
    migrate large amounts of data 

networking and contnet delivery 
------------------------------
vpc 
    virtual private cloud 
    firewalls 
    security groups 
    route tables 
    security groups 
        fundamental part of 3 ass exams 
cloudfront 
    content delivery entwork 
route53
    go through and buy a domain name 
    old school telephone book 
api gateway 
    create your own api 
    developer ass course 
direct connect 
    dedicated line 
    into vpc 


developer tools 
------------------------------
    codestar 
        group of devlelpers
        project management 
        collaboration 
        continuos delivery
    codecommit 
        git repositories in codecommit
        store code 
        source control service 
    codebuild 
        running test 
        compiling and deploy 
    codedeploy 
        automate deployment 
        onpremise 
        lambda as well 
    codepipeline
        continuous integration 
    xray 
        root cause analysis 
    cloud9 
        ide environment 
        aquisition 


