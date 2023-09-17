# streaming_04_bonus
A bonus project using RabbitMQ

# Overview
This is additional practive working with streaming data and RabbitMQ. There are 3 different queues recieved by three workers. The first takes the nation and returns it in title case to a csv. The remaining 2 queues to the same operation to the local and varietal information.

# Data
The data was found on kaggle at [https://www.kaggle.com/datasets/dev7halo/wine-information]. It is a csv containing wine data for several varietals, location data, and other information. This uses just the varietal and location data. 

# 1. Running The Code
1.Open four separate terminal windows and navigate to the folder containing this project.
2.Activate the virtual environment
3.Start the "nation_consumer.py" file in one terminal.
4.Start the "local_consumer.py" file in a second terminal.
5.Start the "varietal_consumer.py" file in the third terminal.
6.Start the "wine_producer.py" file in the final terminal.

The processes will run until the end of the input file is reached or until the process is manually stopped. (This can be done by hitting CTRL + c)
The messages transmitted will now be in the respective CSV files.

# Processing
<img width="1440" alt="Screen Shot 2023-09-17 at 11 25 44 AM" src="https://github.com/AMersman/streaming_04_bonus/assets/91644580/8a2665d4-c96c-487b-9f33-955105136aad">
