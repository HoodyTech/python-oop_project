# Learn OOP with Python
object oriented programming project with python:
Here we are simulating a virtual world populated by 100,000 people. We want to know from what population density people are less agreeable than the average.
When we run the program, a window displays a graph concerning the population density according to average agreeableness.

# Installing dependencies
To plot graphs, you need to install matplotlib:

pip install matplotlib

# Data
We provide you with 100,000 agents, courtesy of PPLAPI. Remember to unzip the document!

unzip agents-data.zip

If you want to generate new ones, enter the following command:

./download_agents -d agents-data.json -c 100000

# Lunch the program
./script.py agents-100k.json
