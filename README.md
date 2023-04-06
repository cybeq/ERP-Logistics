## :construction: Long term project! Under development
#### started 6.04.2023
![img.png](schemat-aplikacji.pdf)

##  [> SEE FULL APPLICATION AND WORKFLOW DIAGRAM](schemat-aplikacji.pdf)

----------------------------------------------------
#### [System details](#details)
1. [Company jobs](#ROLES)
2. [Workflow](#WORKFLOW)
#### [Alerts and notifications](#Notifications)
#### [Updates](#Updates)


# :ocean: Logistics ERP System

This is an enterprise resource planning (ERP) system developed specifically for logistics companies. It is designed to streamline and automate various logistics processes, including inventory management, supply chain management, transportation management, and order fulfillment.

## Project Information

This is a long-term project that is constantly being developed to improve functionality and add new features. The system is being built using the **Model-View-Controller (MVC)** design pattern and is developed using modern technologies.
Designed with Polish and English support & interface

## Technologies Used

- Laravel
- Angular2
- MySQL
- HTML
- SCSS
- TypeScript
- JavaScript

## Features

- Track inventory levels in real-time
- Automate supply chain management processes
- Optimize transportation routes and schedules
- Streamline order fulfillment
- Generate reports for data analysis

## Future Development

- Integration with other logistics systems and platforms
- Integration with scanning devices to ensure real-time data exchange across all the warehouse workarea
- Implement machine learning and AI technologies to optimize logistics processes
- Incorporate blockchain technology for enhanced data security and transparency
- Develop mobile applications for logistics management on-the-go

## Installation and Usage

To use this application, clone the repository and run it on a local server. Please note that this application is currently in development and may contain bugs or incomplete features.

```bash
git clone https://github.com/your-username/logistics-erp-system.git
cd logistics-erp-system
npm install
npm start
```

## Contributors

- Mateusz Swiderski (mateuszss00b@gmail.com) - Owner and Developer

## License

This project is not licensed for public use and may not be shared or distributed without the owner's agreement.

# **********************************

# System details
#details
---------------------------------------

#### Roles
- Warehouse Manager
- Inventory Manager
- Shipping Worker
- Material Handler
- Team Leader
- Order Picker
- Packer
- Quality Control Inspector
- Forklift Operator
- Maintenance Technician
- IT Support Specialist
- Data Analyst
- Operations Manager
- Sales Representative
- Customer Service Representative

---------------------------------------------------

#### WORKFLOW
#####    Task: Receiving of goods
- Influence on work: Ensures that goods are received in a timely and accurate manner, minimizing delays and errors in the warehouse operations.
- Influence on warehouse: Proper receiving processes help prevent inventory discrepancies and ensure accurate inventory levels.
- Influence on system: Accurate and timely receiving information helps the WMS/ERP system maintain accurate inventory records, supplier information, and purchase orders.
- Notification to receiving clerk to receive goods and perform quality checks
- Notification to accounts payable to reconcile invoices with purchase orders and receiving reports
- Notification to inventory manager to update inventory levels and locations
- Notification to sales and customer service departments to update product availability information
- Notification to the supplier or carrier to schedule delivery appointments
- Quality control inspection process and documentation for incoming goods
- Electronic data interchange (EDI) with suppliers to receive advanced shipping notices (ASNs) and purchase orders
#####    Task: Put-away of goods
- Influence on work: Proper put-away processes ensure that goods are stored in the correct location, reducing the time and effort required for order picking and reducing the risk of errors.
- Influence on warehouse: Optimized put-away processes help maximize storage capacity and reduce the amount of time required to locate and retrieve items.
- Influence on system: Accurate put-away information helps the WMS/ERP system maintain accurate inventory records, reduce inventory carrying costs, and optimize space utilization.
- Notification to material handler to move goods to designated locations based on product attributes such as weight, size, and temperature requirements
- Notification to inventory manager to update inventory locations and levels
- Notification to order picker to locate goods for customer orders based on inventory location and attributes
- Put-away optimization based on product velocity and demand forecasting
- Use of RFID or barcoding technology for efficient and accurate put-away processes
- Cross-docking processes to bypass put-away and immediately move goods to outbound dock doors
#####    Task: Order picking
- Influence on work: Efficient order picking processes ensure that customer orders are fulfilled accurately and quickly, reducing the time to ship and improving customer satisfaction.
- Influence on warehouse: Optimized order picking processes help reduce the time and effort required to retrieve items, improving overall warehouse efficiency.
- Influence on system: Accurate order picking information helps the WMS/ERP system maintain accurate inventory records, reduce inventory carrying costs, and optimize space utilization.
- Notification to order picker to pick goods for customer orders based on order details and shipping requirements
- Notification to packer to pack goods for shipping based on shipping requirements and product attributes
- Notification to shipping clerk to schedule shipment and create shipping labels based on carrier requirements and shipping rules
- Voice-directed picking technology for hands-free and efficient order picking
- Batch picking to fulfill multiple orders simultaneously and reduce travel time
- Collaborative robots or autonomous mobile robots (AMRs) to assist with order picking and increase productivity
#####    Task: Inventory management
- Influence on work: Effective inventory management ensures that the right inventory is available at the right time, reducing stockouts and overstocking.
- Influence on warehouse: Optimized inventory management helps reduce inventory carrying costs, improve space utilization, and prevent inventory discrepancies.
- Influence on system: Accurate and timely inventory information helps the WMS/ERP system maintain accurate inventory records, optimize inventory levels, and generate demand forecasts.
- Notification to inventory manager to monitor inventory levels, perform demand forecasting, and optimize inventory levels and locations-
- Notification to purchasing department to update purchase orders or supplier information based on inventory levels and demand forecasts
- Notification to sales and customer service departments to update product availability information based on inventory levels and lead times
- Cycle counting processes to ensure inventory accuracy and identify discrepancies
- Safety stock and buffer inventory management for critical items or unpredictable demand
- Integration with supplier and customer systems for real-time visibility of inventory levels and demand forecasting
#####    Task: Maintenance and repair
- Influence on work: Proper maintenance and repair of equipment helps prevent downtime, reducing delays and increasing productivity.
- Influence on warehouse: Effective maintenance and repair processes help prevent accidents and equipment failures, improving overall safety and efficiency.
- Influence on system: Accurate and timely maintenance and repair information helps the WMS/ERP system optimize maintenance schedules, reduce equipment downtime, and improve data accuracy.
- Notification to maintenance technician to perform preventive or corrective maintenance on equipment based on usage and performance data from the WMS/ERP system
- Notification to operations manager to schedule maintenance downtime based on production and customer needs
- Predictive maintenance based on machine learning algorithms and IoT sensor data
- Remote monitoring and diagnostics for equipment maintenance and repair
- Spare parts management and tracking for efficient maintenance and repair processes
#####    Task: Data analysis and reporting
- Influence on work: Data analysis and reporting help identify areas for improvement and support decision-making, improving overall warehouse efficiency.
- Influence on warehouse: Actionable insights from data analysis and reporting help optimize warehouse operations and improve customer satisfaction.
- Influence on system: Accurate and timely data analysis and reporting help the WMS/ERP system identify areas for improvement, optimize inventory levels, and generate demand forecasts.
- Notification to data analyst to generate reports on inventory levels, order fulfillment, product performance, and other key performance indicators (KPIs) based on data from the WMS/ERP system
- Notification to operations manager to review and analyze reports for decision-making and continuous improvement
- Machine learning algorithms for predictive analytics and optimization
- Real-time data visualization and dashboard for quick insights and decision-making
- Integration with external data sources such as weather forecasts, market trends, and social media sentiment analysis for improved demand forecasting
#####    Task: System administration and support
- Influence on work: Proper system administration and support help ensure system stability and data security, reducing the risk of system failures and data breaches.
- Influence on warehouse: Effective system administration and support help ensure that warehouse operations are not impacted by system downtime or errors.
- Influence on system: Accurate and timely system administration and support help the WMS/ERP system maintain data accuracy, prevent system failures, and optimize system performance.
- Notification to IT support specialist to perform system maintenance, updates, and backups to ensure system stability and data security
- Notification to operations manager to provide training and support to warehouse employees on using the WMS/ERP system and best practices for warehouse operations
- Cloud-based system hosting and automatic software updates for seamless system maintenance
- Access control and user permissions management to ensure data security and compliance
- Disaster recovery and business continuity planning to minimize system downtime and data loss
#####   Task: Accounts payable and receivable
- Influence on work: Proper management of accounts payable and receivable ensures timely payments to suppliers and accurate invoicing to customers.
- Influence on warehouse: Accurate accounts payable and receivable information helps ensure that the correct inventory levels are maintained and reduces the risk of overstocking or stockouts.
- Influence on system: Accurate and timely accounts payable and receivable information helps the WMS/ERP system maintain accurate inventory records and generate financial reports.
- Automated invoice processing and payment scheduling for improved efficiency and accuracy
- Integration with banking and payment systems for real-time payment processing
- Credit management and collections processes for accounts receivable management
  #####    Task: Budgeting and forecasting
- Influence on work: Effective budgeting and forecasting helps allocate resources efficiently and make informed decisions about future investments.
- Influence on warehouse: Accurate budgeting and forecasting helps optimize inventory levels, reduce costs, and improve warehouse efficiency.
- Influence on system: Accurate and timely budgeting and forecasting information helps the WMS/ERP system optimize inventory levels and generate demand forecasts.
- Scenario planning and sensitivity analysis for strategic decision-making
- Capital expenditure planning and analysis for investments in new technology or equipment
- Integration with financial accounting systems for accurate budgeting and forecasting based on historical financial data.

#####     Task: Team leadership and management
- Influence on work: Effective team leadership and management helps ensure that team members are motivated and working together towards common goals.
- Influence on warehouse: Effective team leadership and management helps improve overall warehouse productivity and reduce the risk of accidents or errors.
- Effective communication: Good team leadership and management requires regular communication with team members to ensure that everyone is on the same page and working towards common goals. This helps to prevent misunderstandings and reduces the risk of mistakes or errors.
- Role impact on system: Effective team management involves using WMS/ERP system data to track employee performance and identify areas for improvement. This information can be used to optimize workforce planning and scheduling, ensuring that the right people are in the right place at the right time.

  #####    Task: Forklift and order picker management
- Influence on work: Proper management of forklift and order picker operations helps ensure safe and efficient warehouse operations.
- Influence on warehouse: Effective forklift and order picker management helps reduce the risk of accidents and improve overall warehouse efficiency.
- Equipment maintenance: Proper forklift and order picker management includes regular maintenance and repair to ensure that equipment is functioning safely and efficiently. This can help reduce the risk of accidents and prevent downtime due to equipment failure.
- Role impact on system: Accurate and timely forklift and order picker management information can be used to optimize warehouse layout and reduce operational costs. For example, by analyzing which areas of the warehouse require the most equipment usage, the system can make recommendations for better equipment placement and utilization.
#####     Task: Quality control and assurance
- Influence on work: Effective quality control and assurance processes help ensure that products meet customer expectations and regulatory requirements.
- Influence on warehouse: Optimized quality control and assurance processes help reduce the risk of product defects and returns, and improve customer satisfaction.
- Inspection and testing: Effective quality control and assurance requires regular inspection and testing of products to ensure that they meet customer expectations and regulatory requirements. This can involve both manual inspections and automated testing using specialized equipment.
- Role impact on system: Accurate and timely quality control and assurance information can help the WMS/ERP system maintain accurate inventory records and generate demand forecasts. By tracking product defects and returns, the system can identify patterns and adjust inventory levels accordingly, ensuring that the warehouse is stocked with the right products at the right time.

-----------------------------------------------------
## NOTIFICATIONS
# Low inventory alert
- Influence on work: A low inventory alert can prompt employees to reorder products, preventing stockouts and ensuring timely delivery to customers.
- Influence on warehouse: By alerting warehouse employees to low inventory levels, the system can help them prioritize picking and replenishment tasks, ensuring that critical inventory levels are maintained.
- Influence on system: Low inventory alerts can trigger automated reorder processes in the WMS/ERP system, helping to optimize inventory levels and reduce the risk of stockouts.

# Shipment delay alert
- Influence on work: A shipment delay alert can prompt employees to take corrective action, such as expediting shipping or communicating with the customer to adjust delivery expectations.
- Influence on warehouse: By alerting warehouse employees to shipment delays, the system can help them prioritize picking and packing tasks to ensure that the shipment is ready as soon as possible.
- Influence on system: Shipment delay alerts can trigger automated communication with carriers or customers, helping to minimize the impact of the delay and maintain customer satisfaction.

# Order fulfillment confirmation
- Influence on work: A fulfillment confirmation can help ensure that orders are accurately picked and packed, reducing the risk of errors or returns.
- Influence on warehouse: By confirming order fulfillment, the system can help warehouse employees prioritize tasks and ensure that all orders are fulfilled in a timely manner.
- Influence on system: Order fulfillment confirmations can update inventory levels and trigger automated billing processes, helping to maintain accurate inventory records and generate financial reports.

# Quality control alert
- Influence on work: A quality control alert can prompt employees to perform additional checks and inspections, reducing the risk of product defects and returns.
- Influence on warehouse: By alerting warehouse employees to quality control issues, the system can help them prioritize inspection and rework tasks, ensuring that all products meet customer expectations.
- Influence on system: Quality control alerts can update inventory records and trigger automated communication with suppliers or customers, helping to maintain accurate inventory levels and improve customer satisfaction.

# Equipment maintenance alert
- Influence on work: An equipment maintenance alert can prompt employees to perform necessary repairs or maintenance, reducing the risk of accidents and downtime.
- Influence on warehouse: By alerting warehouse employees to equipment maintenance needs, the system can help them prioritize tasks and ensure that equipment is always in good working condition.
- Influence on system: Equipment maintenance alerts can trigger automated maintenance requests and generate maintenance logs, helping to optimize equipment performance and reduce operational costs.

---------------------------------------------------

# Updates

#### 1. 06.04.2023 || README.md created, empty project initiated.