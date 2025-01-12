
Here's the revised README with the acknowledgments updated to thank the teachers:

Hashing for Security: A Comprehensive Approach to Data Integrity and Authentication
Features
🔒 Custom Hashing Algorithm

Inspired by SHA-256, this system uses salts, peppers, and a custom CHARSET for secure and unique password hashing.
Ensures collision resistance, preimage resistance, and an avalanche effect for robust security.
👤 Secure User Management

Features include user signup, signin, password recovery, and two-factor authentication.
Supports account recovery with security questions and secure deletion of user data.
⚙️ Memory Security

Implements SecureZeroMemory to erase sensitive data from memory, preventing unauthorized access.
📚 Linked List Data Storage

Efficiently stores user data using linked list structures to ensure fast and secure data management.
🔑 Role-Based Authentication

Differentiates access levels, granting administrative privileges for advanced functionalities like user list management.
Methodology
The project was developed through a structured process that includes:

Data Collection and Storage:

User data is stored in a linked list with nodes for each user.
Passwords and security questions are hashed with salts and peppers for added security.
Custom Hashing Mechanism:

Input messages are padded, processed, and hashed using custom SHA-256-like operations.
Salts and peppers are introduced to thwart rainbow table and brute-force attacks.
Security Features:

Avalanche effect: A small change in input drastically changes the hash.
Memory security: Securely wipes sensitive data from memory after processing.
User Interactions:

Signup includes strong password enforcement and optional two-factor authentication.
Password recovery uses security questions or denies recovery if two-factor authentication is not enabled.
Results and Conclusion
The system demonstrated exceptional performance in:

Securing user data with advanced cryptographic techniques.
Handling diverse scenarios, including authentication failures and recovery processes.
Maintaining user-friendly interaction while ensuring robust security.
