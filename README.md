# Week 12 Day 2 Lab: Manipulating Data in a JSON file to display on a Graph

## Analyzing NBA Teams' Win-Loss Records Using Chart.js

### Objective

 The goal of this lab is to familiarize yourself with JSON data manipulation and visualization using the Chart.js library. You will use a provided JSON file containing NBA teams' win-loss records and create a bar chart to visualize the data.

&nbsp;

![Pie Chart Example](./Nba%20pie%20chart%20example.png)


### Task 1: Create a React app

**Description:**
Set up a new React application using create-react-app or any other method of your choice. This app will serve as the foundation for displaying data using Chart.js.

**Steps:**
1. Initialize a new React application.
2. Set up project structure and dependencies.

### Task 2: Create a pie chart displaying only the wins of every team

**Description:**
Create a pie chart that displays only the wins of each NBA team. Each slice of the pie chart should represent the number of wins for a specific team.

**Steps:**

1. Read the NBA team data from the provided JSON file.
2. Extract the wins data for each team.
3. Generate a pie chart using Chart.js, with labels representing team names and values representing total wins.
4. Display the wins-only pie chart on your webpage.

### Task 3: Create a pie chart displaying only the losses of every team

**Description:**
Create a pie chart that displays only the losses of each NBA team. Each slice of the pie chart should represent the number of losses for a specific team.

**Steps:**

1. Read the NBA team data from the provided JSON file.
2. Extract the losses data for each team.
3. Generate a pie chart using Chart.js, with labels representing team names and values representing total losses.
4. Display the losses-only pie chart on your webpage.

By completing these tasks, you'll create a React application that utilizes Chart.js to visualize NBA team data from a JSON file, displaying both wins and losses separately on pie charts.

## Stretch Goal

Try using the modal bootstrap component to display the different charts. And have it to where you can click a button and have the modal for the wins show on the page and a button to show the modal with the losses.

## Resources

[Chart.js Documentation](https://www.chartjs.org/docs/latest/getting-started/)

[Bootstrap Modal Documentation](https://react-bootstrap.github.io/docs/components/modal)
