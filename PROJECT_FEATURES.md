
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
