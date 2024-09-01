# My To-Do List App

A simple and elegant To-Do List application built with React and Expo. This app helps you organize your tasks efficiently and boost your productivity.

## Features

- **Add Tasks:** Quickly add new tasks with a user-friendly interface.
- **Mark as Completed:** Mark tasks as completed with a single click.
- **Delete Tasks:** Remove tasks from the list when they are no longer needed.
- **Persistent Storage:** Tasks are stored locally, so your data is safe even after closing the app.
- **Responsive Design:** Optimized for all screen sizes and devices.


## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/) (or npm)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/my-todo-app.git
   cd my-todo-app
   ```

2. Install the dependencies:
   ```bash
   yarn install
   # or
   npm install
   ```

3. Start the development server:
   ```bash
   yarn start
   # or
   npm start
   ```

4. Open the Expo app on your mobile device or an emulator to view the project.

### File Structure

```
my-todo-app/
├── assets/               # Asset files like images, fonts, etc.
├── components/           # Reusable UI components
│   ├── TaskItem.jsx      # Component for individual task item
├── pages/                # Application pages/screens
│   ├── Home.jsx          # Main screen of the To-Do app
├── utils/                # Utility functions and helpers
│   ├── storage.js        # Functions for storing and retrieving data
├── App.js                # Main entry point of the app
├── app.json              # Expo configuration file
├── babel.config.js       # Babel configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── global.css            # Global styles
└── README.md             # Project documentation
```

### Configuration

- **Tailwind CSS** is used for styling the components. Make sure the `tailwind.config.js` is correctly set up with your custom theme and color configuration.
- **Expo CLI** is utilized to run the app on various devices. Follow the Expo documentation for any advanced configuration.

### Usage

1. **Adding Tasks:**
   - Click the "Add Task" button and type your task in the input field.
   - Press "Enter" or click the "Add" button to save the task.

2. **Marking Tasks as Completed:**
   - Click on the checkbox next to the task to mark it as completed.

3. **Deleting Tasks:**
   - Click on the trash icon next to the task to delete it.

### Built With

- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [Expo](https://expo.dev/) - A framework and platform for universal React applications
- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework

### Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new Pull Request

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Acknowledgements

- Thanks to the [React](https://reactjs.org/) and [Expo](https://expo.dev/) communities for their excellent tools and documentation.

---

Happy coding!

---

