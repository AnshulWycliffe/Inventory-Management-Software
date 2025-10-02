
# 📦 Inventory-Management-Software

A comprehensive and user-friendly web-based system for efficiently managing inventory, built with Python, HTML, and CSS.

## ✨ Features

*   📊 **Dashboard Overview:** Get a quick glance at your inventory status, low-stock items, and recent activities.
*   📦 **Product Management:** Easily add, update, and remove products with detailed descriptions, quantities, and pricing.
*   🔍 **Advanced Search & Filtering:** Quickly locate specific items using powerful search capabilities and various filters.
*   🔔 **Low Stock Alerts:** Receive automated notifications for items falling below predefined stock levels to prevent shortages.
*   📝 **Order Tracking:** Monitor incoming and outgoing stock movements, providing a clear history of transactions.


## 🚀 Installation Guide

Follow these steps to get your local development environment up and running.

### Prerequisites

Ensure you have Python 3.8+ installed on your system.

### Manual Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AnshulWycliffe/Inventory-Management-Software.git
    cd Inventory-Management-Software
    ```

2.  **Create and activate a virtual environment:**
    It's highly recommended to use a virtual environment to manage dependencies.
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    This project likely uses Flask. Install it along with any other required packages.
    ```bash
    pip install Flask
    # If there's a requirements.txt file, use:
    # pip install -r requirements.txt
    ```

4.  **Database Setup:**
    The project uses `database.json` for data storage. Ensure this file exists in the root directory. If it's missing, you might need to create an empty JSON object `{}` in it, or run a setup script if provided.
    ```json
    # database.json (example content)
    {
      "products": [],
      "transactions": []
    }
    ```


## 💡 Usage Examples

To start the Inventory Management Software, run the `app.py` file from your activated virtual environment.

1.  **Run the application:**
    ```bash
    python app.py
    ```
2.  **Access the application:**
    Open your web browser and navigate to the address provided in the terminal (usually `http://127.0.0.1:5000/` or `http://localhost:5000/`).

3.  **Example Workflow:**
    *   **Adding a Product:** Navigate to the "Products" section and click "Add New Product." Fill in details like name, description, quantity, and price.
    *   **Updating Stock:** Find an existing product, select "Edit," and adjust the quantity.
    *   **Viewing Dashboard:** The main dashboard provides real-time insights into your inventory.


## 🛣️ Project Roadmap

Our goal is to continuously improve and expand the capabilities of the Inventory Management Software. Here's what's planned:

*   **Version 1.1.0 - Reporting & Analytics:**
    *   Generate printable reports for inventory summaries and transaction history.
    *   Basic sales and stock movement analytics.
*   **Version 1.2.0 - User Authentication:**
    *   Implement user login and role-based access control.
    *   Secure user accounts for managing inventory.
*   **Future Enhancements:**
    *   Integration with barcode scanners.
    *   Multi-location inventory management.
    *   API for external integrations.
