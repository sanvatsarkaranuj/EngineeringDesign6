# Lab 10 :Blockchain
### Instructions: 
Review lesson 10 in the GitHub repository.
- Run hash_value.py twice and compare results
- Run snakecoin.py
- Run snakecoin-server-full-code.py on Terminal 1 and mine a new block on Terminal 2
- Clone Python blockchain app and uncomment the last line of node_server.py
- Run node_server.py on Terminal 1 and run app.py on Terminal 2  </br>

Document results to your GitHub repository.

---
## Running hash_value.py
I was able to run the hash_value.py program twice by executing the following code: 
```
$ cd ~/iot/lesson10
$ cat hash_value.py
$ python3 hash_value.py
$ python3 hash_value.py
```
Note that the cat command allowed me to view the file contents before running the program. The purpose of this program was to generate hash values for several different variables. </br>

The results for my first and second runs are pictured below:
![Image](https://github.com/user-attachments/assets/a1b92d70-38d0-4ed8-bfe9-c989c8ab16e5)

## Running snakecoin.py
I was able to run snakecoin.py by executing the following code: 
```
$ cd ~/iot/lesson10
$ cat snakecoin.py
$ python3 snakecoin.py
```
Note that the cat command allowed me to view the file contents before running the program. The purpose of this program was to build a small blockchain using Python. </br>

The results of running this program are pictured below: 
![Image](https://github.com/user-attachments/assets/e8b73470-f131-4b44-9cda-115be1303452)

While this server was running, on a seperate terminal I ran the following code: 
```
$ curl "localhost:5000/txion" \
     -H "Content-Type: application/json" \
     -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'
$ curl localhost:5000/mine
```

This code created a transaction and mined a new block at http://127.0.0.1:5000/mine. The result of the transaction is pictured below: 
![Image](https://github.com/user-attachments/assets/17b67fa4-7de1-4c60-becc-a4c306eb9cca)

## Python blockchain app
In order to run the Python blockchain app, I needed two terminals. The following code was ran on Terminal 1: 
```
$ git clone https://github.com/satwikkansal/python_blockchain_app.git
$ cd ~/python_blockchain_app
$ nano node_server.py
$ python3 node_server.py
```
The following code was ran on Terminal 2: 
```
$ cd ~/python_blockchain_app
$ python3 run_app.py
```
To view this app, I went to  http://127.0.0.1:5000/. I posted initial content to the app (Block #1) and requested to mine it. Then I went to http://127.0.0.1:8000/mine to get a confirmation that my block had been mined. 
![Image](https://github.com/user-attachments/assets/92efbf9c-ed56-4644-9861-60bbf62701b8)

Lastly, I went back to the main page and pressed "Resync" to see my updated changes to my blockchain. 
