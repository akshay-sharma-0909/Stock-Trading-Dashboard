## Stock Trading Platform 
** Stock Trading Platform is a web-based dashboard application that simulates real-world stock trading functionality. The platform allows users to track holdings, view positions, manage orders, and monitor portfolio performance through an interactive and structured UI.

This project is inspired by real-world trading platforms (e.g., Zerodha) and focuses on portfolio management, authentication flow, data visualization, and REST-based integration.

## Features

- **User Dashboard – View holdings, positions, funds, and orders

-**Portfolio Summary – Real-time visual insights using charts

-**Order Simulation – Buy/Sell interaction window

-**Watchlist Management – Track selected stocks

-**Data Visualization – Doughnut & vertical graphs

-**Component-Based UI – Modular and reusable React components

-**State Management – Centralized state using React Context API

## Installation
**Prerequisites**
- Node.js (for backend)
- MongoDB (for database)
- React (for frontend

**Steps to Install**
1. Clone the Repository:
```bash
git clone https://github.com/akshay-sharma-0909/Stock-Trading-Dashboard
cd Stock-Trading-Dashboard
```
2. Install Backend Dependencies:

Navigate to the frontend/ folder and run:
```bash
node install
```

3. Install Frontend Dependencies:

Since the frontend uses React, CSS, and JavaScript, there are no specific package dependencies. You can simply open the frontend/ folder and start working with the files.

4. Configure Database:

Set up your MongoDB instance and configure the connection string in the backend/config/db.js file.

5. Start the Application:

For the :
```bash
cd frontend
npm start
```

6. Visit https: https://stock-trading-dashboard-6rpx.onrender.com in your browser to access the application.

## Tech Stack
- Backend: Node.js, Express.js
- Database: MongoDB
- Fronted :React.js, CSS, JavaScript
- Deployment: Render

## Folder Structure
```
trading-platform-dashboard/
│
├── public/
│
├── src/
│   ├── components/             # Dashboard UI components
│   │   ├── Apps.js
│   │   ├── BuyActionWindow.js
│   │   ├── BuyActionWindow.css
│   │   ├── Dashboard.js
│   │   ├── DoughnutGraph.js
│   │   ├── Funds.js
│   │   ├── GeneralContext.js
│   │   ├── Holdings.js
│   │   ├── Home.js
│   │   ├── Menu.js
│   │   ├── Orders.js
│   │   ├── Positions.js
│   │   ├── Summary.js
│   │   ├── TopBar.js
│   │   ├── VerticalGraph.js
│   │   └── WatchList.js
│   │
│   ├── data/
│   │   └── data.js             # Static / mock data
│   │
│   ├── index.css               # Global styles
│   └── index.js                # React entry point
│
├── .env                         # Environment variables
├── .gitignore
├── package.json
└── package-lock.json



```

## Screenshots
***Dashboard***
<img width="1304" height="908" alt="Image" src="https://github.com/user-attachments/assets/81e619ff-de73-423b-afcb-f487414429e1" />


***Holding***

<img width="1279" height="820" alt="Image" src="https://github.com/user-attachments/assets/435906ae-36e3-4ee7-be4d-787b671c7187" />





***Position***
<img width="1292" height="816" alt="Image" src="https://github.com/user-attachments/assets/d7fa363f-e0e0-4943-bd5b-aa1e53046d84" />





## Contributing
We welcome contributions from the community! If you'd like to improve or add features to this project, feel free to fork the repository, make your changes, and submit a pull request. Please ensure that your code adheres to the project's coding standards and is well-documented.




** Node.js and Express.js for building the backend server.

** MongoDB for storing data.
** React.js for  Building Frontend.
