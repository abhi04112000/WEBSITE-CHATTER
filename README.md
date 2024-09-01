# Vehicle Routing Problem with Time Window

## Project Overview

This project focuses on developing an optimization model for route planning with installation scheduling to minimize total operational costs. The problem is identified as a Vehicle Routing Problem with Time Windows (VRPTW). The project includes the formulation and solution of a Mixed Integer Linear Programming (MILP) model, utilizing advanced techniques to enhance performance.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Model and Techniques](#model-and-techniques)
- [Results](#results)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)

## Project Description

The aim of this project is to optimize route planning for vehicles with specific time windows for service requests. The problem is formulated as a Vehicle Routing Problem with Time Windows (VRPTW). The project involves the development of a MILP model using the Miller-Tucker-Zemlin (MTZ) formulation to prevent sub-loops and the implementation of the Branch and Cut method using CPLEX software for solving the model efficiently.

## Features

- **Optimization Model:** Developed a MILP model to minimize total operational costs for route planning and installation scheduling.
- **MTZ Formulation:** Used Miller-Tucker-Zemlin (MTZ) constraints to prevent sub-loops in the routing solution.
- **Branch and Cut Method:** Implemented the Branch and Cut method with CPLEX software to solve the optimization model.
- **Performance Enhancement:** Achieved exact solutions for 15 requests and worked on valid cuts and constructive heuristics to improve performance.

## Technologies Used

- Python
- CPLEX Optimization Studio
- Mixed Integer Linear Programming (MILP)
- Miller-Tucker-Zemlin (MTZ) Constraints
- Branch and Cut Method

## Model and Techniques

### MILP Model and MTZ Formulation

- **MILP Model:** Developed a Mixed Integer Linear Programming model to handle route planning and installation scheduling.
- **MTZ Constraints:** Applied Miller-Tucker-Zemlin constraints to ensure no sub-loops in the routes.

### Branch and Cut Method

- **Branch and Cut:** Implemented the Branch and Cut algorithm using CPLEX software to efficiently solve the MILP model.
- **Performance Enhancements:** Focused on valid cuts and constructive heuristics to improve the efficiency of the solution.

## Results

- **Exact Solutions:** Successfully obtained exact solutions for 15 requests.
- **Performance Improvements:** Worked on valid cuts and constructive heuristics to enhance the model's performance.

## Usage

1. **Data Preparation:** Prepare your input data for route requests and time windows in the required format.
2. **Configuration:** Adjust configuration settings for the MILP model in the project files.
3. **Run Optimization:** Execute the optimization script using CPLEX to obtain solutions for the vehicle routing problem.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. For more details, see the [CONTRIBUTING](CONTRIBUTING.md) guidelines.
