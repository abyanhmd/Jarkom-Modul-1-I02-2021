# Jarkom-Modul-1-I02-2021

Made by:

Abyan Ahmad (05111942000013)

Gede Yoga Arisudana (05111942000009)

Zulfiqar Rahman Aji (05111942000019)

## Problem 1


## Problem 2


## Problem 3


## Problem 4


## Problem 5


## Problem 6
The display filter to find the username is `ftp contains USER`
![6-USER](/Screenshot/6-USER.png)
The display filter to find the password is `ftp contains PASS`
![6-PASS](/Screenshot/6-PASS.png)

## Problem 7
The display filter to find Real.pdf is `ftp-data contains Real.pdf`

## Problem 8


## Problem 9


## Problem 10


## Problem 11
![Screenshot (583)](https://user-images.githubusercontent.com/74660281/134458818-a414fa6b-9ba7-4ecb-a0da-d844c63111b8.png)
In problem 11, we are needed to filter so that wireshark only picks up packets coming from port 80, and the key to solve this problem is word `from`, therefore we are going to use a display filter called `src` and then write the port number, thus we will get the capture filter, and the capture filter is `src port 80`

## Problem 12
![Screenshot (585)](https://user-images.githubusercontent.com/74660281/134458943-957e0c27-72c4-4b57-8e2a-8c53e318d823.png)
In problem 12, we are needed to filter so that wireshark only picks up packets containing port 21, and the key to solve this problem is word `containing`, therefore we are going to use only one display filter called `port` and then write the port number, thus we will get the capture filter, and the capture filter is `port 21`

## Problem 13
![Screenshot (587)](https://user-images.githubusercontent.com/74660281/134459124-83a2f4f1-db8c-436a-8fe7-4e6649decde2.png)
In problem 13, we are needed to filter so that wireshark only shows packets going to port 443, and the key to solve this problem is word `going`, therefore we are going to use a display filter called `dst` and then write the port number, thus we will get the capture filter, and the capture filter is `dst port 443`

## Problem 14
![14](https://user-images.githubusercontent.com/74660281/134459517-93e9ae03-70b7-4e1a-a4b4-f0189bb7a5eb.jpeg)
In problem 14, we are needed to filter so that wireshark only picks up packets going for kemenag.go.id, and the key to solve this problem is word `going`, therefore we are going to use a display filter called `dst` and then write the website link, and don't forget to do some activity in the website so the wireshark can show the picked up packet that are going for kemenag.go.id, thus we will get the capture filter, and the capture filter is `dst host kemenag.go.id`

## Problem 15
![Screenshot (590)](https://user-images.githubusercontent.com/74660281/134459222-4b61535d-4fcb-4620-a3a7-9b2c605b760e.png)
![Screenshot (591)](https://user-images.githubusercontent.com/74660281/134459225-d6cd9d23-3721-4ba9-a3c4-04baf523ba72.png)
In problem 15, we are needed to filter so that wireshark only picks up packets coming from your ip, and the key to solve this problem is word `coming`, therefore we are going to use a display filter called `src` and then write our ip address, and we can get our ip address by typing `ipconfig` in our command prompt, thus we will get the capture filter, and the capture filter is `src host 192.168.0.100`
