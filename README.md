# RealTimeWeatherMonitor
A real time weather monitoring system using open mpi
Weather Forecasting using Open MPI
This repository contains a parallelized weather forecasting program implemented in C using the Open MPI library. The program simulates weather conditions for different locations and computes various statistics, such as average temperature, maximum temperature, minimum temperature, and variance.

Prerequisites
Make sure you have the Open MPI library installed on your system. You can install it using the package manager specific to your operating system.

Output
The program will output the weather forecast for each location, including the predicted weather condition and temperature. Additionally, it will display statistics such as average temperature, maximum temperature, minimum temperature, and variance for each MPI process. The global averages and extrema across all processes will also be printed.

File Structure
weather_forecast.c: The main source code file containing the MPI parallelized weather forecasting program.
README.md: This file providing information about the program, its compilation, execution, and output.
License
