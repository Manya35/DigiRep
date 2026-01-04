# Digital Class Representative (Digital CR)

The **Digital Class Representative (Digital CR)** system is a university management platform designed for **IGDTUW** students, Class Representatives (CRs), and society heads. This platform automates and organizes key tasks like timetable management, attendance tracking, event notifications, classroom tracking, and ranking system management, fostering efficiency and collaboration.

---

## 🚀 Getting Started

### Prerequisites
* **Node.js** (v14 or higher)
* **MongoDB** (Local instance or Atlas)
* **MongoDB Compass** (Recommended for database visualization)

### Installation
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/manya35/digital-cr.git](https://github.com/manya35/digital-cr.git)
   cd digital-cr
   ```
2. **Set up the backend**
   ```bash
   cd backend
   npm install
   # Create a .env file and add your MONGODB_URI and PORT
   npm start
   ```
3. **Set up the frontend**
   ```bash
   cd frontend
   npm install
   npm start
   ``` 
🛠 Technology Stack
-------------------

*   **Frontend**: React.js (Responsive UI with modern design)
    
*   **Backend**: Node.js (Secure and scalable backend)
    
*   **Database**: MongoDB (Managed via MongoDB Compass)
    
*   **Styling**: CSS & Bootstrap
    

🤝 Contributing to Open Source
------------------------------

We welcome contributions from the community! Whether you are fixing a bug or adding a new feature, follow these steps:

### How to Contribute

1.  **Find an Issue**: Browse our \[GitHub Issues\] for tasks labeled good first issue or help wanted.
    
2.  **Fork the Repo**: Click the "Fork" button at the top of the repository page.
    
3.  **Create a Branch**: git checkout -b feature/your-feature-name.
    
4.  **Commit Changes**: Use clear, descriptive commit messages.
    
5.  **Open a Pull Request**: Describe your changes in detail and link the relevant issue.
    

### Current Open Issues for Contributors

**IssueFiles InvolvedTasksResponsive Sidebar**src/App.js, src/components/Sidebar.jsCreate a collapsible navigation menu for mobile users.**Dark Mode Toggle**src/index.css, src/App.jsImplement a global theme switcher using CSS variables.**JWT Authentication**backend/server.js, backend/routes/auth.jsSecure the CR and Society Head routes with token-based login.**Conflict Logic**backend/server.js, src/components/ClassroomModule.jsPrevent overlapping classroom bookings in the database.**PDF Export**src/components/ResultPage.jsAllow students to download their rank and CGPA as a PDF file.

✨ Features
----------

### 1\. Timetable Notifications & Attendance Tracker

*   **Notifications**: Students receive daily schedule notifications via email, SMS, or push notifications.
    
*   **Management**: CRs can update class schedules in real-time, including cancellations and rescheduling.
    
*   **Tracking**: CRs can track and record attendance for students during each session and view analytics.
    

### 2\. Classroom Availability Tracker

*   **Real-time Status**: Provides classroom availability for CRs and society heads.
    
*   **Filtering**: Search and filter classrooms by department (e.g., CSE-ECE, IT, MAE), location, and capacity.
    

### 3\. Society Events Dashboard

*   **Calendars**: Dedicated society pages with a calendar-based events dashboard (e.g., Coding Society, Music Society).
    
*   **Engagement**: Students can subscribe to events for notifications, and society heads can manage outreach.
    

### 4\. Ranking System

*   **Academic Progress**: Displays sortable, CGPA-based course-wise and year-wise rankings.
    
*   **Personalized Views**: Students can view personalized results, including rank and CGPA relative to peers.
    

🎨 Design Theme
---------------

*   **Primary Colors**: Blue, White, Gray
    
*   **Accent Colors**: Green, Orange
    
*   **Design Style**: Modern minimalist with card layout and subtle shadows
