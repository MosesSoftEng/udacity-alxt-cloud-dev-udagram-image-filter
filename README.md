# Udagram Image Filter Application Server.
Application server for filtering images in the Udagram web application that will run on it own AWS EC2 server provisioned by Elastic Beanstalk.

## Endpoint URL for a running elastic beanstalk deployment (EB_URL)
[http://udagram-image-filter-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://i.imgur.com/WvcU1zU.jpeg](http://udagram-image-filter-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://i.imgur.com/WvcU1zU.jpeg)

## NOTE! Project provided test images issues.
[https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg](https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg)
Image does not exist

[https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg](https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg) Image is CORS protected check here [CORS Tester for provided Wikipedia image](https://cors-test.codehappy.dev/?url=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fb%2Fbd%2FGolden_tabby_and_white_kitten_n01.jpg&method=get)


## Platforms
Node.js and Express.js

### Commands used
Install dependecies in package.json
npm install

Run the application
npm run dev


## Third party Packages
[valid-url package](https://www.npmjs.com/package/valid-url)
npm i valid-url
 npm install @types/valid-url

## Check for CORS
[CORS Tester](https://cors-test.codehappy.dev)


## Source code reference
[Image Filter Starter Code](https://github.com/udacity/cloud-developer/tree/master/course-02/project/image-filter-starter-code)


**Build Project and update project**
npm run build; eb deploy




