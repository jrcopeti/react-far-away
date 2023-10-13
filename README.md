# 🌍 React Far Away

Built using React, the **far-away** app ensures you never forget anything for your trips. Easily add items to your checklist, mark them as packed, and get on with your adventure!

![Screenshot](public/screenshot1.png)

## 📝 Features:

- **Add Items**: Use the form to quickly add new items to your packing list.
- **Check off Packed Items**: Simply click on an item to mark it as packed.
- **Delete Items**: Remove items you no longer need in your list with ease.
- **Sort Items**: Choose to display items sorted by added order, description or packed status.
- **Clear All**: With one button, clear your entire list after confirming.
- **Statistics**: At a glance, view the total number of items, how many are packed, and your packing percentage.

## 🏗 App Structure:

- `App`: The root component.
- `Logo`: Displays the far-away logo.
- `Form`: Responsible for adding new items.
- `PackingList`: Handles the display and functionality of the items list.
- `Stats`: Showcases statistics like total count and packing percentage.

## 📘 React Concepts Learnt:

- **Props**: Transfer data from parent to child components.
- **State & useState**: Maintain and manage dynamic data within components.
- **Functional Updates**: Update state based on the previous state (useful when the next state depends on the previous one).
- **Event Handlers**: Functions passed as props to handle specific events within child components.
- **Parent to Child Communication**: Parent component `App` interacts with child components by passing down data and callback functions through props.

## 🚀 Getting Started:

1. Clone the repository.
2. Navigate to the project directory and run `npm install`.
3. Once dependencies are installed, run `npm start`.
4. Open a browser and go to `http://localhost:3000`.

Happy packing! 🎒
