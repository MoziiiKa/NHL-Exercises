# Debugging Exercises for Scientific Programming

This repository contains a series of debugging exercises aimed at identifying and resolving bugs in various scientific programming scenarios. These exercises encompass a range of issues, from data type inconsistencies and implementation errors to more subtle bugs found in real-world tutorials.

## Exercise Summaries

### Exercise 1: Identifying Fruits by ID

- **Description**: A method designed to return the name of a fruit given its ID within a set of fruit names.
- **Issues**:
    1. **Incorrect Indexing**: Due to the unordered nature of sets in Python, indexing directly is not possible, leading to unreliable outputs.
    2. **Solution**: Convert the set to a list to enable stable indexing.

### Exercise 2: Swapping Coordinates in Arrays

- **Description**: A function intended to swap the x and y coordinates within an array of bounding box coordinates.
- **Issues**:
    1. **Obvious Error**: Incorrect assignment led to improper swapping.
    2. **Solution**: Ensure proper indexing and assignment during the swap to correct the logic.

### Exercise 3: Plotting Precision-Recall Curves

- **Description**: A method for plotting precision-recall curves from data contained within a CSV file.
- **Issues**:
    1. **Plot Display Issue**: The plot does not display correctly due to data not being correctly parsed or plotted.
    2. **Solution**: Convert string data to floats and correct the axis assignment.

### Exercise 4: Training a Generative Adversarial Network (GAN)

- **Description**: Code for training a GAN to generate images of handwritten digits, distinguishing between real and generated images.
- **Issues**:
    1. **Structural Bug**: Changing the batch size leads to a mismatch in the expected and actual sizes of tensors.
    2. **Cosmetic Bug**: Possible issues with the visualization or update logic of generated images.
    3. **Solutions**: Dynamically adjust tensor sizes and ensure correct update and display logic for generated images.

## Objectives

The primary objective of these exercises is to develop and refine debugging skills in scientific programming contexts. Through the process of identifying and resolving these issues, key insights into common programming pitfalls and their solutions were gained.

## Contributions

Feedback and contributions are welcome to enhance the solutions and approaches discussed.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
