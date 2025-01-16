# MasterTicket Project

MasterTicket

MasterTicket is a comprehensive QR Code ticket management system designed to make implementing QR Code ticket in any events easy. The project is composed of two key components:

1. [MasterTicket System](https://github.com/HKManus/MasterTicket_System): for Ticket Generation and Distribution
- Generates unique QR code tickets for each participant by importing a participant list
- Creates a spreadsheet with embedded QR codes, facilitating easy email distribution of e-tickets through mail merge

2. [MasterTicket_Scanner](https://github.com/HKManus/MasterTicket_Scanner): for Ticket Scanning and Validation
- Provides a QR code scanner application for verifying ticket authenticity
- Checks ticket details including participant name and entry timestamp
- Prevents duplicate entries by tracking and blocking multiple scans of the same ticket
