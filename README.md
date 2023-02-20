# Hyperledger Fabric Installation

Hey there! This is <a href="https://www.linkedin.com/in/rohit-patil-06a5261b6/" target="_blank">Rohit Patil</a> . Welcome to the Hyperledger Fabric installation guide that's as easy as telling a joke and its the only Hyperledger Fabric Installation that you need! Before we get started with installation guide for Hyperledger Fabric, I have a quick request. If you find this guide useful why not give this repository a star⭐🤩? which is present at top-right of screen. It's like giving me a virtual high-five, and we could all use a little extra encouragement these days. And how about connecting on [LinkedIn](https://www.linkedin.com/in/rohit-patil-06a5261b6/)?

This must be done in **Ubuntu Terminal** :

Let's start with some harmless fun - we're going to make /etc/hosts a little more open-minded. Don't worry, we're not trying to change its political views or anything, we're just giving it some extra permissions. So, type in the following commands:


```
sudo chmod 666 /etc/hosts
sudo chmod 777 /etc/hosts
```
Now that we've convinced /etc/hosts to be a little more flexible, let's introduce it to some new friends. The first one is called curl, and it's great at fetching things from the internet. We'll use it to install some necessary packages. Type in:


```
sudo apt install curl 
sudo apt-get update
```
Now that curl has introduced us to some new friends, let's invite them over for a little party. We can install them separately, or we can use a single command to bring them all together:

```
sudo apt-get install git curl docker.io docker-compose nodejs npm 
sudo chmod 777 /var/run/docker.sock
```
Now that our new friends are all settled in, it's time to introduce them to our project. We're going to clone it from GitHub using the following commands:

```
git config --global core.autocrlf false
git config --global core.autocrlf false 
```
Now, it's time to run the script that will get things rolling:

```
sudo curl -sSL http://bit.ly/2ysbOFE | bash -s 1.4.4
```
Once the script is done, we'll head over to our new project folder and create our first network. It's like having a housewarming party, but for a new network:

```
cd fabric-samples/first-network
```
```
fabric-samples/first-network$ ./byfn.sh generate
fabric-samples/first-network$ ./byfn.sh up
```

Wait for the BIG END in your terminal and that's it! You've successfully installed Hyperledger Fabric, and you've had a few laughs along the way. Remember to always treat your files with kindness and understanding, and they'll return the favor. Happy blockchain-ing!
