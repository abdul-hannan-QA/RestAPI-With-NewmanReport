# RestAPI-With-NewmanReport
restful-booker API

## technology and tool used
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

Report: 
Install: npm install -g newman-reporter-html
	npm install -g newman-reporter-htmlextra
Run Command: 
newman run “Collection Link” -e “Path”/EnvironmentName.json -r cli,html
or
newman run “Collection Link” -e “Path”/EnvironmentName.json -r cli,htmlextra
![image](https://user-images.githubusercontent.com/73884851/201742784-c3723483-0b14-4d79-ac27-03642e8e0de9.png)

      
## Prerequisites
- You must have installed node js to your system

- Postman

## API Documents

 https://documenter.getpostman.com/view/14991602/2s8YmEymS9

## Output
<img width="417" alt="Screenshot_1" src="https://prnt.sc/3TyPbHyNHxnj">
<img width="417" alt="Screenshot_2" src="https://prnt.sc/4KUyMKyChUqO">
