# Docker
Docker Course Exercises

## Ex1.1
![1.1](https://github.com/kettroni/Docker/blob/master/Exercise1/ex1_1.png "Exercise 1.1")

## Ex1.2
![1.2](https://github.com/kettroni/Docker/blob/master/Exercise1/ex1_2.png "Exercise 1.2")

## Ex 1.3
Firstly I ran ubuntu:16.04 container with:
![1.3p1](https://github.com/kettroni/Docker/blob/master/Exercise1/ex1_3p1.png "Exercise 1.3p1")

It opens up the root immediately and before installing curl to the container first I run apt-get update:
![1.3p2](https://github.com/kettroni/Docker/blob/master/Exercise1/ex1_3p2.png "Exercise 1.3p2")

Then after I run apt-get install curl:
![1.3p3](https://github.com/kettroni/Docker/blob/master/Exercise1/ex1_3p3.png "Exercise 1.3p3")

Now I can execute the given script from the exercise like so:
![1.3p4](https://github.com/kettroni/Docker/blob/master/Exercise1/ex1_3p4.png "Exercise 1.3p4")

## Ex 1.4  
First I created a docker file [Docker File](https://github.com/kettroni/Docker/blob/master/Exercise1/Ex1.4/Dockerfile).

Then I build it with: 
```
docker build -t curler .
```

Now that I had created the image I simply ran the program:  
![1.4](https://github.com/kettroni/Docker/blob/master/Exercise1/ex1_4.png "Exercise 1.4")
