<p># Online-Attendance<br>
To run and execute the online attendance system, which consists of two main files encodeGenerator.py and main.py, follow these steps:</p>

<p>1. Install Required Dependencies:<br>
Ensure you have the necessary dependencies installed. You can install them using pip<br>
2. Generate Face Encodings:<br>
First, run the encodeGenerator.py script to generate face encodings for the images of individuals/students. Make sure to place your images in a directory and update the folderPath variable in encodeGenerator.py to point to that directory.<br>
3. Run the Main Script:<br>
Now, you can run the main.py script to start the attendance system. Ensure that your webcam is connected and functioning properly.<br>
This script continuously captures video frames from the webcam, detects faces, compares them with the known encodings, and records attendance if a match is found. The attendance data is stored in a CSV file named face_attendance.csv.<br>
4. Monitoring Attendance:<br>
You can monitor the attendance data by opening the face_attendance.csv file, which will contain the recorded attendance records.</p>

<p>Note:<br>
Ensure that both scripts (encodeGenerator.py and main.py) are in the same directory.<br>
Make sure to provide appropriate permissions for accessing the webcam if you're running the scripts in environments like Linux.<br>
You may need to customize the scripts according to your specific requirements, such as adjusting file paths or modifying the appearance of the user interface.</p>
