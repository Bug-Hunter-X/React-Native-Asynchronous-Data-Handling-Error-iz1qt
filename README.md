# React Native Asynchronous Data Handling Error

This repository demonstrates a common error in React Native applications when dealing with asynchronous data fetching: `TypeError: Cannot read properties of null (reading 'name')`.

The error arises when attempting to access a property of an object before the data has been fetched and the object has been populated with data. This is often due to trying to access data within a component's render method before the `useState` or `useReducer` hook has finished updating the state.  The solution involves checking if the object is null or undefined before accessing its properties.

## Setup

1. Clone the repo
2.  `npm install`
3.  Run the app on your preferred emulator or device
