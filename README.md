
# Finding lanes lines on the road

## Overview

- This project involves using OpenCV and Python to detect lane lines in images.
- The objective is to develop a pipeline that can detect road lines in a video stream captured by a roof-mounted camera.

## Basic Build Instructions

- Clone the repository.
- Launch the Finding_lanes.py Python file and execute the code. 
- The Python file is self-explanatory and explains the purpose of section of the code.

## Goal of the Project

- The project focuses on detecting road lines in an image using computer vision techniques without any machine learning involved.
- The aim is to identify the lane lines in different driving situations with varying levels of complexity.

## General Process

The process of detecting lane lines involves several steps, including:
- Filtering colors to eliminate non-line components.
- Applying a region filter to focus on the expected location of the lane lines
- Converting the image to grayscale.
- Computing the gradient with the Canny algorithm.
- Smoothing with a Gaussian filter.
- Finding lines with the Hough Transform.
- Smoothing the results with a moving average filter.

## Results

The project includes videos showing the results of the lane detection.


