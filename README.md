MYCLICKDOCTOR is an online platform that enables patients to consult with doctors remotely via video calls. The application facilitates seamless communication between healthcare providers and patients, ensuring convenient and efficient medical consultations.
Features
•	Doctor & Patient Registration – Users can sign up as doctors or patients.
•	Appointment Scheduling – Patients can book appointments with available doctors.
•	Secure Video Consultations – Powered by Jitsi for real-time video calls.
•	Chat & Messaging – Secure communication between doctors and patients using SignalR.
•	Medical Records Management – Patients can upload and store their medical history.
•	Payment Integration – Barion payment gateway for secure online transactions.
Tech Stack
•	Frontend: Angular (MUI Tools, TypeScript)
•	Backend: .NET Core
•	Database: SQL Server
•	Video Call: Jitsi
•	Chat: SignalR
•	Storage: AWS S3 (for storing files and medical records)
•	Task Management: Celery (for background tasks like document conversion using LibreOffice)
•	Payment Gateway: Barion
Installation
Prerequisites
•	.NET Core installed
•	Node.js and npm installed
•	AWS S3 configured for file storage
•	Jitsi configured for video calls
•	SignalR configured for real-time chat
•	Barion payment gateway setup
•	Celery and Redis configured for task management




Setup
Backend
cd backend
# Install dependencies
dotnet restore
# Run the application
dotnet run
Frontend
cd frontend
# Install dependencies
npm install
# Start the frontend
ng serve
Configuration
•	Jitsi: Set up a Jitsi server or use the Jitsi Meet API.
•	AWS S3: Configure storage credentials for file uploads.
•	LibreOffice & Celery: Ensure LibreOffice is installed and Celery workers are running for document processing.
•	SignalR: Set up SignalR for real-time chat between users.
•	Barion: Configure Barion API keys for payment processing.
Contributing
Contributions are welcome! Please follow these steps:
1.	Fork the repository.
2.	Create a new branch.
3.	Make your changes and commit them.
4.	Push to your fork and submit a pull request.
License
This project is licensed under the MIT License.
Contact
For any inquiries, please contact .
________________________________________
Note: This project is running in Hungary.

