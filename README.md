
# World-Cup-2019-Web-Scrapping-Project

Made a web scrapper which has ability to scrap the WorldCup 2019 matches and keep those matches in excel and folders. The purpose of this project is to extract information of worldcup 2019 from cricinfo and present that information in the form of excel and pdf scorecards. The application can be used to solve real purpose problems of extracting large information from websites.


## Npm Modules Used

- Minimist--> Takes command line arguments
- Axios--> For making http request
- JSDOM--> For getting information from dom tree
- EXCEL4NODE--> Used to make excel file
- PDF_LIB--> Used to make scorecards in the form of pds

  
## FEATURES AND FUNCTIONS
Dowloading data in the form of HTML by making a http request using axios as we are not using any browser so axios will help to achieve this. Reading HTML and extracting important and useful information using Jsdom Converting matches to teams using Array Manipulation Making of excel file and adding important stuff in that excel using excel4node library Making pdf and making changes to Template pdf using pdf-lib library.
  
## PDF TEMPLATE BEFORE RUNNING SCRIPT

![pdf template img](https://user-images.githubusercontent.com/73634132/137447308-4b1b0a92-e8e9-49ff-b484-369931bef9b6.png)

## PDF TEMPLATE AFTER RUNNING SCRIPT 

![imageofpdftemplateafterrunningthescript](https://user-images.githubusercontent.com/73634132/137447397-55df7b42-73c8-4eb8-8cda-ed6a084ccc30.png)

## EXCEL FILE CREATION WITH DATA AFTER RUNNING SCRIPT

![iamgeofexcelfile](https://user-images.githubusercontent.com/73634132/137447486-c4029ba3-d049-4c1f-9500-4bbc38c1f801.png)

  
## Deployment

First fork this to your profile, then clone it to your desktop

Then install the following libraries

```bash
  npm install minimist
  npm install axios
  npm install pdf-lib
  npm install excel4node
  npm install jsdom
```
To run this project fire this command
```bash
  node WebScrapingCricInfo.js --url="https://www.espncricinfo.com/series/icc-cricket-world-cup-2019-1144415/match-results" --htmlFile="download.html" --dest="World Cup"
```

  
## CONTACT

#### In case of any suggestions or enquires, feel free to contact me.

E-mail :- ajju9990.ak@gmail.com


  