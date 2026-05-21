Title: Advanced AI Demand Forecasting Enhancements 

Backend: Python, Fast-api

Frontend: React.js

Database: MySQL Workbench

IDE: Visual Studio Code

Backend packages:

Fast-api,
Uvicorn,
SQLAlchemy,
PyMySQL,
python-jose,
Passlib,
Pandas,
Scikit-learn,
OpenPyXL,
python-multipart,
ReportLab

Frontend packages:

React,
Vite,
Tailwind CSS,
Axios,
React Router DOM,
Recharts,
React Toastify,
exceljs,
file-saver,
jspdf,
jspdf-autotable

Database Tables:

1. Users - To store admin and users
2. Sales - To store the dataset
3. Forecast_results - To store the generated forecast prediction
4. Reports - To store the forecast report files created by users

Features Added:

1. Admin Panel
  - System analytics and dashboard
  - Manage users
  - Manage datasets
  - Manage reports
  - Analytics summary
  - Notification 

2. User Page
  - Dashboard
  - Upload dataset
  - Generate forecast
  - Download Report
  - Analytics Summary
  - Notification

3. Frontend React
  - Improved UI at the login, register pages, and sidebar component
  - Loading animation and skeleton screens
  - Pagination and filter feature
  - Added bell icon for notification
  - Drop-down list for notification

4. Backend FastAPI
  - JWT authentication and authorization
  - Added success response format
  - Global error response implementation
  - Paginations and Search Filters
  - Validations and error handling
  - Reusable code structure

6. Dashboard
  - KPI carts for system analytics
  - Monthly charts
  - Top products charts
  - Forecast prediction graph
  - Filter features to display analytics

6. Downloads
  - Forecast report downloaded in PDF and Excel
  - User report file view and download
  - Summary analytics downloaded in PDF and Excel
