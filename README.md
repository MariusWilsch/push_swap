# push_swap

## Project Overview

`push_swap` is a C project aimed at sorting data on a stack with a limited set of instructions, using the lowest possible number of actions. The challenge involves utilizing algorithms to find the most optimized solution for data sorting. This project specifically leverages the Radix Sort algorithm to efficiently sort numbers in ascending order.

## Features

- **Stack Manipulation**: Utilizes two stacks (`a` and `b`) to sort integers.
- **Limited Instructions**: Employs a predefined set of operations (like `sa`, `pb`, `ra`, etc.) to manipulate stack elements.
- **Radix Sort Algorithm**: Implements the Radix Sort algorithm for efficient sorting, minimizing the number of operations required.
- **Error Handling**: Robust error handling for invalid inputs and scenarios.
- **Efficiency**: Focuses on minimizing the number of operations to sort the stack.

## Installation

Ensure you have a C compiler (GCC recommended) and `make` installed. Clone the repository and compile the project:

```bash
make
```

## Running the Program

Execute `push_swap` with a list of integers to sort:

```bash
./push_swap 42 21 17 6 0 -3
```

The program outputs a series of operations to sort the stack `a` in ascending order.

## Testing

Testing can be performed by manually checking the output with an arbitrary set of integers or by using a checker program (if provided) to verify the correctness of the output.
