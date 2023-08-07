# Project Readme: Solving the 3x5y Problem

## Overview

The 3x5y Problem Solver is a software application designed to find and generate ideal numbers, which are positive integers having only 3 and 5 as prime divisors. An ideal number can be expressed in the form of 3^x * 5^y, where x and y are non-negative integers. This project aims to efficiently identify and display such numbers within a given range, providing a valuable tool for mathematicians, programmers, and enthusiasts interested in exploring these unique mathematical properties.

## Features

1. Ideal Number Generator: The core functionality of this application is to generate ideal numbers in the form of 3^x * 5^y for a specified range of x and y values.

2. Range Selection: Users can input a range of non-negative integers for both x and y to explore ideal numbers within that specified range.

3. Filter Options: Users can set optional filters to limit the ideal numbers generated based on certain criteria, such as the total number of prime factors or the sum of x and y.

4. User-Friendly Interface: The application provides an easy-to-use command-line interface, allowing users to input their preferences and view the generated results conveniently.

## Installation

1. Clone the repository from GitHub:

```
git clone https://github.com/your-username/3x5y-problem-solver.git
cd 3x5y-problem-solver
```

2. Ensure you have Python 3 installed on your system.

3. Install the required dependencies using pip:

```
pip install -r requirements.txt
```

## Usage

1. Run the program by executing the main script:

```
python main.py
```

2. Follow the on-screen instructions to input the desired range for x and y values.

3. Optionally, you can set additional filters based on the total number of prime factors or the sum of x and y.

4. The program will then calculate and display the ideal numbers matching the specified criteria.

## Examples

Example 1: Finding ideal numbers in the range of 0 <= x <= 3 and 0 <= y <= 4 without any filters:

```
Enter the range for x (non-negative integers):
0 3
Enter the range for y (non-negative integers):
0 4
```

Output:

```
Ideal Numbers:
3^0 * 5^0 = 1
3^0 * 5^1 = 5
3^0 * 5^2 = 25
3^1 * 5^0 = 3
3^1 * 5^1 = 15
3^2 * 5^0 = 9
```

Example 2: Finding ideal numbers in the range of 0 <= x <= 4 and 0 <= y <= 4 with a filter on the sum of x and y (x + y <= 5):

```
Enter the range for x (non-negative integers):
0 4
Enter the range for y (non-negative integers):
0 4
Enter the maximum sum of x and y (non-negative integer):
5
```

Output:

```
Ideal Numbers:
3^0 * 5^0 = 1
3^0 * 5^1 = 5
3^1 * 5^0 = 3
```

## Contributions

Contributions to this project are welcome! If you find any bugs, have suggestions for improvements, or want to add new features, feel free to open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

We would like to express our gratitude to the open-source community and the developers of the Python programming language and associated libraries for their valuable contributions that made this project possible.
