
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
