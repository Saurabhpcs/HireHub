**HireHub: MERN Stack Job Portal**

HireHub is a job portal built using the MERN stack, allowing users to browse, apply for jobs, and manage applications. Companies can post job listings, track applicants, and update application statuses. The platform includes authentication, state management, file uploads, admin functionalities, and a smooth UI powered by ShadCN.

**Tech Stack**

- Frontend: React.js (Vite) with ShadCN UI for modern styling

- Backend: Node.js with Express for server-side logic and API handling

- Database: MongoDB (Mongoose for schema validation and data modeling)

- State Management: Redux Toolkit for global state management

- Authentication: JWT (for authentication) and bcrypt (for password hashing)

- File Uploads: Multer (for handling resume and profile uploads)

- UI Animations: Framer Motion (for smooth UI transitions)

**Project Components**

**Frontend**

Navigation & Layout

- Navbar: Provides easy navigation to key sections like Home, Jobs, Browse, Login, and Profile.

  Protected Routes: Ensures only authenticated users can access specific pages.

- Pages

  Home Page: Displays job postings and trending companies.

  Login/Signup Page: Handles user authentication and account creation.

  Jobs Page: Lists all available jobs with filters.

  Browse Page: Allows users to search and filter jobs by company, type, and skills.

  User Profile Page: Displays user details, resumes, and applied jobs.

  Job Description Page: Provides detailed job information with an "Apply Now" option.

  Update Profile Dialog Page: Allows users to update their profile details.

- Job Features

  Custom Hook for Fetching Jobs: Efficiently retrieves jobs from the backend.

  Apply Job Feature: Users can apply for jobs directly from the platform.

  Persisted State: Ensures job applications and user sessions remain intact across page reloads.

- Admin Features

  Company Admin Page: Enables company users to manage job postings.

  Filter Company Logic: Allows filtering of jobs by company.

  Admin Job Page: Displays all jobs posted by a company.

  Applicant Management Page: Enables companies to view and update applicant statuses.

  Get All Applied Jobs: Displays all job applications for an admin.

**Backend**

- Authentication & Security

  JWT Authentication: Used for securing user sessions.

  Middleware for Route Protection: Ensures only authorized users access admin features.

- Database & Models

  MongoDB & Mongoose: Stores users, jobs, applications, and companies.

  Models Created: User, Job, Company, Application schemas for structured data storage.

- Controllers & Routes

  User Controller & Routes: Handles user authentication, registration, and profile management.

  Company Controller & Routes: Manages job postings and company details.

  Job Controller & Routes: Handles job creation, retrieval, and updates.

  Application Controller & Routes: Manages job applications and applicant status.

- File Uploads

  Multer Integration: Enables users to upload resumes and profile images securely.

- API Testing

  Postman Testing: Ensured all API routes function correctly before integrating with the frontend.

**Conclusion**

✅ A fully functional job portal where users can browse and apply for jobs.
✅ Companies can post jobs, track applicants, and manage applications.
✅ A smooth and responsive UI with protected routes and real-time updates.
✅ Secure authentication, file uploads, and well-structured API endpoints.


For any questions or further information, please contact me at saurabh.kumar.21cse@bmu.edu.in.

