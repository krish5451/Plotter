# Plotter
Plotter - Seismic Fragility Analysis 
# Seismic Fragility Curve Analysis Application - User Guide

## Introduction

Welcome to the Seismic Fragility Curve Analysis Application! This user guide provides step-by-step instructions on using the application to analyze seismic data and derive seismic fragility curves while quantifying uncertainty. The application is designed to assist you in plotting the probability of a structure exceeding different damage states as a function of ground motion intensity.

## Prerequisites

Before using the application, please ensure you have the following:

- Windows operating system (the executable file provided is specific to Windows)
- Your seismic data in an Excel file format (e.g., .xlsx or .xls)
- Knowledge of the yield point and ultimate point values for the analysis (in mm units)

## Step 1: Load Seismic Data

1. Launch the Seismic Fragility Curve Analysis Application by double-clicking the executable file (e.g., `seismic_plotter.exe`) provided to you.

2. Once the application window appears, click the "Load Data" button to load your ATC 40 Excel file.

3. A file dialog will open. Browse and select your ATC 40 Excel file containing seismic data. The file should have a column labeled "SdCapacity" representing the seismic capacity of structures.

4. After selecting the file, the application will process and display the data in the text area on the application window.

## Step 2: Input Expected Values

1. In the application window, you will find two input fields labeled "Yield Point" and "Ultimate Point."

2. Input the expected Yield and Ultimate Point values in mm units. These values represent the ground motion intensities at which different damage states may occur.

3. Ensure the input values are in mm units for accurate analysis.

## Step 3: Analyze Data and Quantify Uncertainty

1. click the "Analyze Data" button after inputting the expected values.

2. The application will perform optimization and Monte Carlo simulation in the background to quantify the appropriate uncertainty.

3. Once the analysis is complete, the application will display the optimization results and the quantified uncertainty in the text area.

## Step 4: Plot Seismic Fragility Graph

1. After the analysis, the application will automatically plot the seismic fragility graph based on the quantified uncertainty and the expected values you provided.

2. The graph will show the probability of exceeding each damage state (Slight, Moderate, Severe, Complete) as a function of ground motion intensity (Spectral Displacement in mm).

3. The legend on the graph will indicate different damage states using specific markers and colors.

## Step 5: Save the Seismic Fragility Graph

1. Once the graph is plotted, the application will prompt you to save the graph.

2. Choose the file path and name for saving the graph. You can select the desired location and provide a name for the PNG file.

3. Click "Save" to save the seismic fragility graph in PNG format.

## Conclusion

Congratulations! You have successfully used the Seismic Fragility Curve Analysis Application to load your seismic data, input expected values, analyze and quantify uncertainty, and plot the seismic fragility graph. The plotted graph will help you understand the probability of exceeding damage states at varying ground motion intensities. Should you have any questions or issues, don't hesitate to contact the developer through the "Contact via Email" or "Visit Website" buttons provided in the application. Enjoy using the application for your seismic analysis needs!
