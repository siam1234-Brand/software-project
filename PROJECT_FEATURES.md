
## Customer, Casrrier,Seller User Story
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
# Implemented Features
>>>>>>> 586b8aa2297a47685a1ab5bbfdc44eb3472a9f69

# Project Proposal

## Background to the Problem
Nowadays, many businesses depend on fast and reliable delivery management services. In a Delivery management system, there are some roles like seller, customer, admin, carrier and employee etc. Sellers need an easy way to send products to customers, customers want to track their shipments, employees must verify the payments and assign carriers to individual shipments, carriers need to update delivery status. When they do the tasks manually, a lot of mistakes can happen - such as wrong tracking updates by the carriers, loss of shipment information, or mismatch in assigning carriers, loss of documentation of the shipments.

To solve these problems, the Delivery Management System software was created. It takes all the parts of the delivery process into one Desktop-based application so every user can do their own work easily. The employee can add, update and delete any shipment, carrier and routes, update and check his information and also check payment status. The sellers can create shipments easily, create new account and also delete account. The carriers can see their appointed shipment, can update tracking information and customers can see the delivery status. Admin is the main role of this project - he can Update, Delete, Create simultaneously all the roles and he can also affect the shipment by changing information if found any wrong.

After getting all information in a database and providing each user with a different dashboard, the system prevents errors, saves time, and keeps data organized. This makes delivery faster, clearer, and more reliable for the users.

## Target Users

### 1. Admin
- Can create: Employees, Carriers, Routes, Update Payment, Tracking
- Can view all records
- Able to delete: Employees, Carriers & Shipments

### 2. Employees
- Can add carriers to shipments
- Can check payment status
- Can view all shipments
- Can update payment
- Can update own profile
- Can delete shipment from the system

### 3. Carrier
- Can view Assigned Shipments
- Can update Tracking Status
- Can update own Info

### 4. Seller
- Seller is a client who can create shipment
- Can delete Shipments
- Can view tracking status
- Can make payment
- Can delete his account

### 5. Customer
- Can view shipments which are assigned from seller to him
- Can update profile
- Can delete account

## Scopes and Features

### 2.1.1 Admin
- **Create Admin Profile:** Admin can create new profile to enroll themselves in the system.
- **Login to Dashboard:** Admin securely logs in using email and password to access the dashboard.
- **View Shipments, Payments, Employees, Carriers, Routes:** Admin can view all records of shipments, payments, employees, carriers, and routes.
- **Add and Delete Employees, Carriers, Shipments, Routes:** Admin can manage users and system data by adding, updating, or deleting records.
- **Access Tracking Information:** Admin can check the tracking status of any shipment.
- **Update Shipment, Payment, Tracking, Route Data:** Admin can modify shipment, payment, or route details.
- **Delete Records:** Admin can remove incorrect records from the system.

### 2.1.2 Employee
- **Login to Dashboard:** Employees can log in using their user email and password to access the system.
- **Verify Shipment Payment Status:** Employees can check whether a shipment is paid or unpaid.
- **Assign Shipments to Carriers:** Employees can assign shipments to carriers after confirming the payment.
- **Update Shipment Information:** Employees can update shipment details, such as status or delivery updates.
- **Remove Shipments:** Employees can remove canceled shipments from the system.
- **Update Employee Data:** Employees can update their personal information.
- **Add/Delete Carriers:** Employees can add new carriers or delete carriers.
- **Add Routes:** Employees can define new shipment routes with destination addresses.
- **Update Shipment Tracking Status:** Employees can update tracking status for shipments in transit.

### 2.1.3 Customers
- **Login to System:** Customers can log in using their client ID and password.
- **Sign Up/Register:** New customers can register by filling in their details to create an account.
- **Create Account/Login:** Customers can create new account or log in to the system with their information.
- **View Shipment Details:** Customers can see detailed information about their shipments, including status and delivery times.
