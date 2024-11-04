##                     Homework 7   - Docker and Python
This repository contains the dependencies and code for Homework 7 combining Docker with Python program that generates a QR code PNG file that points to my GitHub repository.

###Project Setup

  On cloning the repository, please run
  
  docker build -t qrcode .
  
  docker run --name my_qrcode -e QR_CODE_DIR=test -v .:/app  qrcode --url "https://github.com/mallikakasi"
  

### Generated a QR code that points to my GitHub repository , Given below MY QRCODE IMAGE 

![image](https://github.com/user-attachments/assets/f474e1a4-adf1-461a-b585-ea7d1f7cdf31)


### Logs to show Successfully generated QRCODE and saved in test directory 

![image](https://github.com/user-attachments/assets/f203e63a-e3e6-43fe-8c57-95ab39975a44)




