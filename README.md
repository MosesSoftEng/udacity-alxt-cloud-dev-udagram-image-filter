# Udagram Image Filter Application Server.
Application server for filtering images in the Udagram web application that will run on it own AWS EC2 server provisioned by Elastic Beanstalk.

## Endpoint URL for a running elastic beanstalk deployment (EB_URL)
[http://udagram-image-filter-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://i.imgur.com/WvcU1zU.jpeg](http://udagram-image-filter-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://i.imgur.com/WvcU1zU.jpeg)

## Sample results
Initial Image curtesy of imgur.com

![Cat walking](https://i.imgur.com/WvcU1zU.jpeg)


Filtered Image

![Filtered cat image](images/filteredimage.jpg)


## NOTE! Project provided test images issues.
[https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg](https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg)
Image does not exist

[https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg](https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg) Image is CORS protected check here [CORS Tester for provided Wikipedia image](https://cors-test.codehappy.dev/?url=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fb%2Fbd%2FGolden_tabby_and_white_kitten_n01.jpg&method=get)

## Platforms used.
Node.js and Express.js
AWS Elastic Beanstalk

## Commands used
Install dependecies in package.json

```npm install```

Run the application locally

```npm run dev```

Build application

```npm run build```

Create Elastic Beanstalk application 

```eb init```

Create Elastic Beanstalk infrastructure

```eb deploy```

Deploy/ Update Node.js Changes to Elastic Beanstalk

```eb create```

## Third party Packages used in node.js
[valid-url package](https://www.npmjs.com/package/valid-url)

```npm i valid-url```

```npm install @types/valid-url```

# Reference
1. [Image Filter Starter source Code](https://github.com/udacity/cloud-developer/tree/master/course-02/project/image-filter-starter-code)
2. [CORS Tester web application](https://cors-test.codehappy.dev)
