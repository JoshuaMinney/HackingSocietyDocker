This is the linux fundamentals docker for the Hacking society 15/10/2025 session.
To run this, please use your linux virtual machine. This is designed for ubuntu, other operating systems may work but not guaranteed.
This is to be used in conjunction with the https://tryhackme.com/jr/HackingSocietyLinuxF room I created.


To download this:
1) git clone https://github.com/JoshuaMinney/HackingSocietyDocker.git
2) cd HackingSocietyDocker/
3) unzip zippedDockers.zip
   
To run:
1) sudo apt install docker.io
2) sudo docker build -t dockerimage:1.0 .
3) sudo docker run -it --entrypoint bash dockerimage:1.0

To exit:
1) write exit in terminal
