1. PROJECT PROPOSAL
1.1 Background to the Problem
Now a days, many businesses depend on fast and reliable delivery management services. In a Delivery management system, there are some roles like seller, customer, admin, carrier and employee etc. Sellers need an easy way to send products to customers, customers want to track on there shipment, employees must have to verify the payments and assign carriers into the individual shipment, carriers need to update delivery status. When they do the tasks manually, a lot of mistakes can happen-such as wrong tracking updates by the carriers, lost of shipment information, or miss match in assigning carriers, lost of documentation of the shipments.

If we want solve these problems, the Delivery Management System software was created. It takes all the parts of the delivery process into one Desktop based application so every user can do their own work easily. The employee can add ,update and delete any shipment , carrier and routes, update and check his information and also check payment status. The sellers can create shipments easily, create new account and also delete account. .The carriers can see his appointed shipment, can update tracking information and customers can see the delivery status. Admin is the main role of this project he can Update, Delete, Create simultaneously all the role and he also effect the shipment by changing information if found any wrong.

After getting all information in a database and providing each user with a different dashboard, the system prevent errors, saves time, and keeps data organized. This makes delivery faster, clearer, and more reliable for the users.

The target group of users:

Admin
Admin can create: Employees, Carriers, Routes, Update Payment, Tracking. He view all records and able to delete the Employees, Carriers & Shipments.

Employees
Employee can add carriers with the shipments, check payment status .He can view all shipments and can update payment also update his own profile, can delete shipment from the system.

Carrier
Carrier can view Assigned Shipments . Update Tracking Status and His own Info.

Seller
Seller is a client who can create shipment, delete Shipments, can view tracking status, He also can make payment and delete his account.

Customer
He can View his shipments which are assign from seller to him . Update his profile and Delete his Account .

1.2 Selection of Process Model
In our Delivery Management System, we picked Extreme Programming (XP) as a development model. The XP model works well for our projects where requirements can change and where we can get feedback from customers and use common sense principles to develop our project easily. It helps us to stay flexible and focused on delivering quality at each step of the process.

XP is a software development method which built around the idea of doing simple to understand practices, getting feedback from customers, and improving the system over time. XP encourages continuous communication between the development team and the customer to make sure the software always fulfills the customer's needs.

XP Process Flow:

Exploration: In This phase we can gather requirements from the customer and our development team gets knowledge about the tools and technologies that we will use. This phase can take two weeks of our project time.

Planning: At first, we can write the user stories (features) and estimate the effort of the working of the user stories for the implementation we can give priorities of the user stories and the releasing schedule will create.

Iterations to Release: Before the first release of our system several iterations will include, and it takes two weeks for implementation. In the first iteration the architecture of the hole system will be created. Customers can select the stories in each iteration. When all the iteration is completed, our project will be ready for production.

Productionizing: When the system is ready for release, we can do extra testing and performance checks. We can also review any last-minute changes that might need to be included in our project.

Maintenance: After the first release, we can keep our system running and produce some new iteration simultaneously. We can also have some developers to maintain our project.

Death: After the satisfaction of the customer needs this phase occurred and we can write our necessary documents of the system.

Why XP is the Best Fit for This Project
We chose XP for the Delivery Management System for several reasons:

Pair programming: In the Pair programming it allows two people to program at a time, one person is brainstorming, another is involved with writing code. By this we can used to write code efficiently for a long time.

Frequent Requirement Changes: Our system consists of different user roles- admin, employee, carrier, client, and their needs will likely change as we develop. XP works well here because it's built to adapt quickly to changing requirements through its short development cycles.

Metaphor: In metaphor there is a shared story which is a summary of the overall project describes how the system will work for development. By this our project team will get a clear understanding of what the project needs.

40-hour week: Developer can maximum 40-hour work in a week. So that the developers' working productivity will increase.

Reduced Risk: XP reduces the risk of major issues later in the process because we get constant feedback and release small, incremental updates regularly. If something isn't working, we can address it immediately rather than discovering it later in the project.

On-site customer: We can understand the requirements perfectly and the problems because a customer must present full time and available for our team.

XP will work perfectly in our Delivery Management System Because XP values like communication, simplicity, feedback, courage, respect which will enhance our project progress. Besides it's Practices will also help us to develop the project smoothly.

2. SOFTWARE REQUIREMENTS SPECIFICATIONS (SRS) / PRODUCT REQUIREMENTS DOCUMENT (PRD)
2.1 Scopes and Features
2.1.1 Admin
Create Admin Profile: Admin can create new profile to enroll themselves in the system.

Login to Dashboard: Admin securely logs in using email and password to access the dashboard.

View Shipments, Payments, Employees, Carriers, Routes: Admin can view all records of shipments, payments, employees, carriers, and routes.

Add and Delete Employees, Carriers, Shipments, Routes: Admin can manage users and system data by adding, updating, or deleting records.

Access Tracking Information: Admin can check the tracking status of any shipment.

Update Shipment, Payment, Tracking, Route Data: Admin can modify shipment, payment, or route details.

Delete Records: Admin can remove incorrect records from the system.

2.1.2 Employee
Login to Dashboard: Employees can log in using their user email and password to access the system.

Verify Shipment Payment Status: Employees can check whether a shipment is paid or unpaid.

Assign Shipments to Carriers: Employees can assign shipments to carriers after confirming the payment.

Update Shipment Information: Employees can update shipment details, such as status or delivery updates.

Remove Shipments: Employees can remove canceled shipments from the system.

Update Employee Data: Employees can update their personal information.

Add/Delete Carriers: Employees can add new carriers or delete carriers.

Add Routes: Employees can define new shipment routes with destination addresses.

Update Shipment Tracking Status: Employees can update tracking status for shipments in transit.

2.1.3 Customers
Login to System: Customers can log in using their client ID and password.

Sign Up/Register: New customers can register by filling in their details to create an account.

Create Account/Login: Customers can create new account or log in to the system with their information.

View Shipment Details: Customers can see detailed information about their shipments, including status and delivery times.

2.1.4 Carriers
Login to Dashboard: Carriers can log in to access their assigned shipments and manage deliveries.

View Assigned Shipments: Carriers can view all shipments assigned to them for delivery.

Update Shipment Tracking Status: Carriers can update the shipment status to inform customers of progress.

Update Shipments as Delivered: Carriers update shipments as delivered once they are completed.

Update Profile Information: Carriers can edit their personal and contact details.

View Route Information: Carriers can access route details, including the origin and destination of shipments.

2.1.5 Sellers
Create Shipment Order: Sellers can create new shipment orders with product details and delivery information.

Auto-Assign RouteID: System automatically assigns or creates a route ID for the shipment based on available routes.

View Shipment Orders Created: Sellers can view and track all the shipments they have created.

See Delivery Estimate: System calculates an estimated delivery date based on payment status.

Manage Profile: Sellers can view, update, or delete their own profile and account information.

2.2 User Story Table
AS A / AN	I want to	So that	Acceptance criteria
Admin	Create a new Admin Profile	I can enroll myself in the system	An OTP is sent to user's mobile and confirmation mail to the registered email
Log in securely to access the admin dashboard with my email and password.	I can oversee and modify shipment, payment, and tracking records.	System verifies admin credentials from Login table
View all shipments, payments, employees, carriers, and routes	I can oversee system-wide activities and ensure accuracy	Admin can see all data from Shipment, Payment, Carrier, Employee, and Route tables
Add new employees, carriers, shipments, and routes	I can expand system functionality and manage operational growth	Admin can create new records using valid forms
Access tracking information for any shipment	I can verify delivery progress and assist in customer service issues	Tracking Status is visible for all shipments
Update shipment, payment, tracking, and route information	I can resolve disputes, correct errors, and ensure proper workflow	Admin can modify any field in Shipment, Payment, Carrier, Employee, and Route tables
Delete employees, carriers, and shipments	I can remove inactive or incorrect records from the system	Deletion allowed for Admin
Employee	log in securely to access the employee dashboard.	I can enroll myself into employee dashboard	need registered employee email and password
verify whether a shipment is fully paid or unpaid.	I can update the payment status as Paid	need shipment request
assign shipment orders to carriers only after payment is confirmed.	i can accept customer shipment and assign a carrier	need carrier id, and payment id, shipment id
remove shipment	I can remove shipment details from the database	need delete button
update employee information	I can update all information of the employee	need update button
add or delete carrier	I can remove and add new carrier or delete old carrier	need carrier add and delete button
add routes	I can add new roots and its address( form -to)	need add routs button
update the tracking status of shipments.	I can provide customer shipment tracking information	need shipment id
Customer	log in securely	to view shipment details.	providing password & clientID
track	only shipment tied to clientID	providing clientID
verify shipment using name and email	to be member	providing contact no., password, DOB, gender.
System checks details	against the system table	providing contact no., password, DOB, gender.
be member	order product	providing contact no., password, DOB, gender.
sign up by filling out a registration form.	to be a new user	providing contact no., password, DOB, gender.
create an account (new user)	log in to the system.	providing password and clientID
Carrier	Log in securely to my carrier dashboard	I can access my assigned shipments and manage deliveries	Must enter valid email & password
View all shipment orders assigned to me	I can know which deliveries I am responsible for	Shipment details include: CarrierID, ShipmentID, Client info, Route & Status.
Update the tracking status of a shipment	Customers and employees can track real-time delivery progress	Editable status options: Pending, In Transit, Shipped to Delivered. System updates Shipment table & timestamp is recorded.
Update my own profile information	My contact information remains accurate for the company	Carrier can update Name, Contact, Address, Password & Profile updates do not affect Login credentials unless changed.
Mark a shipment as Delivered	The system can complete the shipment process	Status changes to Delivered & shipment no longer appears in pending lists.
View route information for assigned shipments	I can understand the origin and destination before starting delivery	RouteID correctly linked to Shipment & No access to edit route data.
Seller	Create a shipment order	I can send goods to my customers	System allows entering goods type, weight, volume, pickup & drop-off address, receiver details. Shipment saved with ClientID. PaymentStatus defaults to Pending.
Have the system auto-assign a RouteID	I don't manually choose or manage routes	System checks for existing route. If route exists, reuse RouteID; otherwise create new RouteID automatically.
View all shipment orders I created	I can track and manage my shipments	System shows only shipments linked to my ClientID with details (goods, weight, status, delivery time). Access to others' shipments is blocked.
See delivery estimate automatically	I know when the shipment should arrive	When payment changes from Pending → Paid/Unpaid, system sets EstimatedDeliveryTime = Today + 3 days.
Manage my own profile	I can keep my information updated	Seller can view/update own profile only; can delete own account without affecting others.
2.3 Requirements Traceability Matrix
2.3.1 Functional Requirements
Admin Requirements

Req. ID	Requirement
2.3.1.0	Admin Dashboard – All administrative features accessible after secure login.
2.3.1.1.1	Create a new admin profile by entering required details (name, email, password).
2.3.1.1.2	Securely log in to the dashboard using email and password.
2.3.1.1.3	Send OTP to mobile and confirmation email upon profile creation.
2.3.1.2.1	View all records: shipments, payments, employees, carriers, and routes in a list/table.
2.3.1.2.2	Access detailed tracking information for any shipment in the system.
2.3.1.3.1	Add new employees, carriers, shipments, and routes to the system.
2.3.1.3.2	Update details for shipments, payments, tracking status, and routes.
2.3.1.3.3	Delete (remove) records for employees, carriers, and shipments.
2.3.1.3.4	All changes (add, update, delete) must reflect immediately in the system views.
Employee Requirements

Req. ID	Requirement
2.3.1.4	Employee Dashboard – All employee features accessible after secure login.
2.3.1.5.1	Log in securely using registered email and password.
2.3.1.5.2	Update personal employee information.
2.3.1.6.1	Verify the payment status (Paid/Unpaid) of a shipment request.
2.3.1.6.2	Assign a confirmed (paid) shipment to an available carrier, linking ShipmentID, CarrierID, and PaymentID.
2.3.1.7.1	Update shipment information and tracking status (e.g., Pending, In Transit).
2.3.1.7.2	Remove (cancel/delete) shipment orders from the system.
2.3.1.8.1	Add new carriers to the system.
2.3.1.8.2	Delete carrier records.
2.3.1.8.3	Define and add new shipment routes with origin and destination addresses.
Customer Requirements

Req. ID	Requirement
2.3.1.9	Customer Portal – All customer features accessible after login/registration.
2.3.1.10.1	Register/Sign Up as a new user by providing details (contact, password, DOB, gender).
2.3.1.10.2	Create an account and log in using the provided ClientID and password.
2.3.1.10.3	System validates provided details (name, email) against records during registration.
2.3.1.11.1	View detailed information for all shipments linked to their ClientID.
2.3.1.11.2	Track the status and delivery timeline of their shipments.
Carrier Requirements

Req. ID	Requirement
2.3.1.12	Carrier Dashboard – All carrier features accessible after secure login.
2.3.1.13.1	Log in securely using email and password.
2.3.1.13.2	Update personal profile information (Name, Contact, Address).
2.3.1.14.1	View all shipment orders assigned to their CarrierID.
2.3.1.14.2	View route information (origin, destination) for assigned shipments.
2.3.1.14.3	Update the tracking status of a shipment (e.g., to "In Transit").
2.3.1.14.4	Mark a shipment as "Delivered" to complete the delivery process.
2.3.1.14.5	System records a timestamp for all status updates.
Seller Requirements

Req. ID	Requirement
2.3.1.15	Seller Portal – All seller features accessible after login.
2.3.1.16.1	View, update, and delete own profile and account information.
2.3.1.17.1	Create a new shipment order by entering goods details, weight, volume, pickup/drop-off addresses, and receiver information.
2.3.1.17.2	System automatically saves the shipment with the seller's ClientID and a default "Pending" payment status.
2.3.1.18.1	System auto-assigns a RouteID by checking for an existing matching route or creating a new one.
2.3.1.18.2	System automatically calculates and displays an Estimated Delivery Time (Today + 3 days) once payment status changes from "Pending".
2.3.1.19.1	View a list of all shipment orders created under their ClientID.
2.3.1.19.2	Access is restricted to own shipments only; cannot view others's orders.
2.3.2 Non-Functional Requirements
Category	Requirement
Performance	The system shall allow administrators to view, filter, and update all system records (shipments, users, routes) with a page load time of under 3 seconds, even with large datasets.
Reliability	Core transaction features (creating shipments, updating status, processing payments) shall maintain 99.5% operational uptime. Data integrity must be preserved during power or network failures.
Usability	The user interface for Employees, Carriers, and Sellers shall be intuitive, requiring minimal training. Common tasks (e.g., updating a shipment status) should be completable in 3 clicks or less.
Security	The system shall enforce role-based access control (RBAC). All user authentication must use encrypted credentials, and sensitive data (client info, payment details) must be protected in transit and at rest.
Compatibility & Scalability	The web-based dashboard shall be fully compatible with modern browsers (Chrome, Firefox, Edge). The system architecture shall support a linear scale in users and shipment volume without performance degradation.
Availability	The customer and carrier tracking portals shall be available 24/7. Scheduled maintenance windows shall be communicated at least 48 hours in advance.
Data Integrity & Accuracy	The system shall ensure that all shipment tracking statuses and financial records (payments) are accurate, auditable, and prevent conflicting updates through locking mechanisms.
Maintainability	The system shall be built with a modular codebase (e.g., separate modules for User Management, Shipment Processing, Analytics) to allow for easy updates, debugging, and feature addition.
Response Time	All user interactions (button clicks, form submissions) shall provide visual feedback within 500 milliseconds.
3. SOFTWARE DESIGN
3.1 System Design
(Diagrams included in original document: Use Case, Class, Activity)

3.2 UI Design using Figma
(All UI screens shown in original document)

4. GIT WORKFLOW
https://via.placeholder.com/800x400.png?text=Git+Workflow+Diagram

Workflow Process:

Central Repository – Created on GitHub with main/master branch

Clone Repository – Each member clones the main repository

Feature Branching – Create individual branches for specific tasks

Regular Commits – Stage and commit changes with descriptive messages

Push Updates – Push changes to remote feature branches

Pull Requests – Create PRs for code review

Merge to Main – After approval, merge feature branches to main

Continuous Integration – Regular updates and conflict resolution

5. SOFTWARE TESTING
Test Case ID	Module	Test Title	Status
SMS_01	Login & Validation	Verify login with Email & Password	Pass
SMS_02	Add Employee Account	Verify Admin can add Employee	Pass
SMS_03	Create Shipment	Verify user can create Shipment	Fail
SMS_04	Manage Shipment	Confirm shipment	Pass
SMS_05	Add Carrier	Verify add new carrier	Pass
SMS_06	Add Routes	Verify add new routes	Fail
SMS_07	Update Employee Info	Verify employee can update own info	Pass
SMS_08	Tracking Status Update	Verify carrier updates tracking status	Pass
SMS_09	Confirm Payment	Verify employee confirms payment	Pass
SMS_10	Update Shipment Info	Verify employee updates shipment info	Pass
SMS_11	Create Client Account	Verify client can create account	Pass
SMS_12	Delete Client Account	Verify delete account	Pass
SMS_13	Delete Carrier Account	Verify admin deletes carrier account	Pass
SMS_14	Delete Routes	Verify admin deletes route	Pass
6. CONCLUSION
In the Delivery Management System project we are try to create a user-friendly software to manage all delivery steps easily. This project solves common problems as like lost shipments info, wrong tracking status updates, and a lot of paperwork by bringing everything into one organized system. There are different users get their own dashboards like Admins control everything, Employees are checking payments and assigning deliveries, Carriers update delivery status, Sellers create shipments and can delete shipments, Customers track their orders. We used Extreme Programming (XP) in our Delivery Management System project which help us to adapt quickly to changes and build the system step by step with constant feedback from our customers. The Testing showed most of the features work well, though we found some of small issues to fixed them later.

The final system is very secure, easy to use, and helps everyone involved save time while reducing the mistakes. It makes the entire delivery process faster, clearer, and more reliable for businesses and their customers.
