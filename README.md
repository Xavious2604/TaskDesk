# 📋 TaskDesk - Enterprise Task Management System

> ⚠️ **CONFIDENTIAL ENTERPRISE PROJECT**: This is a proprietary enterprise-level application developed for **Sensys Technologies Pvt. Ltd.** The source code and implementation details are confidential and cannot be publicly shared. This documentation serves as a portfolio showcase of the project's features and architecture.

<div align="center">
  
  [![Vue.js](https://img.shields.io/badge/Vue.js-3.x-4FC08D?logo=vue.js&logoColor=white)](https://vuejs.org/)
  [![.NET Core](https://img.shields.io/badge/.NET%20Core-8.0-512BD4?logo=.net&logoColor=white)](https://dotnet.microsoft.com/)
  [![SQL Server](https://img.shields.io/badge/SQL%20Server-2022-CC2927?logo=microsoft-sql-server&logoColor=white)](https://www.microsoft.com/sql-server)
  [![PrimeVue](https://img.shields.io/badge/PrimeVue-Latest-41B883?logo=vue.js&logoColor=white)](https://primevue.org/)
  [![Enterprise](https://img.shields.io/badge/Status-Enterprise%20Confidential-red)](https://github.com/Xavious2604)
  
</div>

## 📋 Overview

**TaskDesk** is a comprehensive enterprise-grade task management and project tracking system built for team collaboration and productivity optimization. Developed at **Sensys Technologies Pvt. Ltd.**, this platform provides powerful Kanban boards, performance analytics, and real-time collaboration features for modern teams.

The system supports multiple views including Kanban boards, dashboard analytics, individual and project performance tracking, making it ideal for organizations managing complex workflows and multiple team members.

## ✨ Key Features

### 🎯 Task Management
- **Kanban Board Interface**: Drag-and-drop task management across multiple status columns (Pending, In Progress, On Hold, Completed)
- **Task Dashboard**: Comprehensive overview with real-time statistics and progress tracking
- **Task Cards**: Rich task cards displaying priority, assignees, due dates, and progress percentages
- **Smart Filtering**: Advanced search and filter capabilities across all task attributes
- **Subtask Management**: Break down complex tasks into manageable subtasks
- **Bulk Operations**: Handle multiple tasks simultaneously for efficient workflow management

### 👥 Team Collaboration
- **Multi-User Support**: Role-based access control for team members and administrators
- **Task Assignment**: Assign tasks to individuals or teams with automatic notifications
- **Team Performance Dashboard**: Track individual and team productivity metrics
- **Work Logs**: Comprehensive activity tracking with time logging capabilities
- **Collaboration Tools**: Comments, mentions, and real-time updates

### 📊 Analytics & Reporting
- **Individual Performance Dashboard**: 
  - Total tasks, completed, in progress, and pending metrics
  - Average progress tracking
  - Hours logged per team member
  - Overdue task identification
  
- **Project Performance Dashboard**:
  - Project-level statistics and completion rates
  - Resource allocation tracking
  - Timeline and deadline monitoring
  - Task distribution across projects

- **Real-Time Metrics**: Live dashboard updates with task status changes
- **Progress Indicators**: Visual progress bars and percentage tracking
- **Performance Analytics**: Identify bottlenecks and optimize workflows

### 🎨 User Interface
- **Modern Dark Theme**: Professional dark mode interface for reduced eye strain
- **Responsive Design**: Fully responsive layout for desktop, tablet, and mobile devices
- **Intuitive Navigation**: Easy-to-use sidebar navigation with quick access to all modules
- **Color-Coded Status**: Visual indicators for task priority and status
- **Customizable Layouts**: Personalize dashboard views and preferences

### ⚡ Advanced Functionality
- **Priority Management**: High, Medium, Low priority levels with visual indicators
- **Due Date Tracking**: Automatic overdue detection with alerts
- **Progress Tracking**: Real-time progress updates with percentage completion
- **Project Organization**: Group tasks by projects with dedicated views
- **Status Workflow**: Customizable workflow states (Pending → In Progress → On Hold → Completed)
- **Search & Filter**: Powerful search with multiple filter criteria
- **Sorting Options**: Sort by name, date, priority, assignee, or progress

## 🛠️ Tech Stack

### Frontend
- **Vue.js 3** - Progressive JavaScript framework with Composition API
- **PrimeVue** - Rich UI component library for Vue.js
- **JavaScript (ES6+)** - Modern JavaScript features
- **CSS3** - Custom styling and animations
- **HTML5** - Semantic markup

### Backend
- **.NET Core 8.0** - High-performance web API framework
- **C#** - Primary backend programming language
- **ASP.NET Core Web API** - RESTful API architecture
- **Entity Framework Core** - ORM for database operations
- **LINQ** - Integrated query syntax

### Database
- **SQL Server 2022** - Enterprise-grade relational database
- **Stored Procedures** - Optimized database queries
- **Indexing** - Performance optimization
- **Transaction Management** - Data integrity and consistency

### Additional Technologies
- **JWT Authentication** - Secure token-based authentication
- **SignalR** - Real-time communication (for notifications)
- **Axios** - HTTP client for API requests
- **Vuex/Pinia** - State management
- **Vue Router** - Client-side routing

## 📁 Project Structure

```
TaskDesk/
├── Frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── KanbanBoard.vue
│   │   │   ├── TaskCard.vue
│   │   │   ├── TaskDashboard.vue
│   │   │   ├── ProjectPerformance.vue
│   │   │   └── IndividualPerformance.vue
│   │   ├── views/
│   │   │   ├── TaskBoards.vue
│   │   │   ├── Dashboard.vue
│   │   │   └── ProjectsList.vue
│   │   ├── services/
│   │   │   └── taskService.js
│   │   ├── store/
│   │   │   └── taskStore.js
│   │   ├── router/
│   │   │   └── index.js
│   │   └── App.vue
│   └── package.json
│
├── Backend/
│   ├── Controllers/
│   │   ├── TaskController.cs
│   │   ├── ProjectController.cs
│   │   └── PerformanceController.cs
│   ├── Models/
│   │   ├── Task.cs
│   │   ├── Project.cs
│   │   └── User.cs
│   ├── Services/
│   │   ├── TaskService.cs
│   │   └── ProjectService.cs
│   ├── Data/
│   │   └── ApplicationDbContext.cs
│   └── Program.cs
│
└── Database/
    ├── StoredProcedures/
    ├── Tables/
    └── Views/
```

## 🚀 Technical Architecture Overview

> **⚠️ Note**: Due to the enterprise-level confidential nature of this project, the complete source code, database schemas, and implementation details cannot be publicly shared. The information below provides an architectural overview for portfolio purposes.

### Technology Requirements

- **Node.js** (v16 or higher)
- **.NET 8.0 SDK**
- **SQL Server 2022** - Enterprise-grade relational database
- **Visual Studio 2022** or Visual Studio Code
- **npm** or **yarn**

### High-Level Architecture

The application follows a three-tier architecture:

1. **Presentation Layer (Frontend)**
   - Vue.js 3 with Composition API
   - PrimeVue component library
   - Responsive design with mobile support

2. **Business Logic Layer (Backend)**
   - ASP.NET Core 8.0 Web API
   - RESTful API architecture
   - JWT-based authentication
   - Entity Framework Core ORM

3. **Data Layer (Database)**
   - SQL Server 2022
   - Stored procedures for complex operations
   - Optimized indexing strategy
   - Transaction management

### Deployment Architecture

- **Frontend Hosting**: Internal corporate server
- **Backend API**: Secure internal network deployment
- **Database**: Enterprise SQL Server instance
- **Authentication**: Corporate SSO integration

**📝 Note**: For inquiries about implementation details or enterprise deployment, please contact through professional channels.

## 📝 API Endpoints

### Tasks
```
GET    /api/tasks                    # Get all tasks
GET    /api/tasks/{id}               # Get task by ID
POST   /api/tasks                    # Create new task
PUT    /api/tasks/{id}               # Update task
DELETE /api/tasks/{id}               # Delete task
GET    /api/tasks/status/{status}    # Get tasks by status
GET    /api/tasks/assignee/{userId}  # Get tasks by assignee
```

### Projects
```
GET    /api/projects                 # Get all projects
GET    /api/projects/{id}            # Get project by ID
POST   /api/projects                 # Create new project
PUT    /api/projects/{id}            # Update project
DELETE /api/projects/{id}            # Delete project
GET    /api/projects/{id}/tasks      # Get project tasks
```

### Performance
```
GET    /api/performance/individual/{userId}   # Individual performance
GET    /api/performance/project/{projectId}   # Project performance
GET    /api/performance/team                  # Team performance
```

## 🎯 Key Features in Detail

### Kanban Board View
- **Drag & Drop**: Seamlessly move tasks between status columns
- **Real-time Updates**: Instant synchronization across all users
- **Status Columns**: Pending Tasks, In Progress, On Hold, Completed
- **Task Counts**: Live count of tasks in each column
- **Color Coding**: Visual priority indicators (Red: High, Yellow: Medium, Blue: Low)

### Task Dashboard
- **Statistics Cards**: Total tasks, today's tasks, completed, in progress, overdue
- **Quick Filters**: Filter by assigned user, status, priority
- **Search Functionality**: Full-text search across task names and descriptions
- **Pagination**: Navigate through large task lists efficiently
- **Sort Options**: Multiple sorting criteria for task organization

### Performance Dashboards
- **Individual Metrics**: Track each team member's productivity and workload
- **Project Metrics**: Monitor project health and completion rates
- **Progress Tracking**: Visual progress bars for quick status overview
- **Overdue Alerts**: Highlight tasks and projects requiring immediate attention
- **Hours Logged**: Track time spent on tasks and projects

## 🔒 Security Features

- **JWT Authentication**: Secure token-based user authentication
- **Role-Based Access Control**: Granular permissions for different user roles
- **Data Validation**: Input validation on both client and server sides
- **SQL Injection Prevention**: Parameterized queries and stored procedures
- **CORS Configuration**: Controlled cross-origin resource sharing
- **HTTPS Enforcement**: Secure communication between client and server

## 📊 Database Schema

### Core Tables
- **Tasks**: Task details, status, priority, assignees, due dates
- **Projects**: Project information, team assignments, deadlines
- **Users**: User profiles, roles, authentication data
- **WorkLogs**: Time tracking and activity logs
- **TaskComments**: Collaboration and communication records
- **TaskHistory**: Audit trail for all task changes

## 🎨 UI Screenshots

### 1. Kanban Board - Task Management
![Kanban Board](https://github.com/Xavious2604/TaskDesk/blob/main/Uploads/TaskBoards.PNG)

Multiple status columns with drag-and-drop task cards showing priority, assignees, and progress indicators. Features include:
- Color-coded priority levels (High: Red, Medium: Yellow, Low: Blue)
- Real-time task counts per column
- Quick search within each status
- Assignee and due date visibility

### 2. Tasks Dashboard - Overview
![Tasks Dashboard](https://github.com/Xavious2604/TaskDesk/blob/main/Uploads/Task%20Dashboard.PNG)

Comprehensive task overview dashboard displaying:
- Total tasks, today's tasks, completed, in progress, and overdue statistics
- Advanced filtering options (Assigned to Me, Status, Priority)
- Expandable task rows with detailed information
- Overdue task alerts with visual indicators
- Total hours logged tracking

### 3. Project Performance Dashboard
![Project Performance](https://github.com/Xavious2604/TaskDesk/blob/main/Uploads/Projects%20List.PNG)

Project-level analytics and metrics showing:
- Total projects with task distribution
- Completion rates and progress tracking
- Overdue project identification
- Average progress per project
- Task breakdown: Total, Completed, In Progress, Pending, Overdue
- Hours logged per project

### 4. Individual Performance Dashboard
![Individual Performance](https://github.com/Xavious2604/TaskDesk/blob/main/Uploads/Individaul%20Performance%20Dashboard.PNG)

Team member productivity tracking featuring:
- Individual task statistics and completion rates
- Overdue task alerts per team member
- Average progress calculation
- Hours logged tracking
- Task distribution: Total, Completed, In Progress, Pending

### 5. Projects List Management
![Projects List](https://github.com/Xavious2604/TaskDesk/blob/main/Uploads/Project%20Performance%20Dashboard.PNG)

Project management interface with:
- Project listing with team assignments
- Quick edit and delete actions
- Search functionality across projects
- Project creator and team member information
- Pagination for large project lists

## 🔮 Future Enhancements

- [ ] Mobile application (React Native/Flutter)
- [ ] Email notifications for task assignments and deadlines
- [ ] File attachments and document management
- [ ] Gantt chart view for project timelines
- [ ] Calendar integration for due date management
- [ ] Export reports (PDF, Excel)
- [ ] Custom workflow automation
- [ ] Integration with third-party tools (Slack, Microsoft Teams)
- [ ] Advanced analytics with AI-powered insights
- [ ] Recurring tasks and templates
- [ ] Time tracking with Pomodoro timer
- [ ] Dark/Light theme toggle

## 🤝 Collaboration & Contact

**⚠️ Enterprise Software Notice**: This is proprietary enterprise software developed for Sensys Technologies Pvt. Ltd. The source code, database schemas, and business logic are confidential intellectual property and cannot be publicly shared or distributed.

**For Professional Inquiries**:
- Technical discussions about architecture and design decisions
- Collaboration opportunities on similar enterprise projects
- Questions about the development experience

Please reach out through the contact information below.

## 📄 License & Copyright

**© 2024 Sensys Technologies Pvt. Ltd. - All Rights Reserved**

This project is proprietary and confidential enterprise software. The source code, documentation, database schemas, and all associated intellectual property are owned exclusively by **Sensys Technologies Pvt. Ltd.**

**Restrictions**:
- ❌ Source code is not available for public access
- ❌ No code distribution or reproduction permitted
- ❌ Implementation details are confidential
- ❌ Commercial use prohibited without authorization

**Portfolio Use**: This documentation is shared solely for professional portfolio purposes to showcase development capabilities and project experience.

For licensing inquiries or partnership opportunities, please contact Sensys Technologies Pvt. Ltd. directly.

## 👨‍💻 Developer

**Mohammed Irfan Shaikh**  
*ERP Developer at Sensys Technologies Pvt. Ltd.*

- 🌐 GitHub: [@Xavious2604](https://github.com/Xavious2604)
- 💼 LinkedIn: [Mohammed Irfan Shaikh](https://www.linkedin.com/in/mohammed-irfan-shaikh-2362a62a4/)
- 📧 Email: [223171@theemcoe.org](mailto:223171@theemcoe.org)

## 🙏 Acknowledgments

- **Sensys Technologies Pvt. Ltd.** - For providing the opportunity to develop this enterprise solution
- **PrimeVue Team** - For the excellent UI component library
- **Vue.js Community** - For the powerful frontend framework
- **Microsoft** - For .NET Core and SQL Server technologies

## 📈 Project Stats

- **Development Period**: October 2024 - December 2024
- **Team Size**: Full-stack development with stakeholder coordination
- **Technologies**: 8+ (Vue.js, .NET Core, SQL Server, PrimeVue, etc.)
- **Features**: 15+ major features implemented

---

<div align="center">
  <p>Built with 💻 for enterprise productivity and team collaboration</p>
  <p>⭐ Part of Sensys Technologies' ERP Suite</p>
</div>
