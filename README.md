<img width="540" height="1200" alt="WhatsApp Image 2026-09-16 at 12 10 28" src="https://github.com/user-attachments/assets/5c4dc1d6-1606-4ae6-aa82-52b2e5c76b56" />
<img width="540" height="1200" alt="WhatsApp Image 2026-09-16 at 12 11 03" src="https://github.com/user-attachments/assets/c387ee2e-8bd1-45e8-b0ec-ab18b31ba324" />

<img width="540" height="1200" alt="WhatsApp Image 2026-09-16 at 12 10 25" src="https://github.com/user-attachments/assets/5c766eea-8c90-4428-8d88-6cdfe3bcb997" />
<img width="540" height="1200" alt="WhatsApp Image 2026-09-16 at 12 11 06" src="https://github.com/user-attachments/assets/b52105e2-a3d5-402e-91bf-7d2b71ba81b3" />


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
