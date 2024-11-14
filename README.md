# Sorting Visualizer

A web-based tool to visualize popular sorting algorithms. This Sorting Visualizer project provides an interactive experience for understanding how various sorting algorithms work through real-time animations.

## Live Demo
Check out the live demo [here](https://kunall0880.github.io/Sorting-Visualizer/).

## Features
- **Interactive Visualization**: Watch sorting algorithms in action.
- **Multiple Algorithms Supported**:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
- **Controls**:
  - **Speed Adjustment**: Set the speed of the visualization.
  - **Array Size Control**: Change the number of elements to visualize.
  - **Random Array Generation**: Generate a new random array at any time.
  - **Reset**: Clear and reset the array to start fresh.

## Technologies Used
- HTML
- CSS
- JavaScript

## File Structure

- `index.html`: The main structure of the application with controls for selecting algorithms, adjusting array size, and speed.
- `app.js`: Contains the main functionality for handling user interactions, rendering the array, and initiating the sorting process.
- `helper.js`: Defines the `Helper` class, responsible for managing visual effects like marking elements, pausing between operations, and swapping elements.
- `sort-algorithms.js`: Implements various sorting algorithms within the `sortAlgorithms` class. Each algorithm uses the `Helper` class for visual feedback.

## Usage
1. Visit the [live demo](https://kunall0880.github.io/Sorting-Visualizer/).
2. Choose a sorting algorithm from the dropdown menu.
3. Adjust the array size and visualization speed as desired.
4. Click "Sort" to start the sorting visualization.
5. Use "Generate Array" to create a new random array.
6. Press "Reset" to clear the array and select a new algorithm if needed.

## Getting Started (Local Setup)
To run the project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/kunall0880/Sorting-Visualizer.git
