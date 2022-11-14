## RestAPI-With-NewmanReport
restful-booker API

### Technology and tool used
- postman
- newman


## How to run this project

- clone this project

- hit following commands
      
    Newman 
Install Command: npm install -g newman

Run Command: 
newman run “Path/CollectionName.json” -e Path/EnvironmentName.json
or
newman run “Collection Link” -e “Path”/EnvironmentName.json

For Report: 
Install: npm install -g newman-reporter-html
	npm install -g newman-reporter-htmlextra
Run Command: 
newman run “Collection Link” -e “Path”/EnvironmentName.json -r cli,html
newman run “Collection Link” -e “Path”/EnvironmentName.json -r cli,htmlextra


      
## Prerequisites
- You must have installed node js to your system

- Postman

## API Documents

 https://documenter.getpostman.com/view/14991602/2s8YmEymS9

## Output Image
<img width="417" alt="Screenshot_1" src="https://ibb.co/njd8j9d">
<img width="417" alt="Screenshot_2" src="https://ibb.co/jbpVQQx">
