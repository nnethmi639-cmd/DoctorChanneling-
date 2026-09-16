<img width="540" height="1200" alt="WhatsApp Image 2026-09-16 at 12 10 25" src="https://github.com/user-attachments/assets/0e8b2465-ef92-409b-8714-de3e50e9f7a8" />

Doctor Channeling App

An Android mobile application for booking doctor appointments online. Built as an HNDIT academic project using Java (Android Studio) with Firebase as the backend.

Features

 Patient Module
- Register and login
- Browse list of approved doctors
- Book an appointment (select date and time)
- View and cancel own appointments

 Doctor Module
- Register and login (requires admin approval before appearing to patients)
- View appointments booked by patients
- Mark appointments as completed

Admin Module
- Login with admin credentials
- View pending doctor registrations
- Approve or reject doctor accounts

 Tech Stack

- **Language:** Java
- **IDE:** Android Studio
- **Backend:** Firebase
  - Firebase Authentication (Email/Password)
  - Firebase Realtime Database
- **UI Components:** RecyclerView, CardView, Material Components

 Project Structure

```
app/src/main/java/com/example/doctorchannelingg/
├── Models (Doctor.java, Appointment.java)
├── Adapters (DoctorAdapter, AppointmentAdapter, PendingDoctorAdapter)
├── Patient screens (PatientLoginActivity, PatientRegisterActivity, DoctorListActivity, BookAppointmentActivity, MyAppointmentsActivity)
├── Doctor screens (DoctorLoginActivity, DoctorRegisterActivity, DoctorDashboardActivity)
└── Admin screens (AdminLoginActivity, AdminDashboardActivity)
```

Setup

1. Clone this repository
2. Open in Android Studio
3. Create a Firebase project and add your own `google-services.json` file to the `app/` folder
4. Enable Email/Password authentication in Firebase Console
5. Create a Realtime Database and set rules to allow read/write (test mode)
6. Build and run
 Author

T.M. Nethmi Nimesha — HNDIT Student
