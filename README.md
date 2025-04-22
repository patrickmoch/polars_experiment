# polars_experiment

install if not pre-installed

curl (optional), use curl --version to see if installed

I recommend to use a virtual environment for testing or experiment purpose

python 3.11
If you are using Ubuntu 24.04 or higher you have to install it by yourself,
the distribution has 3.12 on board.

to install follow these steps:
- sudo add-apt-repository ppa:deadsnakes/ppa
- sudo apt update
- sudo apt install python3.11

For 3.12 there ist an workaround that although should work


packages:
- pandas
- polars
- pyspark

for spark you have to install a java runtime environment.

to check if java is installed try java -version fro example on linux shell

Ouput on Ubunut you may see like here

Command 'java' not found, but can be installed with:
sudo apt install openjdk-17-jre-headless  # version 17.0.14+7-1~24.04, or
sudo apt install openjdk-21-jre-headless  # version 21.0.6+7-1~24.04.1
sudo apt install default-jre              # version 2:1.17-75
sudo apt install openjdk-11-jre-headless  # version 11.0.26+4-1ubuntu1~24.04
sudo apt install openjdk-8-jre-headless   # version 8u442-b06~us1-0ubuntu1~24.04
sudo apt install openjdk-19-jre-headless  # version 19.0.2+7-4
sudo apt install openjdk-20-jre-headless  # version 20.0.2+9-1
sudo apt install openjdk-22-jre-headless  # version 22~22ea-1

I made my decision for openjdk 17 jre headless

