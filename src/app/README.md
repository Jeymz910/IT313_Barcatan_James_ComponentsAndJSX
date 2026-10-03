# IT313 Components and JSX

## Problem

The activity is about creating a Student Roster Card Renderer using React Native. Each student is displayed using a reusable StudentCard component.

## Component Structure

### StudentRoster

- Manages the student list
- Calculates the total number of students
- Uses map to create StudentCard components
- Includes a button to reverse the student list

### StudentCard

- Receives student information through props
- Uses props destructuring
- Displays the student's name, course, and units
- Conditionally displays Full Load

## React Concepts Used

- Functional Components
- Props
- Props Destructuring
- JSX Expressions
- Conditional Rendering
- List Rendering
- Keys

## Key Experiment

The project temporarily uses the array index as a key to demonstrate how keys behave when the list is reversed. The final version restores the student's unique ID as the key.

## How to Run

Install the project dependencies:

npm install

Start the Expo project:

npx expo start