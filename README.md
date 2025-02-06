# Automated-Data-Management-System


### **Functionality**
This system is designed to upload structured data into an SQL database efficiently. The process ensures data integrity and provides appropriate feedback in case of failures.

### **Process Flow**
1. **File and Folder Verification:**
   - Check if the specified folder exists.
   - Verify if the required file is present in the folder.
   - Ensure that the file contains valid data.
   - If any check fails, return an appropriate error message.

2. **Data Reading:**
   - Read structured data using the Pandas library.
   - Validate that the file is not empty and is correctly formatted.

3. **Database Connection:**
   - Establish a connection with the SQL database.
   - Use SQLAlchemy for efficient and scalable database interactions.

4. **Table Handling and Data Insertion:**
   - Check if the required table already exists in the database.
   - If the table exists, directly insert the new data and confirm insertion.
   - If the table does not exist, create it dynamically based on the data structure and then insert the data.
   - Print confirmation upon successful data insertion.

### **Key Features and Enhancements**
- **Error Handling:** Provides appropriate error messages for missing files, folders, or invalid data.
- **Modular Design:** Functions are structured for better readability and reusability.
- **Scalability:** Uses SQLAlchemy to support different database types.
- **Automation:** Automates table creation if it does not exist, reducing manual interventions.

This system ensures efficient data management while maintaining data integrity and scalability.
