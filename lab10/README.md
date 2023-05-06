#Lab 10

This lab serves as an introduction to BlockChain and Mining. 

From the lesson 10 folder in the iot repository, I ran hash_value.py twice and compared the two results.   
I also ran snakecoin.py  
Third step was to run snakecoin-server-full-code.py on Terminal 1 and mine a new block on Terminal 2  
I cloned this repo to get the python_blockchain-app and uncommented the last line of node_server.py in VIM  
git clone https://github.com/satwikkansal/python_blockchain_app.git  
I then ran node_server.py on Terminal 1 and run_app.py on Terminal 2 and checked the url of both to interact with the website  

These are the commands I used as per the professors instructions:  
$ cd ~/iot/lesson10  
$ cat hash_value.py  
$ python3 hash_value.py  
$ python3 hash_value.py  
$ python3  
>>> import hashlib  
>>> m = hashlib.sha256(b"hello, world")  
>>> m.hexdigest()  
>>> m.digest_size  
>>> m.block_size  
>>> exit()  
$ cd ~/iot/lesson10  
$ cat snakecoin.py  
$ python3 snakecoin.py  

$ cat snakecoin-server-full-code.py  
$ python3 snakecoin-server-full-code.py  
$ cd  

$ sudo pip3 install markupsafe==2.0.1  
$ python3 snakecoin-server-full-code.py  

$ curl "localhost:5000/txion" \
     -H "Content-Type: application/json" \
     -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'  
$ curl localhost:5000/mine  

$ git clone https://github.com/satwikkansal/python_blockchain_app.git  
$ cd ~/python_blockchain_app  
$ vim node_server.py  
$ python3 node_server.py  

$ vncserver  
$ cd ~/python_blockchain_app   
$ python3 run_app.py   
<img width="1440" alt="Screenshot 2023-05-06 at 18 27 56" src="https://user-images.githubusercontent.com/109293108/236650025-849783a0-f8f8-4952-bacb-53ee9b176835.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 28 00" src="https://user-images.githubusercontent.com/109293108/236650026-29a9042b-2f4f-44a2-82ef-5f665014b52d.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 28 06" src="https://user-images.githubusercontent.com/109293108/236650027-8fa6e180-da39-449c-a9e4-f32d1f2402e5.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 28 11" src="https://user-images.githubusercontent.com/109293108/236650028-e13589b5-9134-495c-9513-d564c0002224.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 31 12" src="https://user-images.githubusercontent.com/109293108/236650029-5337e3d3-3d87-4d0d-b4e5-023caf6ff383.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 31 16" src="https://user-images.githubusercontent.com/109293108/236650030-a9429dee-a472-4d23-87f5-e75d87e919e4.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 31 18" src="https://user-images.githubusercontent.com/109293108/236650031-a6d27dde-5579-4b7c-8399-13cfd8d619d2.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 31 20" src="https://user-images.githubusercontent.com/109293108/236650032-e8ba3bb8-578b-4cfc-b9c6-09718db0b275.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 31 22" src="https://user-images.githubusercontent.com/109293108/236650033-5b8d63be-54ae-4223-8d90-b5be8451d5ca.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 31 26" src="https://user-images.githubusercontent.com/109293108/236650034-945b9479-202b-4893-ad08-ad5e31220287.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 32 52" src="https://user-images.githubusercontent.com/109293108/236650036-ba951c85-c007-493b-898e-1d5905a909fc.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 33 38" src="https://user-images.githubusercontent.com/109293108/236650037-96b2b734-6427-49c4-88d3-ff82184dfd28.png">
<img width="1440" alt="Screenshot 2023-05-06 at 18 52 58" src="https://user-images.githubusercontent.com/109293108/236650040-ed356fca-a867-4405-99c2-2caa3e7d0552.png">  
<img width="1440" alt="Screenshot 2023-05-06 at 19 03 34" src="https://user-images.githubusercontent.com/109293108/236650041-b9cbe709-698c-47fb-b119-b82106a54572.png">
<img width="1440" alt="Screenshot 2023-05-06 at 19 05 04" src="https://user-images.githubusercontent.com/109293108/236650042-bb35f98e-2509-4b55-9359-8e4280eb1b08.png">
<img width="1440" alt="Screenshot 2023-05-06 at 19 05 06" src="https://user-images.githubusercontent.com/109293108/236650043-fc718efe-3f4e-478f-b966-a617fdc8c5fe.png">
















