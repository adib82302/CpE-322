# Lab 9

This lab is focused on YANG which is a framework that allows you to make UML diagrams of structured or unstructured data using code.

The terminal commands I used were:  
$ sudo pip3 install pyang plantuml  
$ mkdir ~/demo  
$ cp ~/iot/lesson9/intrusiondetection.yang ~/demo  
$ cd ~/demo  
$ cat intrusiondetection.yang  
$ pyang -f yin -o intrusiondetection.yin intrusiondetection.yang  
$ cat intrusiondetection.yin  
$ pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef  
$ cat intrusiondetection.uml  
$ python3 -m plantuml intrusiondetection.uml  

I also need to use $ pip install six to make the uml diagram. 

Below are images of my terminal and output image:  


<img width="1440" alt="Screenshot 2023-05-06 at 17 30 51" src="https://user-images.githubusercontent.com/109293108/236647500-599b77b4-cd34-4cd1-842d-51b313c37b40.png">

<img width="1440" alt="Screenshot 2023-05-06 at 17 30 55" src="https://user-images.githubusercontent.com/109293108/236647501-beec7492-c0e6-4b1c-9534-c3af0d6bc525.png">

<img width="1440" alt="Screenshot 2023-05-06 at 17 31 00" src="https://user-images.githubusercontent.com/109293108/236647502-372cee33-7474-496a-808a-3ca3c81cfe9e.png">

<img width="1440" alt="Screenshot 2023-05-06 at 17 31 12" src="https://user-images.githubusercontent.com/109293108/236647503-f639fd49-3f40-4c20-80ae-5db39f19415e.png">

<img width="1440" alt="Screenshot 2023-05-06 at 17 31 21" src="https://user-images.githubusercontent.com/109293108/236647504-a5b2fe96-19aa-4541-a247-929d5c57e000.png">

<img width="1440" alt="Screenshot 2023-05-06 at 17 31 30" src="https://user-images.githubusercontent.com/109293108/236647505-cadfa553-6545-40f3-9d1a-b80b007984f1.png">

<img width="1440" alt="Screenshot 2023-05-06 at 17 31 35" src="https://user-images.githubusercontent.com/109293108/236647506-d429f46f-a832-4f33-983f-87ed5d196aa2.png">

<img width="1440" alt="Screenshot 2023-05-06 at 17 31 40" src="https://user-images.githubusercontent.com/109293108/236647507-102c431b-93b5-46b7-9534-6f16e4d913ba.png">

<img width="1440" alt="Screenshot 2023-05-06 at 17 31 43" src="https://user-images.githubusercontent.com/109293108/236647508-d24da0ff-7f4f-49fb-a7e5-da55b799a540.png">

![intrusiondetection](https://user-images.githubusercontent.com/109293108/236647531-879a4ee9-32eb-4072-b9b6-9ed96d319cd3.png)



