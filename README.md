# _{Programming Language Selecter}_

#### By _**{Eleanor Quandt}**_

#### _{A webpage focused on finding you the best possible language to learn by asking five questions}_

## Technologies Used

* _HTML_
* _CSS_
*_JavaScript_


## Description

_{This application takes a number from user and returns a range of numbers from 0 to their inputted number and returns fun robot speech}_

## Setup/Installation Requirements

* _Open url https://github.com/eleanorq/Programming-Language-Selecter.git

*_Click green code button in top right of repository_

*_Copy HTTPS link_

*_Open command line and enter: cd [directory name]_

*_In command line enter: git clone [copied link]_

*_In command line enter: code ._
}


## Known Bugs

* _No known issues_


## License

_{If you run into any issues or have questions, ideas or concerns please don't hesistate to contact me at elquandt@gmail.com}_

Copyright (c) _4/8/22_Eleanor_Quandt_//


//Tests
Describe: beepBoop()

Test: It should return an array of numbers from 0 to the user's inputted number.
Code: beepBoop(5)
Expected Output: [0,1,2,3,4,5]

Test: It should return an array of numbers from 0 to user's inputted number, but for every number containing the number 1, "Beep!" will be returned in it's place.
Code: beepBoop(12)
Expected Output: [0, "Beep"!, 2, 3, 4, 5, 6, 7, 8, 9, "Beep!", "Beep!", "Beep!"]

Test: It should return an array of numbers from 0 to user's inputted number, but for every number containing the number 2 "Boop!" will be returned in it's place (and last rule still applies)
Code: beepBoop(5)
Expected Output: [0, "Beep!", "Boop!", 3, 4, 5]

Test:Test: It should return an array of numbers from 0 to user's inputted number, but for every number containing the number 3 "Won't you be my neighbor?!" will be returned in it's place (and last rulea still apply)
Code: beepBoop(5)
Expected Output: [0, "Beep!", "Boop!", "Won't you be my neighbor?!", 4, 5]
