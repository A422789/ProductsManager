# Products Manager - CRUDS System

A powerful and responsive Product Management System built with pure (vanilla) JavaScript. This project demonstrates a complete **C**reate, **R**ead, **U**pdate, **D**elete, and **S**earch (CRUDS) application that leverages the browser's **Local Storage** for data persistence, allowing users to manage products without needing a backend server.

**Live Demo:** [**Try the Products Manager Here**](https://a422789.github.io/ProductsManager/ )

---

## 🌟 About The Project

This project is an advanced JavaScript application designed to manage a product inventory. It provides a user-friendly interface to perform all essential data operations. The system automatically calculates the total price based on inputs and saves all data locally, ensuring that your product list is preserved between browser sessions.

The primary goal was to build a real-world, practical application using vanilla JavaScript to master core concepts like DOM manipulation, data management, and event handling.

---

## ✨ Key Features

This project is packed with features that make it a robust management tool:

*   **Create Products:** Add new products with details like title, price, taxes, ads, and discount.
*   **Automatic Price Calculation:** The system automatically calculates and displays the total price in real-time as you type.
*   **Read & Display Data:** All products are neatly displayed in a table, showing all their details.
*   **Update Products:** Easily select a product to edit its information. The form will be pre-filled with the existing data for quick modification.
*   **Delete Products:** Remove a single product or clear the entire product list with a single click.
*   **Bulk Creation:** Create multiple copies of the same product at once using the "Count" field.
*   **Advanced Search:** Dynamically search for products by either **Title** or **Category**, with the results updating instantly.
*   **Data Persistence:** All product data is saved in the browser's `localStorage`, so you never lose your work.
*   **Responsive UI:** The interface is clean, intuitive, and updates dynamically in response to user actions.

---

## 🛠️ What I Learned

This project was a fantastic learning experience that solidified my understanding of several key JavaScript concepts:

*   **DOM Manipulation:** Extensive use of JavaScript to interact with and update the HTML content dynamically (e.g., creating the product table, updating form states).
*   **Local Storage API:** Mastered how to use `localStorage` to `setItem`, `getItem`, and manage data persistence by converting objects to JSON strings and back.
*   **CRUD(S) Logic:** Implemented the complete logic for creating, reading, updating, deleting, and searching data within an array of objects.
*   **Event Handling:** Managed various user events like `onclick` and `onkeyup` to trigger functions and create an interactive experience.
*   **State Management:** Handled application state (like 'Create' vs 'Update' mode) to change the behavior of the UI and functions accordingly.
*   **Code Organization:** Structured the JavaScript code into logical functions (`create`, `showData`, `deleteProduct`, `updateProduct`, etc.) for better readability and maintainability.

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository to your local machine:**
    ```bash
    git clone https://github.com/A422789/ProductsManager.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd ProductsManager
    ```
3.  **Open the `index.html` file in your favorite browser.** That's it!

---

## 💡 Future Enhancements

- [ ] Add data validation to ensure all required fields are filled correctly.
- [ ] Implement a feature to export the product list to a CSV file.
- [ ] Add sorting functionality to the product table (e.g., sort by price or title ).
