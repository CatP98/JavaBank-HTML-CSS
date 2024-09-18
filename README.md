# JavaBank Web Application

## Overview

This project provides a basic web application for managing customer information. It includes pages for viewing a list of customers, adding new customers, viewing customer details, and handling cases where a user is not found. The application is styled with CSS and uses a simple directory structure for organizing HTML templates and assets.

### Languages

- **HTML**: Used for structuring the content of the web pages.
- **CSS**: Used for styling the web pages and ensuring a consistent look and feel.

### Frameworks and Libraries

- **Flexbox**: CSS layout module used for creating responsive web layouts.
- **Google Fonts**: Used for custom fonts (e.g., Roboto).

### Tools

- **Apache HTTP Server**: Used for hosting the HTML pages.
- **VS Code**: A code editor used for editing HTML and CSS files.
- **Developer Tools**: Built-in browser tools for debugging and testing web pages.

## Project Structure

```plaintext
webapp/
│
├── assets/
│   └── (Include any images or other static files here)
│
├── templates/
│   ├── index.html
│   ├── add-customer.html
│   ├── customer-details.html
│   └── user-not-found.html
│
└── styles/
    └── stylesheet.css
```
## Implementations

### HTML Pages

- **`index.html`**: The main page displaying a list of customers.
- **`add-customer.html`**: A form for adding a new customer.
- **`customer-details.html`**: Page for displaying detailed information about a specific customer.
- **`user-not-found.html`**: Page displayed when a user is not found in the system.

### CSS Styles

- **`stylesheet.css`**: Contains styles for all HTML pages, including layout and design elements.

## Build and Deploy

### Build

- No specific build process is required for this project as it consists of static HTML and CSS files.

### Deploy

**Hosting with Apache HTTP Server:**

1. **Install Apache HTTP Server on your system.**

2. **Create a project directory under the server's root directory:**

   - **Ubuntu/Debian:**
     ```bash
     sudo mkdir /var/www/html/javabank
     ```

   - **ArchLinux/Manjaro:**
     ```bash
     sudo mkdir /srv/http/javabank
     ```

   - **macOS:**
     ```bash
     mkdir /opt/homebrew/var/www/javabank
     ```

3. **Place `index.html`, `add-customer.html`, `customer-details.html`, `user-not-found.html`, and `stylesheet.css` into the appropriate directories.**

4. **Start the Apache server:**

   - **Ubuntu/Debian:**
     ```bash
     sudo systemctl start apache2
     ```

   - **ArchLinux/Manjaro:**
     ```bash
     sudo systemctl start httpd
     ```

   - **macOS:**
     ```bash
     brew services start httpd
     ```

## Future Enhancements

- **Responsive Design:** Improve mobile responsiveness and layout adjustments.
- **JavaScript Integration:** Add JavaScript functionality for dynamic interactions.
- **Backend Integration:** Connect to a backend service for managing customer data dynamically.
- **Accessibility Improvements:** Enhance accessibility features for better usability.

Feel free to adjust any of the content to better fit your project needs!
