# kattest
Script for testing your code with the sample data files provided by Kattis.
![](kattest-output.JPG)

## Supported languages
* C
* C++
* Java
* Python 3

## How to install
On Ubuntu / Mint, install <i>kattest</i> with the following commands:
```
sudo apt update
sudo apt install python3-dev python3-pip python3-setuptools
sudo pip3 install kattest
```
On other systems, install `kattest` by using `pip`:
```
pip install kattest
```

## How to run
Make sure that your solution has the following format:
```
[Problem ID].[extension]
Example: exponial.cpp
```
Run the following command from the same directory as your solution:
```
kattest [Problem ID].[extension]
Example: kattest exponial.cpp
```
Enjoy!
