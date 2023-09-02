# File-Integrity-Monitoring-System

File Integrity Monitoring Systems (FIMS) are a critical tool for maintaining the security and 
integrity of computer systems. They are designed to monitor file systems and detect any 
unauthorized changes or modifications to critical files. FIMS can be used in a wide range of 
applications, including intrusion detection, compliance monitoring, and malware detection.

![image](https://github.com/yashikanasa/File-Integrity-Monitoring-System/assets/117389788/f58f9f93-82cd-4e72-b9bc-0d846d75b53c)

Monitoring Modules
1. Hash Monitoring: The hash comparison method in the code is used to detect changes in a 
file. When the method is selected, a thread is created. It calculates the initial hash of the file using 
the SHA-256 algorithm.
2.  Directory Monitoring: The code implements a feature called "Directory Monitoring" which 
monitors the specified directory and its subdirectories for changes, and logs the events to a GUI 
window.
3. Metadata Monitoring: The metadata_monitoring function sets up a new thread, which will 
run the meta_loop function. The meta_loop function monitors a file located at the global path and 
prints changes to its size, modification time, and metadata (for an image or video files) to the 
terminal.

The Python libraries used are :
1. os 
2. hashlib 
3. threading 
4. tkinter
5. time 
6. logging 
7. datetime 
8. watchdog 
9. exifread 
10. xlsxwriter 
11. json 
12. requests 
13. moviepy 
