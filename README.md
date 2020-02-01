# AttendanceSheet
A scanner program that saves the time of scanning and osis number of students to be uploaded to google sheets. The time of scans are calculated to display the time a student has particiapted in a after school activity 

# Installation
* [Connect to google sheets](https://www.twilio.com/blog/2017/02/an-easy-way-to-read-and-write-to-a-google-spreadsheet-in-python.html) 
* [Video Tutorial](https://www.youtube.com/watch?v=cnPlKLEGR7E)
* Rename quickstart-00000.json to creds.json

Change some values
```python
mainSheet = client.open("NAME-OF-YOUR-SHEET").get_worksheet(1) #<-- Change number to the indexed number of a sheet 
signSheet = client.open("NAME-OF-YOUR-SHEET").get_worksheet(2) #<-- Change number to the indexed number of a sheet
eventSheet = client.open("NAME-OF-YOUR-SHEET").get_worksheet(3) #<-- Change number to the indexed number of a sheet
```
