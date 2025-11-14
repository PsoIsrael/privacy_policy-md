# Privacy Policy

Last updated: 12.11.2025

## 1. Who we are

This Privacy Policy describes how the mobile application “АН МКО Израиль” (the “App”) operated by Alexander Tian (“we”, “us”, “our”) handles information when you use the App.

We are committed to minimizing data collection and using only the data that is necessary for the App to work.

## 2. Scope of this Policy

This Policy applies only to the App and the backend services that directly support it, such as our Firebase project and public API integrations.

It does not apply to third-party applications or services that you may open from the App (for example WhatsApp, Telegram, Waze, Google Maps, email apps), or to external websites that are opened in your browser. Those services are governed by their own privacy policies.

## 3. Short description of the App

The App provides:

a) A public platform where users can submit posts with images or PDF files. Submitted posts go to an admin panel, and an admin can approve or reject them. If approved, the post becomes visible to all users of the App.

b) A personal “Chistota” section on the device, where the user can store personal notes and files (txt, docx, pdf, jpeg, png, jpg). These items are stored locally in an SQLite database on the device and are not visible to other users.

c) The ability to copy text from external content (received from public APIs inside the App) and share this text to other apps such as WhatsApp, Telegram, email clients and others.

d) Integration with Google Maps and Waze to show locations and open navigation.

---

## 4. Data we do not intentionally collect

Our application is designed with maximum privacy in mind. We do not collect, share, or store any Personal Identifiable Information (PII) of end users, such as name, email address, location, or contacts. All user data created or modified in the personal "Chistota" section (Cabinet) is stored exclusively locally on the user's device (in an SQLite database) and is not transferred to external servers. We also do not use third-party tools for collecting analytics or advertising data.

According to our current implementation and Data Safety declaration in Google Play Console, the App does not intentionally collect or share the following types of personal data:

- Real-world personal identifiers such as your real email address, name, home address, phone number, national ID, or similar.  
- Commercial data such as payment information or purchase history.  
- Sensitive categories such as health, political, religious, racial, or similar information for profiling.  
- Advertising IDs for targeted advertising.  
- Analytics data via third-party analytics SDKs.  

We designed the App so that standard usage does not require the user to provide personal contact details, and we do not use the App for advertising or marketing profiling.

However, please note that when you choose to upload content (for example images or PDFs), that content may contain personal information if you include it yourself. In that case, such content is treated as “User-generated content” as described below.

---

## 5. Data you choose to provide

### 5.1 Public posts (platform content)

**Functionality**

- You can submit posts with text, images and PDF files to the platform.  
- When you submit a post, it is sent to our backend (Firebase) and appears in the admin panel.  
- An admin can review and approve or reject posts.  
- When a post is approved, it becomes public: any user of the App can view it.

**What is stored and where**

- Content of the post (text), and file attachments (images, PDFs) are stored in Firebase services (for example Firestore and Firebase Storage).  
- Posts may be linked to an internal technical user identifier in Firebase so that the App can manage posts correctly.  
- We do not require you to provide your real name or email address together with a post.

**How we use this data**

- To display your post in the App.  
- To allow admins to moderate content (approve or reject posts).  
- To keep the public feed of posts up to date.

**What you should understand**

- Any information you include in a public post, including any personal data inside images or PDFs, becomes visible to all users of the App once approved by the admin.  
- You are responsible for the content you upload. Please avoid uploading sensitive personal information about yourself or others.

### 5.2 Personal Cabinet (“Chistota” screen)

**Functionality**

- Each user has a personal Cabinet section in the App.  
- Here you can store your own notes and files (txt, docx, pdf, jpeg, png, jpg).  
- You can also generate a text file with your answers to questions and save it locally on your device, and optionally share it via other apps such as WhatsApp.

**What is stored and where**

- All data in the Cabinet is stored locally on your device in an SQLite database and, where applicable, as local files.  
- This data is not uploaded to our servers and is not visible to other users or admins.  
- We do not have direct access to your personal Cabinet data.

**How we use this data**

- The data is processed only on your device in order to show you your notes and files.  
- When you choose to share a text file or content from the Cabinet through another app (such as WhatsApp), the data is handed over directly by your device’s operating system to that external app. We do not receive a copy.

**What you should understand**

- If you uninstall the App or clear its data, your Cabinet data stored locally may be deleted.  
- We recommend that you make your own backups if this information is important to you.

### 5.3 Text sharing to other apps

The App allows you to:

- Copy text that comes from external public APIs shown inside the App.  
- Paste and share this text into other apps such as WhatsApp, Telegram, email and others.

This is done entirely via your device’s operating system share and clipboard mechanisms. We do not intercept or store the messages that you send in other apps.

### 5.4 Authentication and internal identifiers

**Special Note on Authentication**

- The App uses Google Firebase Authentication with technical emails and passwords that are created by the service administrator exclusively for the purpose of app administration and security, and not for the registration or login of end users.  
- Administrative account credentials are internal technical identifiers and are not linked to the personal information of end users. We do not collect or store the real email addresses or passwords of end users.

**Additional information**

- Firebase Authentication may create a unique user identifier (UID) for each admin-user account.  
- We do not use this identifier for tracking across other apps or services, and we do not sell this information.

We do not use your data for advertising or marketing targeting and we do not sell your personal information.

We use the data described above only for the following purposes:

- To operate and provide the App’s features, including the public posts platform.  
- To moderate public content through the admin panel.  
- To maintain the security and stability of our backend infrastructure.

### 5.5 Access to Files and Media

To ensure the core functionality of information sharing (uploading and publishing open images and PDF documents), the App requests access to device storage.

This access is utilized only with the user's explicit consent for the purpose of uploading the selected file for public posting. The App does not scan or collect data from your storage for any other purposes.

**Clarification on Storage**

The files selected by the user for public posting (as described in Section 5.1) are intentionally transferred to our Firebase backend for public display. We do not store or backup the files you keep locally on your device in the "Chistota" section (Section 5.2). Files uploaded to the public platform are retained only for the duration that the post remains active.

---

6.      How we use information
We do not use your data for advertising or marketing
targeting and we do not sell your personal information.
We use the data described above only for the following
purposes:
– To operate and provide the App’s features, including the
public posts platform.
– To moderate public content through the admin panel.
– To maintain the security and stability of our backend infrastructure.
– **To diagnose and fix technical errors and maintain reliable performance.**

***

**Limited Diagnostic Data and Technical Metadata**

We collect limited diagnostic information, including **Crash logs and technical metadata** (such as device type and operating system version) that is automatically generated by the service (e.g., Firebase) when an error occurs. This information is used **exclusively for maintaining the security, stability, and reliable performance** of the App. This data is not linked to any user PII and is not used for analytics or profiling.

---

## 7. Data sharing and disclosure

We do not sell your personal information. We do not share data with third parties for advertising purposes.

We may share or allow access to data in the following limited situations:

**Service providers**  
We use Google Firebase and related Google Cloud services to host data and provide authentication and storage. These providers may technically process data on our behalf as part of providing their services.

**Legal compliance and protection**  
We may access, preserve or disclose information if we believe it is reasonably necessary to:

- comply with any applicable law or legal process,  
- enforce our terms of use, or  
- protect the rights, property, or safety of our users or others.

**Public content**  
When an admin approves a post, that post (including attached images and PDFs) is intentionally shared with all users of the App as public content. This is the core function of the platform.

---

## 8. Third-party services

The App integrates with and may open other applications or websites, including but not limited to:

- Google Firebase services (Authentication, Firestore/Realtime Database, Storage)  
- External public APIs that provide text content displayed in the App  
- Google Maps  
- Waze  
- WhatsApp  
- Telegram  
- Email applications and web browsers installed on your device  

Your use of these third-party services is governed by their own terms and privacy policies. We do not control how these services handle your data. We recommend that you review their privacy policies before using them.

---

## 9. Data retention

Public posts and their media files stored in Firebase may be retained for as long as they are needed for the operation of the platform, unless they are removed by an admin or we are required by law to remove them sooner.

Cabinet data is stored only on your device and is retained for as long as you keep it there. If you uninstall the App or clear its data, that data may be deleted.

Technical logs in Firebase and other backend services are retained according to the retention rules of those services and are not kept longer than necessary for security, debugging and legal compliance.

---

## 10. Data security

We take reasonable technical and organizational measures to protect the data that is stored on our backend (for example access control to Firebase and admin tools).

However, no method of transmission or storage is completely secure, and we cannot guarantee absolute security. You are also responsible for protecting access to your device and to any local files or messages that you generate or share from the App.

---

## 11. Children

The App is not designed to collect personal contact details from children, and we do not intentionally collect personal data from children beyond what is necessary for the App to function.

If you are a parent or guardian and believe that a child has provided personal information to us by mistake, please contact us and we will review the situation.

---

## 12. Your rights and choices

Depending on your location, you may have rights regarding your personal data, such as the rights to access, correct, or delete data, or object to certain processing.

If you want to exercise your rights or ask questions about this Policy, you can contact us using the contact details below. Since most of the Cabinet data is stored only on your device, in many cases you can manage or erase this data directly on your device by deleting or editing items, or by uninstalling the App.

---

## 13. Contact us

If you have any questions about this Privacy Policy or our data practices, you can contact us at:

Email: prruslangdistisrael2025@gmail.com
