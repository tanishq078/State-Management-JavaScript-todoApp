# TODO App with State Management in DOM

This TODO app is a purely frontend application built using JavaScript to manage state directly in the DOM, similar to how libraries like React function. This README provides a guide to implementing and using the app, focusing on the essential functions: `addTodoToDom`, `removeTodoFromDom`, `updateTodoInDom`, and `updateState`.

## Project Overview

The goal of this project is to manage a list of TODO items, with each item having a title, description, and unique identifier. The app uses state management directly in the DOM to add, remove, and update TODO items efficiently.

## Getting Started

1. Clone the repository to your local machine.
2. Open the `index.html` file in a web browser to see the TODO app in action.

## State Structure

The state is an array of TODO objects, each with the following structure:

```javascript
const todos = [{
    title: "Go to gym",
    description: "Go to gym from 7-8PM",
    id: 1
}]
