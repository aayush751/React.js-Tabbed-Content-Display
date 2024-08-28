# React.js Tabbed Content Display

This React.js project is a single-page application that provides an interactive interface to explore various aspects of React.js through a tabbed navigation system. Users can switch between different content sections by clicking on the tabs, with the corresponding content being dynamically rendered.

## Features

- **Tabbed Navigation**: The interface includes four tabs:
  - **Why React?**
  - **Core Features**
  - **Related Resources**
  - **React vs Js**
  
  Each tab corresponds to a different set of content related to React.js.

- **Dynamic Content Rendering**: The content displayed is dynamically rendered based on the active tab. The content is stored in a multi-dimensional array and is rendered using the `map` function.

- **State Management**: React's `useState` hook is used to manage the active tab state, ensuring that the correct content is displayed based on user interaction.

- **Responsive and Interactive UI**: The active tab is highlighted for a better user experience, making it clear which content is currently being viewed.

## Technologies Used

- **React.js**: For building the user interface and managing state.
- **JavaScript (ES6)**: For handling the logic and interactivity.
- **CSS**: For styling the components and enhancing the UI.

## Getting Started

### Prerequisites

To run this project, you'll need to have Node.js and npm (or Yarn) installed on your machine.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/react-tabbed-content.git
2. Navigate to the project directory:

   ```bash
   cd react-tabbed-content
3. Install the dependencies:

   ```bash
   npm install
   # or
   yarn install
###Running the Application

```bash
npm start
# or
yarn start

