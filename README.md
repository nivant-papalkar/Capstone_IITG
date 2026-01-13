# Nivant_CapstoneProject


Dynamic Pricing System for Urban Parking Spaces


Introduction

Managing parking in urban areas is becoming increasingly complex due to growing populations and limited
space. This project presents a dynamic pricing system that aims to optimize parking lot usage and reduce
congestion. By simulating real-time pricing adjustments based on various influencing factors, the system
provides an intelligent solution for urban parking management. The approach includes processing
streaming data in batches and visualizing pricing strategies using Bokeh in Google Colab. The project is
designed to be simple, understandable, and effective for practical learning and implementation.

Technology Stack

The project is built using reliable and easy-to-understand tools that are commonly used in data processing
and visualization:
Python: Core programming language for all data handling and simulations.
Pandas: Efficient data processing and management library.
Numpy: Library for handling numerical calculations smoothly and quickly.
Bokeh: Python library used to create interactive visualizations, making it easier to understand
pricing trends.

System Workflow


The system follows a simple and practical workflow that makes it easy to understand and execute:

Step 1: Load the parking lot dataset directly into Google Colab for easy access and processing.

Step 2: Process the dataset in simulated batches to mimic real-time data flow. This allows us to
create the effect of streaming without needing complex server setups.

Step 3: Apply three pricing models to calculate the dynamic prices for each parking lot:
Linear Occupancy Model: Increases the price directly in proportion to how full the parking lot is.
This is a basic but important pricing strategy.
Demand-Based Model: Uses multiple factors such as occupancy, queue length, nearby traffic,
special events, and vehicle type to calculate a more responsive and fair price.
Competitive Pricing Model: Adjusts prices based on simulated competitor pricing to ensure our
parking lot remains competitive in the market.

Step 4: Visualize the price changes over time using Bokeh plots, which help in quickly comparing
pricing trends across different models and parking lots




Visual Architecture

graph TD

 A[dataset.csv] --> B[Google Colab Notebook]
 
 B --> C[Model 1: Linear Pricing]
 
 B --> D[Model 2: Demand-Based Pricing]
 
 B --> E[Model 3: Competitive Pricing]
 
 C --> F[Bokeh Visualization]
 
 D --> F
 
 E --> F
 

Project Files

Dynamic_Pricing_RealTime.ipynb : The Google Colab notebook that contains the complete
batch simulation and visualization code.

dataset.csv : The dataset used for simulating parking lot activity, which includes key features
such as occupancy, queue length, and traffic.

README.md : This file, which explains the project structure, tools, and workflow.

problem_statement.pdf : The original problem statement provided for the project.



Final Output

The final output of this project is a set of clear, interactive visualizations showing how the prices change in
each parking lot over time. These visualizations allow easy comparison between the three pricing strategies
and provide useful insights into how dynamic pricing can improve parking lot management.
The notebook is fully designed to work in Google Colab using batch simulation, which ensures fast
performance and easy access without requiring advanced server setups

 
