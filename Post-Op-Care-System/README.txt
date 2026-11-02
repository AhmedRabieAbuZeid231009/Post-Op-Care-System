POST-OP CARE — COMPLETE FRONT-END PROTOTYPE (VERSION 10)
======================================================

HOW TO OPEN
1. Extract the ZIP file.
2. Open the Post-Op-Care-System folder.
3. Double-click index.html and open it with Chrome or Edge.
4. Keep index.html, app.js, style.css, and the images folder together.
5. The project runs locally; no Java, server, build tool, or internet connection is required for the included photos and core interactions.

THE SIX REQUIRED SCREENS (NAMES ARE EXACT)
1. Login & Registration
   Allows patients and doctors to securely access the Post-Op Care system using their assigned account.
2. Patient Dashboard
   Gives the patient a quick overview of recovery progress, recent health readings, medications, and important alerts.
3. Daily Check-in
   Allows the patient to submit daily symptoms and health readings so the doctor can monitor recovery remotely.
4. Medication & Wound Care
   Helps the patient review prescribed medications, track doses, and submit wound photos for follow-up.
5. Doctor Dashboard
   Provides the doctor with a summary of assigned patients, urgent alerts, and cases that need follow-up.
6. Patient Details & Reports
   Allows the doctor to review a patient's medical record, recovery history, wound updates, and generate a follow-up report.

DEMO ACCOUNTS
Doctor:  doctor@postopcare.com / 123456
Patient: patient@postopcare.com / 123456
Doctor display name: Dr. Ahmed Rabie

HOW TO OPEN ALL SCREENS
After logging in, the left sidebar shows all five post-login screens under two groups: Patient Workspace and Doctor Workspace. Click any page name. Selecting a screen in the other group automatically opens the matching built-in demo account, so all six required screens can be demonstrated from the same menu. The top-right workspace button also switches between the demo accounts.

FUNCTIONAL FEATURES
- Login and registration for patient and doctor demo roles, password show/hide, form validation, and account selection.
- Patient Dashboard with recovery progress, days after operation, vital readings, medication status, appointment details, and alerts.
- Daily Check-in with pain score, temperature, heart rate, oxygen saturation, wound condition, symptom checkboxes, notes, validation, and saved history.
- Automatic doctor alerts for configured concerning demo readings (for example high pain, fever-range temperature, low oxygen, breathing difficulty, or concerning wound status).
- Medication & Wound Care with dose status toggles, wound-photo upload, preview, save/remove, and an included surgical-stitches reference photograph.
- Doctor Dashboard with patient statistics, recovery trend, urgent alerts, recent patients, add-patient action, and patient links.
- Patient Details & Reports with patient search, record selection, edit patient details, medical history, recovery progress, wound updates, and a print / Save as PDF report view.
- Notification center, mark-alert-reviewed, mark-all-reviewed, role switching, and logout.

IMAGE FOLDER
The images folder contains:
- doctor-patient-hero.jpg — hospital scene used on Login & Registration and dashboards.
- doctor-profile.jpg — doctor portrait used as Dr. Ahmed Rabie’s account photo in the sidebar, top bar, doctor dashboard, and care-team cards.
- patient-profile.jpg — demo patient portrait used in the sample patient account and patient record.
- surgical-stitches-reference.jpg — full clinical reference photograph used in Medication & Wound Care and Patient Details & Reports.
- sutures-closeup.jpg — additional close-up reference of the surgical stitches used in the wound photo gallery and patient wound record.
The doctor and patient portrait crops are derived from the project hospital photo to keep the UI consistent. These are demonstration/reference photographs, not verified identity photos or actual patient wound records.

IMPORTANT LIMITATION
This is a front-end academic prototype. Information is stored in the current browser using localStorage; it is not sent to a hospital, doctor, or remote database. It is not secure clinical software and must not be used for real patient care or real patient-identifiable information. Medication names and values are illustrative examples only.
