# ReduxCart

# ReduxCart — Cart project with Redux & Redux Toolkit

A small demo shop that showcases how to build and manage a shopping cart with Redux Toolkit and React. It demonstrates modern Redux patterns (slices, async thunks), global UI state for notifications, and cart persistence via HTTP. To support the database, I used Firebase

- Live stack: React 18, Redux Toolkit, React-Redux, Fetch API, CSS


## Screenshots

- Success flow (cart saved): see the green “Success!” banner in the header (Image 1)
  <img width="1871" height="968" alt="ad05d614-fe6c-42ba-8668-94bff4e5e962" src="https://github.com/user-attachments/assets/4d58b431-b027-42c4-b876-66484cfb61b6" />


- Error flow (fetch failed): see the red “Error!” banner in the header (Image 2)
  <img width="1862" height="925" alt="a75deb11-669c-4e74-a60a-006f67035224" src="https://github.com/user-attachments/assets/855eb611-c9ba-4824-b680-7c1fc26d2195" />

## Features

- Add products to cart, increase/decrease item quantity, remove when it reaches zero
- Cart visibility toggle from header
- Derived totals in the cart UI
- Global notifications for async operations (success, pending, error)
- Fetch-and-persist cart state via async actions
- Clean Redux Toolkit architecture with small, focused slices



## Installation

Prerequisites:
- Node.js 18+ and npm

Steps:
1. Clone the repository
   ``` 
   git clone https://github.com/Lucekkk/Cart-project-with-redux-and-redux-toolkit.git
   cd Cart-project-with-redux-and-redux-toolkit
   ```
2. Install dependencies
   ``` 
   npm install
   ```
3. Start the dev server
   ``` 
   npm start
   ```
   The app will be available at http://localhost:3000





## License

This project is for learning/demo purposes. Add your preferred license text here.
