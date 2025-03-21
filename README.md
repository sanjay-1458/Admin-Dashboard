# Overview
InsightFlow is a feature-rich analytics dashboard built using ReactJS, Tailwind CSS, and Recharts, designed to provide comprehensive data insights across multiple modules.
The dashboard includes seven key sections—Overview, Orders, Sales, Analytics, Products, Users, and Settings—each offering interactive data visualization and smooth navigation with React Router.
The application enhances data representation by 40% through optimized charts and graphs using Recharts, ensuring an intuitive user experience.
A significant highlight of the project is the User Retention Analysis module, which features a dynamic line chart that tracks user trends over an 8-week period with smooth animations powered by Framer Motion.
The dashboard's responsiveness and efficient state management ensure seamless performance across various screen sizes, making it a scalable and user-friendly solution for business analytics.

# Website

![image](https://github.com/user-attachments/assets/e44f906c-dd97-4f20-b1f6-99436639f11c)

# Steps to Run
The bapplications runs on 5173 port, frst check if any other process is using the port.
Check for process in a given port
```
netstat -ano | findstr :PORT_NUMBER
```
Find the PID and kill it. A PID (Process Identifier) is a unique numerical identifier assigned by the operating system to every active process.
```
taskkill /PID {your_PID} /F

```

Clone the repo
```
git clone https://github.com/sanjay-1458/Admin-Dashboard
```
Go inside the repo
```
cd Admin-Dashboard
```
Run the app
```
npm run dev
```

# Deployed URL
https://admin-dashboard-dun-ten-64.vercel.app/
