# Clash-Free University Timetable Generation

## Project Overview

This project aims to automate the creation of clash-free university timetables using a genetic algorithm approach. It addresses the challenges of manual timetable generation, which can be time-consuming and prone to errors, especially in complex university settings.

## Key Features

Automated timetable generation: Relies on genetic algorithms to efficiently create clash-free timetables.
Considers multiple constraints: Takes into account student courses, teacher availability, and resource constraints.
Flexible and adaptable: Can be customized to accommodate various university requirements and scheduling preferences.
Potential for time savings: Automates a tedious and time-consuming process, freeing up human resources for other tasks.
## Technologies Used

- Python
- Pandas
- CSV
- Random
- Copy
## Project Structure

- README.md 
- Proj1_18I0526_18I0523.ipynb (Jupyter Notebook containing project code)
- Courses.csv (contains sample course information)
- teachers.csv (contains sample teacher details)
- studentNames.csv (contains sample student names)
- studentCourses.csv (sample specifies courses for each student)
- requirements.txt (libraries to install beforehand)
## Usage

- Clone this repository.
- Ensure you have Python and the required libraries installed 
- Open Proj1_18I0526_18I0523.ipynb in Jupyter Notebook.
- Run the code cells to execute the project.
## Genetic Algorithm Approach

- Chromosome Representation: Each timetable is encoded as a chromosome.
- Fitness Function: A fitness function is defined to evaluate the quality of a timetable, with a fitness of 0 indicating a clash-free solution.
#### Genetic Operators:
- Mutation: Randomly modifies a timetable to create new variations.
- Selection: Chooses fitter timetables for further evolution.
- Iterative Process: The algorithm repeatedly applies genetic operators until a clash-free timetable is found or a specified stopping criterion is met.
## Contributing

We welcome contributions and feedback! Please feel free to open issues or pull requests.

## License

This project is licensed under the MIT License.
