# Implemented Features

## T-14: Implement User Login Page
This task involves creating a login form component with email and password fields, including validation and error handling.
**Status: Implemented**

## User Stories & Acceptance Criteria

| Role | User Want To | So That | Acceptance Criteria |
|------|--------------|---------|-------------------|
| Admin | Create a new Admin Profile | I can enroll myself in the system | An OTP is sent to user's mobile and confirmation mail to the registered email |
| Admin | Log in securely to access the admin dashboard with my email and password | I can oversee and modify shipment, payment, and tracking records | System verifies admin credentials from Login table |
| Admin | View all shipments, payments, employees, carriers, and routes | I can oversee system-wide activities and ensure accuracy | Admin can see all data from Shipment, Payment, Carrier, Employee, and Route tables |
| Admin | Add new employees, carriers, shipments, and routes | I can expand system functionality and manage operational growth | Admin can create new records using valid forms |
| Admin | Access tracking information for any shipment | I can verify delivery progress and assist in customer service issues | Tracking Status is visible for all shipments |
| Admin | Update shipment, payment, tracking, and route information | I can resolve disputes, correct errors, and ensure proper workflow | Admin can modify any field in Shipment, Payment, Carrier, Employee, and Route tables |
| Admin | Delete employees, carriers, and shipments | I can remove inactive or incorrect records from the system | Deletion allowed for Admin |
| Employee | Log in securely to access the employee dashboard | I can enroll myself into employee dashboard | Need registered employee email and password |
| Employee | Verify whether a shipment is fully paid or unpaid | I can update the payment status as Paid | Need shipment request |
| Employee | Assign shipment orders to carriers only after payment is confirmed | I can accept customer shipment and assign a carrier | Need carrier id, payment id, shipment id |
| Employee | Remove shipment | I can remove shipment details from the database | Need delete button |
| Employee | Update employee information | I can update all information of the employee | Need update button |
| Customer | Log in securely | To view shipment details | Providing password & clientID |
| Customer | Track | Only shipment tied to clientID | Providing clientID |
| Customer | Verify shipment using name and email | To be member | Providing contact no., password, DOB, gender |
| Customer | System checks details | Against the system table | Providing contact no., password, DOB, gender |
| Customer | Be member | Order product | Providing contact no., password, DOB, gender |
| Customer | Sign up by filling out a registration form | To be a new user | Providing contact no., password, DOB, gender |
| Customer | Create an account (new user) | Log in to the system | Providing password and clientID |
| Carrier | Log in securely to my carrier dashboard | I can access my assigned shipments and manage deliveries | Must enter valid email & password |
| Carrier | View all shipment orders assigned to me | I can know which deliveries I am responsible for | Shipment details include: CarrierID, ShipmentID, Client info, Route & Status |
| Carrier | Update the tracking status of a shipment | Customers and employees can track real-time delivery progress | Editable status options: Pending, In Transit, Shipped to Delivered. System updates Shipment table & timestamp is recorded |
| Carrier | Update my own profile information | My contact information remains accurate for the company | Carrier can update Name, Contact, Address, Password & Profile updates do not affect Login credentials unless changed |
| Carrier | Mark a shipment as Delivered | The system can complete the shipment process | Status changes to Delivered & shipment no longer appears in pending lists |
| Carrier | View route information for assigned shipments | I can understand the origin and destination before starting delivery | RouteID correctly linked to Shipment & No access to edit route data |
| Seller | Create a shipment order | I can send goods to my customers | System allows entering goods type, weight, volume, pickup & drop-off address, receiver details. Shipment saved with ClientID. PaymentStatus defaults to Pending |
| Seller | Have the system auto-assign a RouteID | I don't manually choose or manage routes | System checks for existing route. If route exists, reuse RouteID; otherwise create new RouteID automatically |
| Seller | View all shipment orders I created | I can track and manage my shipments | System shows only shipments linked to my ClientID with details (goods, weight, status, delivery time). Access to others' shipments is blocked |
| Seller | See delivery estimate automatically | I know when the shipment should arrive | When payment changes from Pending → Paid/Unpaid, system sets EstimatedDeliveryTime = Today + 3 days |
| Seller | Manage my own profile | I can keep my information updated | Seller can view/update own profile only; can delete own account without affecting others |
EOF
1.2	Selection of Process Model
In our Delivery Management System, we picked Extreme Programming (XP) as a development model. The XP model works well for our projects where requirements can change and where we can get feedback from customers and use common sense principles to develop our project easily. It helps us to stay flexible and focused on delivering quality at each step of the process.

XP is a software development method which built around the idea of doing simple to understand practices, getting feedback from customers, and improving the system over time. XP encourages continuous communication between the development team and the customer to make sure the software always fulfills the customer's needs.

Exploration: In This phase we can gather requirements from the customer and our development team gets knowledge about the tools and technologies that we will use. This phase can take two weeks of our project time.
Planning: At first, we can write the user stories (features) and estimate the effort of the working of the user stories for the implementation we can give priorities of the user stories and the releasing schedule will create. 
Iterations to Release: Before the first release of our system several iterations will include, and it takes two weeks for implementation. In the first iteration the architecture of the hole system will be created. Customers can select the stories in each iteration. When all the iteration is completed, our project will be ready for production.
Productionizing: When the system is ready for release, we can do extra testing and performance checks. We can also review any last-minute changes that might need to be included in our project.
Maintenance: After the first release, we can keep our system running and produce some new iteration simultaneously. We can also have some developers to maintain our project.
Death: After the satisfaction of the customer needs this phase occurred and we can write our necessary documents of the system. 
XP Process Flow
Here’s a simple diagram to show the XP process:





Exploration
↓
Planning
↓
Iterations to Release
↓
Productionizing
↓
Maintenance
↓
Death

Why XP is the Best Fit for This Project
We chose XP for the Delivery Management System for several reasons:
Pair programming:
In the Pair programming it allows two people to program at a time, one person is brainstorming, another is involved with writing code. By this we can used to write code efficiently for a long time.
Frequent Requirement Changes:
Our system consists of different user roles- admin, employee, carrier, client, and their needs will likely change as we develop. XP works well here because it’s built to adapt quickly to changing requirements through its short development cycles.
Metaphor: In metaphor there is a shared story which is a summary of the overall project describes how the system will work for development. By this our project team will get a clear understanding of what the project needs. 
40-hour week: Developer can maximum 40-hour work in a week. So that the developers’ working productivity will increase.
Reduced Risk:
XP reduces the risk of major issues later in the process because we get constant feedback and release small, incremental updates regularly. If something isn’t working, we can address it immediately rather than discovering it later in the project.
On-site customer: 
We can understand the requirements perfectly and the problems because a customer must present full time and available for our team.

XP will work perfectly in our Delivery Management System Because XP values like communication, simplicity, feedback, courage, respect which will enhance our project progress. Besides it’s Practices will also help us to develop the project smoothly.

