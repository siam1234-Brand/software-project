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
