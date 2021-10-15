# World-Cup-2019-Web-Scrapping-Project
Made a web scrapper which has ability to scrap the WorldCup 2019 matches and keep those matches in excel and folders. The purpose of this project is to extract information of worldcup 2019 from cricinfo and present that information in the form of excel and pdf scorecards. The application can be used to solve real purpose problems of extracting large information from websites.
#Languages Used
Javascript
#NPM Modules Used
   Minimist--> Takes command line arguments
   Axios--> For making http request
   JSDOM--> For getting information from dom tree
   EXCEL4NODE--> Used to make excel filr
   PDF_LIB--> Used to make scorecards in the form of pds
   
#Features and Functions
    1.Dowloading data in the form of HTML by making a http request using axios as we are not using any browser so axios will help to achieve this. 
    2.Reading HTML and extracting important and useful information using Jsdom Converting matches to teams using Array Manipulation Making of excel file and adding important stuff     in that excel using excel4node library.
    3.Making pdf and making changes to Template pdf using pdf-lib library.

#PDF TEMPLATE BEFORE RUNNING SCRIPT
![pdf template img](https://user-images.githubusercontent.com/73634132/137447308-4b1b0a92-e8e9-49ff-b484-369931bef9b6.png)
#PDF TEMPLATE AFTER RUNNING SCRIPT
![imageofpdftemplateafterrunningthescript](https://user-images.githubusercontent.com/73634132/137447397-55df7b42-73c8-4eb8-8cda-ed6a084ccc30.png)
#EXCEL FILE CREATION WITH DATA AFTER RUNNING SCRIPT
![iamgeofexcelfile](https://user-images.githubusercontent.com/73634132/137447486-c4029ba3-d049-4c1f-9500-4bbc38c1f801.png)
It contains all the information about every match.

#TO RUN THIS ON YOUR LOCAL

First fork this to your profile, then clone it to your desktop
Then install libraries
 npm install minimist
 npm install axios
 npm install pdf-lib
 npm install excel4node
 npm install jsdom


To run this project fire this command in the terminal
   node --source="https://www.espncricinfo.com/series/icc-cricket-world-cup-2019-1144415?ex_cid=ipl2021:google_cpc:search:dsa_feed:msn&gclid=Cj0KCQjw-4SLBhCVARIsACrhWLVv_gGK-NVT1D36fINNofAKdPwIUdjuwmCWE-PuMJCRl3rGClYu5N4aAuJWEALw_wcB" --dataFolder=data --excel=WorldCup.csv


#CONTACT
In case of any suggestions or enquires, feel free to contact me on my email id.
email id - ajju9990.ak@gmail.com


