# protocol_email_network
📧 Network Email Protocol Project
📝 Description

This project is a Network Simulation of an Email Protocol created using Packet Tracer.
It demonstrates how a mail server and client PCs communicate over a network to send and receive emails.

Features:

Configurable Mail Server with multiple user accounts

Email Client PCs that can send and receive emails

Simulated network using Switches and IP configuration

Domain name setup for email addresses (simulated, not real-world)

🖥️ Requirements

Packet Tracer (Version 8.x recommended)

Basic understanding of IP addressing and network topology

🏗️ Setup Instructions

Open the project file in Packet Tracer (.pkt file)

Verify the network topology:

1 Server

2+ PCs

1 Switch connecting all devices

Server Configuration:

Go to Server → Config → Services → Email

Turn the service ON

Add user accounts with username and password

Set the Domain Name (example: nti.com)

PC Configuration:

Go to PC → Desktop → Email Client

Enter email address, password, and set Incoming/Outgoing server to the Server IP or hostname

Test Email:

Send an email from one PC to another and verify it is received

⚡ Common Issues

Connection Timed Out:

Ensure the Server’s email service is ON

Verify IP addresses and subnet masks of all devices

Check the correct port for email services: SMTP (25), POP3 (110), IMAP (143)

DNS/Domain Issues:

Use the Server IP directly if domain name is not resolving
