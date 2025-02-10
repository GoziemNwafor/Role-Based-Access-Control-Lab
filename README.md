# Role-Based-Access-Control-Lab

## Objective

The objective of this project is to create a proof of concept showing how Azure users and groups are created. This project also aims to demonstrate how role-based access control is used to assign roles to groups.

### Skills Learned

- Implement Role-Based Access Control (RBAC): Assign roles to users, groups, and applications to manage permissions in Azure.
- Create and Manage Custom Roles: Define and configure custom roles with specific permissions.
- Use Azure Portal, CLI, and PowerShell for RBAC: Apply RBAC settings using different management tools.
- Assign Least Privilege Access: Implement the principle of least privilege to secure Azure resources.
- Audit and Monitor RBAC Assignments: Review and analyze role assignments for compliance and security.

### Tools Used

- Azure Portal – GUI for managing RBAC roles and assignments.
- PowerShell – Command-line tool for automating RBAC configurations.
- Azure CLI – Cross-platform command-line tool for managing Azure resources.

## Steps
* Step 1: Use the Azure Portal to create a user (Joseph Price) and group (Senior Admins), and assign the user to the group.

![IMG_2221](https://github.com/user-attachments/assets/d274cd19-99c2-4490-a209-8b560de74c87)
![Screenshot 2025-02-09 015613](https://github.com/user-attachments/assets/96b03402-40a4-4001-9d67-3c3803a8824a)
![Screenshot 2025-02-09 015531](https://github.com/user-attachments/assets/6ac84cf9-3c24-4b2e-b531-a8558c5491e4)



* Step 2: Create the scanner class.

![image](https://github.com/user-attachments/assets/40df6b55-d435-4c4d-9e11-d292437f7416)

* Step 3: URL handling to ensure the same page is not scanned twice.

![image](https://github.com/user-attachments/assets/58efc06f-a0a3-4cc3-8848-48e5000f5a38)

* Step 4: Find all links in webpage's HTML content to that point to target website.

![image](https://github.com/user-attachments/assets/9e4d6e9e-1d1b-48b9-926e-cf743f788df9)

* Step 5: Test for XSS (Cross-Site Scripting).

![image](https://github.com/user-attachments/assets/89fa697e-2e5a-4f1c-b36b-964621dbea8b)

* Step 6: Test for SQL Injection.

 ![image](https://github.com/user-attachments/assets/ee11ad8f-02fd-4d57-9f55-0c5072b82bfb)

* Step 7: Scan a single URL.

![image](https://github.com/user-attachments/assets/29792f7f-9952-47f8-a061-096f429a4258)

* Step 8: Create the main scanning function.

![image](https://github.com/user-attachments/assets/6d4aaccb-045f-41e2-9992-798305e71bf9)

* Step 9: Use the scanner in the console.

![image](https://github.com/user-attachments/assets/9008adc0-ba64-4cb4-a913-4e9379de3077)


















