# 2023 Sioux Falls Canaries Analytics 
This repository contains two Python scripts to be used to analyze excel output files from a Rapsodo InGame system and to analyze a TXT game play by play from the American Association of Professional Baseball. This was a side project that I worked on in conjunction with the pitching coach for the Sioux Falls Canaries while working as a Rapsodo Operator/Analyst during the 2023 season. I did not develop a web scraper to be used with these files, so all input files were manually imported. I appreciate any feedback/advice given!

AA Baseball TXT Game Play by Plays: http://baseball.pointstreak.com/textstats/menu_main.html?leagueid=193&seasonid=33660

## Description of Folders/Files 
| File Name | Description | 
|-----------|-------------|  
|Pitch Count Data| This folder contains CSV files with pitchers, individual pitch count reports for each pitcher, and cumulative season reports for each pitcher|
|Rapsodo Image Files|Folder containing outputs from Rapsodo analysis, separated by pitcher| 
|Raw Rapsodo Game Data| Raw Excel files imported from Rapsodo Live Cloud used for Rapsodo Analysis script| 
|TXT Game Play by Plays | Folder containing raw TXT files with play by plays for every 2023 Sioux Falls Canaries game, used for Pitch Count Analysis|  
|Pitch Count Analysis.ipynb|Python script that calculates opposing batting averages for Canaries pitchers based on the current pitch count| 
|Rapsodo Analysis.ipynb|Python script to clean and analyze Excel outputs from a Rapsodo InGame system| 
