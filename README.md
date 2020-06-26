# jenkins-docker

This github repository is fot the task 2 given by sir vimal daga 

Summary of the task:

Job 1 (github): This job pulls from this github url and paste it inside a directory called code. Also before copying,
it removes any existing code .

Job 2 (docker code): This jobs tests for the code in code/ directory and runs its respective docker image. Like if its php then it runs
php image.

Job 3 (docker test): This job test if the webpage is working or not. If it is not working then it triggers the next job

Job4 (mail): If the webpage is not working then this job is triggered and it emails the developer that there is an error.
