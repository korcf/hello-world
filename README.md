# Viurtual Environment Example

This is a simple example of deploying an application using a virtual environment.

## Deploy the application

### Remote

Connect to the remote system:
```
ssh -i mykey.pem myusername@mydomain.example
```
Check pip installation:
```
$ pip -V
```
Check venv installation:
```
$ python3 -m venv -h
```
Clone the repo:
```
$ git clone git@github.com:korcf/hello-world.git
```
Create a virtual environment:
```
$ cd hello-world
$ python3 -m venv .ve
$ source .ve/bin/activate
```
Install requirements:
```
$ pip install -r requirements.txt
```
Run the application:
```
$ python main.py
```

