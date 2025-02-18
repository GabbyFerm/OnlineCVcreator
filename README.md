# Online CV Creator
## Vision
The Online CV Creator aims to provide users with an intuitive platform to create, edit, and manage professional CVs. The application will allow users to: 
•	Register and log in securely.
•	Input personal, educational and professional details.
•	Save, edit, and export CVs in PDF format.
•	Use AI-powered text generation to assist in writing sections of their CVs based on keywords.
The goal is to simplify the CV creation process, making it accessible and efficient for users of all technical skill levels.

## Functional Requirements
These are the core features the system must provide: 
1.	User Authentication: 
o	Users can register, log in, and log out.
o	Password recovery functionality.
2.	CV Management: 
o	Users can create, edit, and delete CVs.
o	Users can save CVs to their account.
3.	PDF Export: 
o	Users can export their CVs as PDF files.
4.	AI-Powered Text Generation: 
o	Users can input keywords, and the system will generate text suggestions for CV sections.
5.	Dashboard: 
o	Users can view a list of saved CVs and manage them.

## Non-Functional Requirements
These define the quality attributes of the system: 
1.	Performance: 
o	The system should handle up to 100 concurrent users without performance degradation.
2.	Scalability: 
o	The system should be scalable to support future growth in user base.
3.	Security: 
o	User data must be encrypted in transit and at rest.
o	Implement secure authentication mechanisms (e.g., hashed passwords).
4.	Usability: 
o	The UI should be intuitive and responsive across devices.
5.	Availability: 
o	The system should have 99.9% uptime.
6.	Maintainability: 
o	The codebase should follow clean coding principles and be well-documented for future developers.

## MoSCoW Prioritization
Must Have:
•	User authentication (register, login, logout).
•	CV creation, editing, and saving.
•	PDF export functionality.
•	AI-powered text generation.
Should Have:
•	Dashboard for managing saved CVs.
•	Password recovery.
Could Have:
•	Multi-language support for CVs.
•	Pre-designed CV templates.
Won’t Have:
•	Integration with job portals (e.g., LinkedIn).
•	Real-time collaboration on CVs.
