# React Accordion Component

A modern, interactive accordion component built with React that supports both single and multiple selection modes.

## 🚀 Features

- **Single Selection Mode**: Only one accordion item can be expanded at a time
- **Multiple Selection Mode**: Multiple accordion items can be expanded simultaneously
- **Toggle Button**: Easy switching between single and multiple selection modes
- **Responsive Design**: Works well on desktop and mobile devices
- **Smooth Interactions**: Clean UI with expand/collapse animations
- **Customizable**: Easy to modify styles and add new questions

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/ZahidMiana/Accordion-react-project.git
cd reactproject1
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## 🎯 Usage

The accordion component automatically loads with sample FAQ data. You can:

1. **Single Selection Mode** (default): Click on any question to expand it. Clicking another question will collapse the previous one.

2. **Multiple Selection Mode**: Click the "Enable Multi Selection" button to allow multiple items to be expanded at once.

3. **Toggle Expansion**: Click on any expanded item to collapse it.

## 🏗️ Project Structure

```
src/
├── components/
│   └── accordian/
│       ├── index.jsx      # Main accordion component
│       ├── data.js        # Sample FAQ data
│       └── style.css      # Component styles
├── App.js                 # Main application component
└── index.js              # Application entry point
```

## 🔧 Customization

### Adding New Questions

Edit the `src/components/accordian/data.js` file to add or modify questions:

```javascript
const data = [
    {
        id: '1',
        question: 'Your question here?',
        answer: 'Your answer here'
    },
    // Add more items...
];
```

### Styling

Modify the `src/components/accordian/style.css` file to customize the appearance:

- `.wrapper` - Main container
- `.accordian` - Accordion container
- `.item` - Individual accordion item
- `.title` - Question/header area
- `.content` - Answer/content area

## 🛠️ Available Scripts

### `npm start`
Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`
Launches the test runner in interactive watch mode.

### `npm run build`
Builds the app for production to the `build` folder.

### `npm run eject`
**Note: This is a one-way operation. Once you `eject`, you can't go back!**

## 🔄 Component Logic

The accordion uses three main state variables:
- `selected`: Tracks the currently selected item in single mode
- `enableMultiSelection`: Boolean flag for selection mode
- `multiple`: Array of selected items in multi-selection mode

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with [Create React App](https://github.com/facebook/create-react-app)
- Uses React Hooks for state management
- Responsive design principles

---

**Made with ❤️ using React**
