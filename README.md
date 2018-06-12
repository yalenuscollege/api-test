Yale-NUS College IT - API Test
==============================

## Purpose

Please complete this short test, it will help both you (the candidate) and us determine if the our required competencies are met. Please use industry standards and best practices that you are familiar with. 

## Requirements

1. The test must be completed using one of the followng programming languages: PHP, Java, or Javascript (back-end or front-end Javascript)

2. Consume the PM2.5 rest api from data.gov.sg. More information about the API can be found at https://data.gov.sg/dataset/pm2-5.

Here is an example of the endpoint URL: https://data.gov.sg/realtime-api/environment/pm25?start=2018-06-11T07:20:16

3. Parse the json output and display the output.

Your program should be executable in command line / console (PHP, Java, back-end Javascript) or be displayed in HTML (Front-end Javascript)

If you choose to use a library, please use inline comments to explain what you are using the library for. Send our HR representative a link to your code along with any other code samples you wish to share as a part of your application. 

Thank you and good luck!

## Example

$ php restapitest.php


event_time: 2018-06-11T12:08:53Z  
timestamp: 2018-06-11T12:00:00Z  
west: 20  
east: 26  
central: 21  
south: 21  
north: 14  


event_time: 2018-06-11T13:03:53Z  
timestamp: 2018-06-11T13:00:00Z  
west: 11  
east: 12  
central: 19  
south: 22  
north: 14  

... and so on.
