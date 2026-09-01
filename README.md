# 📦 Using Import in Node.js

A beginner-friendly Node.js project created to understand how to use **ES Module `import` and `export` syntax** in a Node.js application.

The project focuses on understanding how modules can be separated into different files and then imported wherever they are required.

## 🚀 Features

* Understanding ES Modules in Node.js
* Using `import` syntax
* Using `export` syntax
* Splitting code into multiple modules
* Importing functions from another JavaScript file
* Basic Node.js project structure
* Understanding modern JavaScript module syntax

## 🛠️ Technologies Used

* **Node.js**
* **JavaScript**
* **ES Modules**
* **npm**

## 📂 Project Structure

```text
useing-import-/
│
├── index.js          # Main application file
├── ...               # Supporting JavaScript modules
├── package.json      # Project configuration
└── README.md         # Project documentation
```

## 📚 Import & Export

JavaScript modules allow code to be divided into separate files and reused across an application.

### Export

A function or variable can be exported from a module:

```javascript
export function greet() {
    console.log("Hello World");
}
```

### Import

The exported function can then be imported into another file:

```javascript
import { greet } from "./greet.js";

greet();
```

For Node.js to interpret `.js` files as ES modules, the project can use:

```json
{
    "type": "module"
}
```

This allows the project to use modern `import` and `export` syntax.

## 🔄 How It Works

```text
JavaScript Module
       │
       │ export
       ▼
Another JavaScript File
       │
       │ import
       ▼
Main Application
       │
       ▼
    Execution
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Ganesh-Machale/useing-import-.git
```

### 2. Navigate to the project

```bash
cd useing-import-
```

### 3. Install dependencies

```bash
npm install
```

### 4. Run the project

```bash
node index.js
```

## 🧠 What I Learned

Through this project, I learned:

* What JavaScript modules are
* Difference between CommonJS and ES Modules
* How `import` works
* How `export` works
* How to organize JavaScript code into multiple files
* How Node.js handles ES Modules
* How `package.json` controls the module system
* Basics of writing reusable JavaScript modules

## 🔮 Future Improvements

Possible improvements include:

* Create multiple reusable modules
* Add default exports
* Practice named and default imports
* Use modules in an Express.js application
* Add external npm packages using ES Module syntax
* Build a small REST API using ES Modules

## 👨‍💻 Author

**Ganesh Machale**

Full Stack Web Developer | MERN Stack Developer

### GitHub

https://github.com/Ganesh-Machale

---

⭐ If you found this project useful, consider giving the repository a star!
