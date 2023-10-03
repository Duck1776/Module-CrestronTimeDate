# Module-CrestronTimeDate

        ___     ________         * * * * * * * ====================
       |\  \   |\   ____\         * * * * * *  ====================
        \ \  \  \ \  \___|       * * * * * * * ====================
      __ \ \  \  \ \  \  ___      * * * * * *  ====================
     |\  \\_\  \  \ \  \|\  \    * * * * * * * ====================    __
     \ \________\  \ \_______\   ==================================  <(o )___
      \|__1776__|   \|_______|   ==================================   ( ._> /
                                 ==================================    `---' 


This is a very simple Time and Date module.

This will report the following:

     STRING    Time+Date                (Date Format + " - " + Time Format)
     STRING    Year_Long                (ex. 2023)
     STRING    Year_Short               (ex. 23)
     STRING    Month_Long               (ex. January)
     STRING    Month_Short              (ex. Jan)
     STRING    Month_Number             (ex. 1)
     STRING    Day_ofthe_Week_Long      (ex. Sunday)
     STRING    Day_ofthe_Week_Short     (ex. Sun)
     STRING    Day_ofthe_Month_Number   (ex. 1)
     STRING    Hour_In_24               (ex. 17 for 5pm)
     STRING    Hour_In_12               (ex. 05 for 5pm)
     STRING    Minute                   (ex. 35)

Date Format Options are:

     ANALOG    DEFAULT  1d  January 01, 2023
     ANALOG             2d  01 January 2023
     ANALOG             3d  Jan 01, 2023
     ANALOG             4d  01 JAN 2023
     ANALOG             5d  01/01/23

Time Format Options are:

     ANALOG    DEFAULT  0d  24 Hour
     ANALOG             1d  12 Hour + AM/PM

Enjoy!
