# LaserPecker-Burntest
gcode file for the LaserPecker Burntest

Power (S) goes from 75 to 255 in Steps of 20
Speed (F) goes from 25 to 1000 in Steps of about 108 

![IMG_0374](https://user-images.githubusercontent.com/91568406/149345468-a7ef7c37-b314-4860-b472-f175b25bf7a2.JPG)

There is also an Excel sheet that I used to "Program" the gcode.
You need to export that as TXT file and then do a lot of search and replace
- Search for all TABs and replace with Spaces
- Search for all , and replace with .
- Search for " and replace with nothing
- Search for  X and Space and replace with X
- Search for  Y and Space and replace with Y
- Search for  F and Space and replace with F
- Search for  S and Space and replace with S
- Search for  P and Space and replace with P
- Search for Space and Space and replace with Space
Delete the first 17 Lines of the code until M05 S0
