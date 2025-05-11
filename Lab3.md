# Lab 3:Python
### Instructions:
Go to the IOT GitHub repository and review lesson 3. Install required Python packages such as jdcal, astral, and geopy. Execute the following code: </br>
`cd ~/iot`,
`cd *3`,
`python3 julian.py`,
`python3 date_example.py`,
`python3 datetime_example.py`,
`python3 time_example.py`,
`python3 sun.py "New York"`,
`python3 moon.py`,
`python3 coordinates.py "Samuel C. Williams Library"`,
`python3 address.py "40.74480675, -74.02532861159351"`,
`python3 cpu.py`,
`python3 battery.py`,
`python3 documentstats.py document.txt`.
</br> 
Document the results to your GitHub repository. 

---
## Installing Necessary Python Packages
Before executing the python code I installed jdcal, astral and geopy. I did this by executing the following commands: `pip3 install jdcal`, 
`pip3 install astral`,
`pip3 install geopy`.

![Image](https://github.com/user-attachments/assets/f7c39777-c2fe-4e07-8282-4d65fe6a395b)
![Image](https://github.com/user-attachments/assets/85af60a7-ec40-421e-b126-57aa489ca785)

---
## Executing Python Code: 

## cd ~/iot
This command changes directories to iot. Note that in a previous lab the iot GitHub repository was copied. The directory "iot" has access to all files/folders from this repository. 

![Image](https://github.com/user-attachments/assets/dd3f7758-86fe-4637-a272-b47a19eec0ed)

## cd *3
This command changes directories to the first directory in iot that has a 3 in it. In this case this is the directory "lesson3"

![Image](https://github.com/user-attachments/assets/72ce5b92-1010-4a47-a02c-b8b4dcefc7e7)

## python3 julian.py
This command runs a python script called julian.py. It gives the calendar date, Julian date, and modified Julian date.
![Image](https://github.com/user-attachments/assets/7cbe03a9-8422-47f1-a9b8-5ac6e4b4411c)

## python3 date_example.py
This command runs a python script called date_example.py. It gets the current date, formats it in a couple different ways, and calculates the number of days since the first day of classes and until the last day of classes.
![Image](https://github.com/user-attachments/assets/f278f0f2-5792-4abf-a626-a5773346dea5)

## python3 datetime_example.py
This command runs a python script called datetime_example.py. It displays time in a couple different ways using the datetime and time modules.
![Image](https://github.com/user-attachments/assets/cf01bb64-4ed9-4318-b07d-d7d45127637e)

## python3 time_example.py
This command runs a python script called time_example.py. It continuously prints the current local time every 10 seconds until interrupted. You can stop this by pressing Ctrl C.
![Image](https://github.com/user-attachments/assets/071401c0-1b60-4fb1-86d3-e86eea444fd1)

## python3 sun.py "New York"
This command runs a python script called sun.py. It takes in a city, then gives data regarding the sun such as sunrise, sunset, dawn, dusk, and noon. 
![Image](https://github.com/user-attachments/assets/3357939c-7e99-479d-9f7c-c6898ed191c7)
![Image](https://github.com/user-attachments/assets/2ae84ea6-53cd-4f4f-812f-300c49a213cf)

## python3 moon.py
This command runs a python script called moon.py. It prints out the phases of the moon for the next 30 days starting with the current day.
![Image](https://github.com/user-attachments/assets/2ceeff05-506b-4037-8f82-3bb16e75eb5f)

## python3 coordinates.py "Samuel C. Williams Library"
This command runs a python script called coordinates.py. It takes in an address or landmark, uses the geopy library to find its geographical coordinates, and prints the full address along with its latitude and longitude.
![Image](https://github.com/user-attachments/assets/8839d27d-9bab-447a-ac05-e3f773258c4f)

## python3 address.py "40.74480675, -74.02532861159351"
This command runs a python script called address.py. It takes in geographical coordinates, uses the geopy library to find the corresponding address, and prints the full address along with its latitude and longitude.
![Image](https://github.com/user-attachments/assets/d0902bbd-d13e-4e35-8d6f-a52dde91cadb)

## python3 cpu.py
This command runs a python script called cpu.py. It displays the number of physical and logical CPU cores and prints CPU utilization percentages for each core every second for 10 seconds.
![Image](https://github.com/user-attachments/assets/814b9a15-ca22-4fc4-a02d-5ace3c9ce466)

## python3 battery.py
This command runs a python script called battery.py. It prints current battery statistics (percentage, seconds left, and whether or not computer is plugged in).
![Image](https://github.com/user-attachments/assets/8d41a318-9cdc-4d3c-ad0b-5fa1c57c80d4)

## python3 documentstats.py document.txt. 
This command runs a python script called documentstats.py. It reads a text file (in this case document.txt), counts the occurrences of wordsmexcluding common stop words, and prints the total word count along with the top ten most frequent words.
![Image](https://github.com/user-attachments/assets/d0a72d17-fe99-4ad8-aba1-3f8c1174a702)
