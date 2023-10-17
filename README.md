[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y7PSI74)
# __Time and Date Reporting for Crestron Control Systems__ 
___

      __         __         __         __         __         __
    <(o )___   <(o )___   <(o )___   <(o )___   <(o )___   <(o )___     GOD BLESS AMERICA
     ( ._> /    ( ._> /    ( ._> /    ( ._> /    ( ._> /    ( ._> /     JULY 4TH, 1776
      `---'      `---'      `---'      `---'      `---'      `---' 
## What does this module do?                                   

This is a very simple Time and Date module that will report the following:

| TYPE   | VAR                      | EXAMPLE                               |
|--------|--------------------------|---------------------------------------|
| STRING | Time+Date                | (Date Format + " - " + Time Format)   |
| STRING | Year_Long                | (ex. 2023)                            |
| STRING | Year_Short               | (ex. 23)                              |
| STRING | Month_Long               | (ex. January)                         |
| STRING | Month_Short              | (ex. Jan)                             |
| STRING | Month_Number             | (ex. 1)                               |
| STRING | Day_ofthe_Week_Long      | (ex. Sunday)                          |
| STRING | Day_ofthe_Week_Short     | (ex. Sun)                             |
| STRING | Day_ofthe_Month_Number   | (ex. 1)                               |
| STRING | Hour_In_24               | (ex. 17 for 5pm)                      |
| STRING | Hour_In_12               | (ex. 05 for 5pm)                      |
| STRING | Minute                   | (ex. 35)                              |
                     

### Date Format Options are:

| TYPE   | DEFAULT | VALUE | FORMAT             |
|--------|---------|-------|--------------------|
| ANALOG | __D__   |1d     | January 01, 2023   |
| ANALOG |         |2d     | 01 January 2023    |
| ANALOG |         |3d     | Jan 01, 2023       |
| ANALOG |         |4d     | 01 JAN 2023        |
| ANALOG |         |5d     | 01/01/23           |


### Time Format Options are:
| TYPE   | DEFAULT | VALUE | FORMAT             |
|--------|---------|-------|--------------------|
| ANALOG | __D__   |0d     | 24 Hour            |
| ANALOG |         |1d     | 12 Hour + AM/PM    |


__*Enjoy!*__

## TO-DO
- [X] PROVIDE MODULE
- [X] PROVIDE EXAMPLE PROGRAM
- [X] DETAIL README

---
<br>

[![Duck1776 GitHub stats](https://GitHub-readme-stats.vercel.app/api?username=Duck1776)](https://GitHub.com/anuraghazra/GitHub-readme-stats) 

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Y8Y7PSI74)
