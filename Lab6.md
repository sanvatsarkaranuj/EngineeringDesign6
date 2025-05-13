# Lab 6: Node.js and Pystache
### Instructions:
Go to lesson 6 in the GitHub repository. Install Node.js and run hello-world.js, hello.js, and http.js. For each, refresh the webpage to see the server activities. Then, installl Pystache 
and run say_hello.py that uses the template say_hello.mustache. Document your results to your GitHub repository.

---
## Node.js:
Node.js was already installed on my mac so I was able to start with running the scripts. To do this I executed the following series of commands: 
- `cd ~/iot/lesson6`
- `node hello-world.js` (I pressed ctrl C to exit the server)
- `node hello.js` (I pressed ctrl C to exit the server)
- `node http.js` (I pressed ctrl C to exit the server)
![Image](https://github.com/user-attachments/assets/842b0c3f-2e42-4ea8-b46e-390d76d7cb80)

Each running webpage displayed different server activity. As can be seen in the image above, hello-world.js did not display any server activity. Hello.js responded to a refresh with outputting
"response end call done" and "request end event fired" to the terminal. Lastly, http.js responded with a count of how many times the webpage had been refreshed. 

The following images show what each webpage looked like: 

### hello-world.js:
![Image](https://github.com/user-attachments/assets/d8a8939a-475e-4b9e-97a0-e5c76c1f4899)

### hello.js:
![Image](https://github.com/user-attachments/assets/ba4dad6a-b0b4-4a5b-96a8-94a60212e9a1)

### http.js:
![Image](https://github.com/user-attachments/assets/e967443f-9e4d-4e15-a06c-f32a1a6f0fb2)

---
## Pystache:
I installed Pystache on my mac using the command `pip3 install pystache`. Then I executed the following commands in order to 
run say_hello.py that uses the template say_hello.mustache.
- `cd ~/iot/lesson6`
- `cat say_hello.mustache`
- `cat say_hello.py`
- `python3 say_hello.py`

The results of these commands are shown below:
![Image](https://github.com/user-attachments/assets/a629ad75-0a51-48b0-812e-c3cb677a6949)
