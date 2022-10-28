# VAS
Its a Voter Authentication System implemented using python for scanning CNIC card against a given CNIC data.
Three main libraries numpy,pyzbar and cv2 are used in this project.
A file name "Authorised.txt" was opened in both reading and writing mode containing CNIC data covered by the QR of the CNIC.
If the scanned qr code data matches to those of the text file data, the Authorised voter is displayed on the camera screen named "Voter Authentication System" and viceversa.
