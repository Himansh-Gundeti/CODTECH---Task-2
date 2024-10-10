NAME: HIMANSH GUNDETI 
ID:CT08DS7970 
DOMAIN:JAVA PROGRAMMING 
DURATION:“10TH SEP 2024 to 10TH OCT 2024” 
MENTOR:SRAVANI GOUNI

### Description:

This Java program simulates a simplified Hospital Management System with modules for patient registration, appointment scheduling, electronic health records (EHR), billing, inventory management for medical supplies, and staff management. Below is a breakdown of the different components:

1. **Main Class (`HospitalManagementSystem`)**:
   - **Data storage**: Uses `ArrayList` to store patients, staff, and medical supplies.
   - **User Interface**: Presents a menu-driven interface for users to interact with the system by choosing different options.
   - **Modules**: Each menu option directs the user to a different module, including:
     - **Patient Registration**: Allows users to register new patients with name, age, gender, and ID.
     - **Appointment Scheduling**: Schedules an appointment by entering patient ID, date, and time.
     - **Electronic Health Records (EHR) Management**: Enables users to manage and update patients' health conditions and prescribed medications.
     - **Billing and Invoicing**: Generates and displays a bill for a patient's treatment.
     - **Inventory Management**: Displays and updates the stock of medical supplies.
     - **Staff Management**: Displays available staff with their respective roles.

2. **Helper Classes**:
   - **Patient Class**: Represents a patient with attributes like name, age, gender, patient ID, health condition, and medication. The class includes setter methods for updating health condition and medication.
   - **Staff Class**: Represents a staff member with attributes such as name, role, and staff ID.
   - **MedicalSupply Class**: Represents medical supplies with attributes like name and quantity. A setter method is included to update the quantity of supplies.

3. **Seed Data**:
   - The program uses predefined (seed) data for initial patients, staff, and medical supplies to demonstrate functionality. This allows the user to interact with the system without needing to add entries from scratch.
   
4. **User Interaction**:
   - A `while` loop drives the program's main menu, allowing the user to interact with various modules. The loop continues until the user chooses to exit the system.
   - **Scanner** is used to accept user input for various operations like entering patient details, updating health records, scheduling appointments, and updating inventory.
   
5. **Helper Methods**:
   - **findPatientById**: Finds and returns a patient based on their ID.
   - **findSupplyByName**: Finds a specific medical supply by its name.
   - These methods simplify operations like managing patient records or updating inventory.

### Conclusion:

This simplified Java-based Hospital Management System provides a foundational structure for managing key operations in a healthcare facility. The system enables:
- **Patient management**: Registration, scheduling appointments, and maintaining electronic health records.
- **Billing**: Generation of invoices based on treatment costs.
- **Inventory control**: Keeping track of medical supplies with the ability to update quantities.
- **Staff management**: Displaying hospital staff and their roles.

While basic in functionality, this program demonstrates core principles of object-oriented programming, such as encapsulation (using classes like `Patient`, `Staff`, and `MedicalSupply`), modularity (separating different functionalities into distinct methods), and user interaction.
Outuput:

![image](https://github.com/user-attachments/assets/d7bad8eb-1d13-464f-b145-feb39569d923)

