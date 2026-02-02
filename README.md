## 📊 Dataset & Data Model

The dataset consists of 5 structured tables designed using a star schema approach:

### Fact Table
- FactEmployee
  - Stores core HR transactional data
  - Attrition status
  - Salary
  - Attendance
  - Performance score

### Dimension Tables
- City → Employee location data
- Department → Organizational structure
- Employee → Personal employee information
- JobTitle → Job roles and levels

### Data Model
- One-to-many relationships between FactEmployee and dimension tables
- Optimized for analytical queries and reporting
- Ensures data consistency and performance


