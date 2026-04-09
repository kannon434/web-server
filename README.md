# comp2322project
Environment

Python 3.12.6

How to run
1. open and run the server.py, you should see the server started in the console
2. open the browser and type 127.0.0.1:8080 to access the index.html page
3. you can change the path like 127.0.0.1:8080/test.txt,127.0.0.1:8080/cat.jpg to access different content in the server
4. you can also open different pages at the same time to check the multithreaded function works well
5. Additionally, you can enter commands like curl.exe -i 127.0.0.1:8080 to send the GET request in windows, or the curl.exe -I -H "If-Modified-Since: Your-Time" 127.0.0.1:8080 to check the 304 Not Modified and so on
6. You can check the log.txt for all the access event information

Reminder
Since github does not allowed to upload write only file, so if you want to test the 403 forbidden by permission denied, you may need to change the permission of the secret.txt and cancel the read permission
