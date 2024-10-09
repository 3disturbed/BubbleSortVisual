# Bubble Sort Visualizer

Visualize **Bubble Sort** and **Enhanced Bubble Sort** algorithms with interactive, step-by-step animations.

![BubbleSort](https://github.com/user-attachments/assets/f1d4f655-fa93-485f-afd8-10614761cf93)

**Access the Visualizer**: Click [here](https://3disturbed.github.io/BubbleSortVisual/bubblesort.html) to open the Bubble Sort Visualization tool.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [How to Use the Visualizer](#how-to-use-the-visualizer)
- [Understanding Bubble Sort](#understanding-bubble-sort)
- [Understanding Enhanced Bubble Sort](#understanding-enhanced-bubble-sort)
- [Applications](#applications)
- [Contribute](#contribute)
- [Acknowledgments](#acknowledgments)

## Introduction

Bubble Sort is a fundamental algorithm used to sort an array of numbers into ascending numeric order. This visualization tool provides a step-by-step graphical representation of the Bubble Sort and its enhanced version, allowing you to interactively see how the algorithms work internally.

Whether you're a student learning sorting algorithms or a developer looking to understand Bubble Sort better, this tool offers an engaging way to explore the sorting process.

## Features

- **Interactive Visualization**: Watch the sorting process in real-time with dynamic animations.
- **Step-by-Step Execution**: Control the speed of the visualization to better understand each operation.
- **Enhanced Bubble Sort**: Explore optimized versions of Bubble Sort that reduce the number of passes.
- **Educational Insights**: Gain deeper insights into how Bubble Sort operates and its computational complexity.
- **Responsive Design**: Accessible on various devices, including desktops, tablets, and smartphones.

## How to Use the Visualizer

1. **Access the Visualizer**: Click [here](https://3disturbed.github.io/BubbleSortVisual/bubblesort.html) to open the Bubble Sort Visualizer in your web browser.
2. **Customize Your Array**: Adjust the size and values of the array you wish to sort.
3. **Choose Sorting Algorithm**: Select between standard Bubble Sort and Enhanced Bubble Sort.
4. **Control the Visualization**:
   - **Play/Pause**: Start or pause the animation.
   - **Step Forward/Backward**: Move through the sorting steps manually.
   - **Adjust Speed**: Change the speed of the animation to your preference.
5. **Analyze the Process**: Observe how elements are compared and swapped to achieve a sorted array.

## Understanding Bubble Sort

Bubble Sort is one of the simplest sorting algorithms. It repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeated until the list is sorted.

### How It Works

1. **Comparison**: Compare each pair of adjacent elements.
2. **Swapping**: Swap them if the first element is greater than the second.
3. **Passes**: Repeat the process for each element in the array. After each pass, the largest unsorted element "bubbles up" to its correct position.
4. **Completion**: The algorithm completes when no swaps are needed on a new pass, indicating that the array is sorted.

### Complexity

- **Time Complexity**: 
  - Worst and Average Case: O(n²)
  - Best Case: O(n) (when the array is already sorted)
- **Space Complexity**: O(1) (in-place sorting)

## Understanding Enhanced Bubble Sort

Enhanced Bubble Sort introduces optimizations to the standard algorithm to improve its efficiency.

### Optimizations

1. **Early Termination**: If during a pass no swaps are made, the algorithm terminates early as the array is already sorted.
2. **Reduced Comparisons**: After each pass, the next pass can ignore the last sorted elements, reducing the number of comparisons needed.

### Benefits

- **Performance Improvement**: Reduces the number of unnecessary passes, especially on nearly sorted arrays.
- **Efficiency**: Lower average time complexity in practice compared to the standard Bubble Sort.

## Applications

- **Educational Tools**: Helps students understand the basics of sorting algorithms.
- **Algorithm Visualization**: Assists developers and learners in visualizing how Bubble Sort operates.
- **Interactive Learning**: Provides an engaging way to explore algorithmic concepts and improve problem-solving skills.

## Contribute

Contributions are welcome! If you have suggestions for improvements, new features, or find any bugs, feel free to:

- **Open an Issue**: Describe the problem or suggestion.
- **Submit a Pull Request**: Provide your code changes and enhancements.

Please ensure that your contributions adhere to the project's coding standards and include appropriate documentation.

## Acknowledgments

- **Inspired By**: The need to make learning algorithms more interactive and engaging.
- **Special Thanks To**:
  - **Sazzzel the Student**: For insightful feedback and testing.
  - **Kevin at CodeInstitute**: For inspiring the necessity of visualization in learning.




---
