#  SaaS Project - MERN Stack Project

##  Overview

A comprehensive, production-ready SaaS (Software as a Service) application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This platform provides a complete business solution with subscription management, team collaboration, task tracking, and real-time analytics.

##  Key Features

###  Authentication & Security
- Secure user registration and login
- JWT-based authentication
- Password encryption with bcrypt
- Role-based access control (User, Manager, Admin)
- Password reset functionality via email

###  Subscription Management
- Multiple subscription tiers (Free, Basic, Pro)
- Stripe payment gateway integration
- Payment history tracking
- Automatic invoice generation
- Subscription upgrade/downgrade

###  Task Management
- Create, edit, and delete tasks
- Priority levels (Low, Medium, High, Urgent)
- Status tracking (Pending, In Progress, Completed)
- Due date management with overdue alerts
- File attachments for tasks
- Comments and discussions

###  Team Collaboration
- Create and manage teams
- Invite team members via email
- Assign tasks to team members
- Role-based team permissions
- Team activity tracking

###  Analytics Dashboard
- Visual task statistics with charts
- Task completion rates
- Priority distribution
- Recent activity feed
- Subscription analytics (Admin only)

###  Email Notifications
- Welcome emails for new users
- Task assignment notifications
- Payment confirmations
- Overdue task reminders
- Password reset emails


### Frontend
- **React.js** 
- **React Router** 
- **Axios** 
- **Chart.js**
- **Stripe.js**
- **CSS3**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**
- **JWT**
- **Bcrypt**
- **Stripe**
- **Nodemailer**
- **Multer** 

### DevOps
- **Git** - Version control
- **Postman** - API testing
- **MongoDB Atlas** - Cloud database
- **Vercel/Netlify** - Frontend hosting
- **Heroku/Railway** - Backend hosting


### Installation

#### 1. Clone the Repository
```bash
git clone https://github.com/anasshahzad44/Saas-project
cd Saas-project

Update the Stripe publishable key in SubscriptionPlans.js:
const stripePromise = loadStripe('your--stripe--key');

Start Backend Server
cd backend
npm run dev
Server runs on http://localhost:3000

Start Frontend Application
cd frontend
npm start
