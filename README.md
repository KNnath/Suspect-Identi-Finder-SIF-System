
![Home](https://github.com/user-attachments/assets/7b6e30dd-bb30-4edd-b2a8-b61ca4127fe7)

# Suspect Identi-Finder 

The Suspect Identity Finder is a full-stack application designed to enhance security by identifying individuals from images or video feeds. By utilizing advanced facial recognition technologies, the system analyzes and matches facial features against a secure database of known individuals stored in MongoDB. The platform integrates a user-friendly interface with robust backend logic, offering real-time identification and generating detailed reports of potential suspects. Built with HTML, JavaScript, Python, CSS, and MongoDB, the project combines frontend and backend technologies for a seamless user experience and enhanced security. 

This project is a Suspect Identi-Finder System designed for organizations, such as colleges and corporate offices, to monitor and identify individuals within their premises securely and efficiently. It aids in detecting and identifying authorized personnel while flagging unknown or unauthorized individuals. The system begins with an employee registration process, where a designated person enrolls each employee by capturing their image and recording essential information such as Name, Roll Number, and Department. This information is stored in **MongoDB**, a secure, cloud-based data storage solution that handles large datasets, including JSON files and face embeddings, making it ideal for maintaining high-performance face recognition capabilities.

The face detection is performed using **MTCNN** for accuracy, while **FaceNet** handles recognition by comparing live inputs with stored profiles. When a known face is detected, the system displays the corresponding Name, Roll Number, and Department, while unknown faces are flagged as “Unknown” with this details admin can easily retrieve the information of that person. Only the Admin has access to real-time detection features, which automatically activate upon login. Additionally, if a registered user forgets their login credentials, they must request a password reset from the Admin, who will reset the password and send new credentials securely via email.

The Admin can also retrieve detailed information on any recognized individual, and if needed, generate a **report card** containing comprehensive details, which is beneficial for record-keeping or further investigation. The application is built on **Python Flask** for backend development and uses **HTML, CSS, and JavaScript** for a user-friendly web interface. This secure and scalable system provides organizations with a reliable tool for real-time face recognition, enhancing their ability to manage security and access control within their premises effectively.


All references Frontend Page was available..

For Contact - koushiknath003@gmail.com
