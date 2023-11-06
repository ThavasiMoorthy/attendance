# attendance
This is the code to scan the barcode of the student and mark the scanned barcode will be marked as present in an excel sheet
How to run the code
To run the code you need install the required modules. The required modules are openCV, pyzbar, openpyxl, winsound, os.
To install the modules you need to open teh command prompt and type the following command in it.
To install OpenCV -----> pip install opencv-python
To install pyzbar -----> pip install pyzbar
To install openpyxl ----> pip install openpyxl
where as the other two module are pre installed in python so you don't need install it.
The scanned barcode will be stored in an excel sheet where the program file is placed.
If the file doesn't exist it create a file by it's own and the store the data of the scanned barcode.
If the file already exist it simply stores the data of the scanned barcode. 
