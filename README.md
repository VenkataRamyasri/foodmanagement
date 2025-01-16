# foodmanagement
Hospital Food Manager Functionality
Manage Patient Details:

CRUD operations for patient records.
Fields: Name, Diseases, Allergies, Room/Bed/Floor, Age, Gender, Contacts, etc.
Create Food/Diet Charts:

Morning, Evening, Night meal plans.
Specify ingredients and instructions.
Store charts with patient references.
Manage Inner Pantry:

CRUD operations for pantry details.
Assign food preparation and delivery tasks.
Track Meal Preparation/Delivery:

Monitor statuses (Preparation & Delivery).
Alert for issues/delays.
Inner Pantry Functionality
Manage Food Preparation Tasks:

View assigned tasks.
Update preparation status.
Manage Delivery Personnel:

CRUD operations for delivery staff.
Assign meal boxes.
Track Meal Deliveries:

Log patient details, diet charts, and room numbers.
Update delivery statuses.
Delivery Personnel Functionality
Mark Deliveries Completed:
Login to view assigned tasks.
Update delivery status with optional notes.
Dashboards
Hospital Food Manager: Overview of all operations, issues, and alerts.
Inner Pantry Staff: Task management and real-time updates.
Development Plan
Backend
Technologies:
Preferred: NestJS (framework), Prisma (ORM), PostgreSQL (DB).
Optional: Node.js with Express.js.
Features:
Authentication with JWT.
APIs for:
Patient CRUD.
Diet chart management.
Task assignment.
Delivery status tracking.
Database schema:
Patients, Diet Charts, Pantry Staff, Delivery Personnel, and Deliveries.
Frontend
Technologies:
Preferred: React.js with Next.js.
Optional: Tailwind CSS/Material UI for styling.
Features:
Role-based dashboards.
Responsive and intuitive forms.
Real-time delivery status updates.
Deployment
Platform:
Vercel/Render/Railway for backend and frontend.
PostgreSQL/MongoDB on cloud platforms.
Testing Credentials:
Preload database with the provided email/password for roles.
