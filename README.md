# Product Management System - CRUD+S

A lightweight, frontend-only product management system built with vanilla HTML, CSS, and JavaScript. This application provides complete CRUD (Create, Read, Update, Delete) functionality plus Search capabilities without requiring any external libraries or frameworks.

![{8D11A6AC-C02C-4924-8307-240926FBE04D}](https://github.com/user-attachments/assets/0da82f90-d6fe-496e-8f64-4858f4e79b6c)


## Features

- **Create**: Add new products to your inventory
- **Read**: View all products in a clean table layout
- **Update**: Modify existing product details
- **Delete**: Remove products from your inventory
- **Search**: Filter products by name, category, or price
- **Local Storage**: Data persists between browser sessions
- **Responsive Design**: Works on desktop and mobile devices

## Validation Rules
When adding or updating products:

Title, Price, and Category are required fields

Price must be a valid number greater than 0

Maximum 49 products can be created in a single batch operation

## Technologies Used

- HTML5
- CSS3 (with Flexbox)
- JavaScript (ES6)
- Browser LocalStorage

## Getting Started

1. Clone the repository:
```bash
https://github.com/honizka/CRUDS-Operations-pureJS.git
```

2. Open the project directory:
```bash
cd CRUDS-Operations-pureJS
```

3. Launch the application:
- Simply open `index.html` in any modern web browser

## Usage

1. **Add a Product**: Click "Add Product" and fill in the form
2. **View Products**: All products display in the main table
3. **Edit Product**: Click the edit icon (✏️) on any product row
4. **Delete Product**: Click the delete icon (🗑️) on any product row
5. **Search**: Type in the search box to filter products

## Limitations

Since this is a frontend-only application:
- Data is stored in browser localStorage
- Data is specific to the device/browser
- Not suitable for multi-user environments

## Contributing

Contributions are welcome! Please open an issue first to discuss what you'd like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note**: Replace `your-username` in the clone URL with your actual GitHub username. Add an actual screenshot named `screenshot.png` in the root directory for the image to display properly.
