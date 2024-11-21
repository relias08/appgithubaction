## This repository corresponds to Krish Naik's - [MLOPS Github Action With CICD Pipeline One Shot Tutorial](https://www.youtube.com/watch?v=ciqWMIf7Pz0) - 1hr 8mins --- this is the intro lesson

- Till 46:00 --- has intuition of CI CD pipeline wrt ML project I think 

- CRITICAL - 46:00 onwards --- shows a nice professional way of creating the following directory structure on laptop/github:
    - 'src' folder which contains the code (we update the code in this folder on the laptop from time to time and when we git push it to the remote Github server in the cloud, it will trigger that whole Github Actions CI CD pipeline I guess)
    - 'tests' folder which contains all the Unit Test files
    - README.md file
    - requirements.txt file 
(Note - he does not follow the above folder structure in the next lesson ie. [MLOPS Tutorial- Automating Workflow Of CI/CD for Dockerized Flask App Using Github Action](https://www.youtube.com/watch?v=9oALxmc5yEw) --- but I need to follow the src, test folder structure shown in this intro video for my ML projects because it looks very professional !!!)

- See (51:19) of current intro lesson for how to set up the "test_operation.py" file --- to set up the Unit Test for my ML program (ie. just import the new model and do an accuracy calculation)

- 54:30 onwards of current INTRO lesson shows how to set up the "cicd.yml" file which is stored in the .github/workflows folder. It controls the sequence of events in the Github Actions pipeline. (57:30) onwards has clean explanation of each line of the .yml file. Must use the .yml file in INTRO as template to create my .yml file for the ML project !!!