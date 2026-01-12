Title

Week 4 – SSH and Firewall

What I learned

What SSH is and why it is used for secure remote access

The role of firewalls in controlling network traffic

Basic concepts of inbound and outbound rules

What I did

Learned how SSH allows secure communication between systems

Understood firewall rules and how they protect systems

Studied how firewalls block unauthorized access

Reflection
This week helped me understand how systems are protected when connected to a network.
I learned that SSH encryption and firewall rules are critical for preventing attacks.
These tools are essential for secure system administration.

This command checks whether SSH is installed on the system and shows the SSH version. SSH (Secure Shell) is used to access systems remotely using encrypted communication.
<img width="1135" height="54" alt="Screenshot 2025-12-18 145126" src="https://github.com/user-attachments/assets/e622c3a2-5008-4ee6-b4db-a90b16f05f86" />

This command installs the OpenSSH server package. Installing the SSH server allows the system to accept secure remote connections.
<img width="1011" height="317" alt="Screenshot 2025-12-18 145119" src="https://github.com/user-attachments/assets/b87f2874-26fc-4c50-951e-c68f5d06905b" />

This command checks the current status of the SSH service. It confirms whether SSH is running correctly on the system.
<img width="889" height="165" alt="Screenshot 2025-12-18 145104" src="https://github.com/user-attachments/assets/24782b30-82c6-4185-8fe6-f75f777adfc0" />

This command ensures that the SSH service starts automatically every time the system boots. This is important for servers that require remote access.
<img width="1059" height="227" alt="Screenshot 2025-12-18 145056" src="https://github.com/user-attachments/assets/c10b8ff8-369c-4f60-adb1-39522bf56b78" />

This command checks the current status of the Uncomplicated Firewall (UFW). Firewalls control network traffic to protect the system from unauthorized access.
<img width="726" height="244" alt="Screenshot 2025-12-18 145612" src="https://github.com/user-attachments/assets/6b4e9ed3-7966-4409-8128-146d43d2b78e" />

This command allows SSH connections through the firewall. This ensures that enabling the firewall does not block legitimate SSH access.
<img width="625" height="40" alt="Screenshot 2025-12-18 145544" src="https://github.com/user-attachments/assets/58762171-c8f0-4860-ba5d-852bed32fb46" />

This command enables the firewall, activating network protection for the system.
<img width="631" height="68" alt="Screenshot 2025-12-18 145536" src="https://github.com/user-attachments/assets/a5672983-f6d0-4eb1-a937-58df1c20ef80" />

This command displays detailed firewall rules and confirms that SSH is allowed while the firewall is active.
<img width="810" height="161" alt="Screenshot 2025-12-18 145526" src="https://github.com/user-attachments/assets/88e7b713-cc29-45eb-9fab-d028861d2b7a" />
