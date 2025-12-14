# Sweet Shop Assessment - Frontend

A modern web application for managing and browsing a sweet shop inventory. This project serves as the frontend client, interacting with a dedicated backend API to handle user authentication, product management, and orders.

## 🚀 Features

* **User Authentication:** Secure login for Admins and Customers.
* **Product Catalog:** Browse sweets with detailed descriptions and pricing.
* **Cart Management:** Add items to cart and review orders.
* **Admin Dashboard:** Manage inventory and view system status (accessible via Admin credentials).
* **Responsive Design:** Optimized for both desktop and mobile viewing.

## 🛠️ Tech Stack

* **Frontend:** React.js / Next.js (TypeScript)
* **Styling:** Tailwind CSS / CSS Modules
* **State Management:** Context API / Redux
* **HTTP Client:** Axios / Fetch

## 🔗 Backend Repository

The backend API for this project is hosted separately. Please ensure the backend server is running for the frontend to function correctly.

* **Repository:** [Sweet Shop Assessment API](https://github.com/lavi-star/sweet-shop-assesment-api)

## 🔑 Demo Credentials

You can use the following credentials to test the application's different access levels:

| Role | Email | Password |
| :--- | :--- | :--- |
| **Admin** | `admin@gmail.com` | `admin` |
| **User (Test)** | `test@gmail.com` | `test` |

## 📦 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

* Node.js (v18 or higher)
* npm or yarn

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/lavi-star/sweet-shop-assesment
    cd sweet-shop-assesment
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Configure Environment Variables:**
    Create a `.env` file in the root directory and add your backend API URL:
    ```env
    NEXT_PUBLIC_API_URL=http://localhost:5000 # or your deployed backend URL
    ```

4.  **Run the development server:**
    ```bash
    npm run dev
    # or
    yarn dev
    ```

5.  **Open the app:**
    Visit `http://localhost:3000` in your browser.

## 📂 Project Structure

```bash
├── components/   # Reusable UI components
├── pages/        # Application routes/pages
├── public/       # Static assets (images, icons)
├── styles/       # Global styles and CSS modules
├── utils/        # Helper functions and API services
└── README.md     # Project documentation
