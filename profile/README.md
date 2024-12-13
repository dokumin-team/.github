# Dokumin

![Dokumin](https://github.com/user-attachments/assets/11e18673-0fbc-44d5-ab03-d6febbb9c674)

<p align="center">
   Download Here!
   <br>
   <a href="https://drive.google.com/file/d/1G-HJILprPYllUxksOYM4xuwG6puZJGXy/view?usp=drive_link" download>
      <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
   </a>
</p>

---

## Table of Contents

1. [Introduction](#introduction)
2. [Team Member](#team-member)
3. [Features](#features)
4. [Tech Stack](#tech-stack)
5. [Repository](#repository)
6. [Cloud Architecture](#cloud-architecture)
7. [Machine Learning Architecture](#machine-learning-architecture)
8. [API Documentation](#api-documentation)
9. [Usage](#usage)
10. [Contributing](#contributing)
11. [License](#license)

---

## Introduction

**Dokumin** is a document management application designed to make organizing your documents effortless. With OCR (Optical Character Recognition) technology powered by Tesseract, Dokumin allows users to scan physical documents into text, categorize them using Machine Learning, and store them securely in designated folders. Users can also upload, rename, and manage their documents and folders manually.

---

## Team Member

| No  | ID Student   | Name Student                                                   | Path               | Status             | LinkedIn                                                                      | Github                                                                      |
| :-: | :----------- | :------------------------------------------------------------- | :----------------- | :----------------- | :-----------------                                                            | :-----------------                                                            |
|  1  | A296B4KX0942 | Cinta Ramayanti              | Mobile Development | Active             | [LinkedIn](https://id.linkedin.com/in/cinta-ramayanti)                        | [Github](https://github.com/cintarmynti)                        |
|  2  | C296B4KY3146 | Mukhamad Aziz Firmansyah        | Cloud Computing    | Active             | [LinkedIn](https://id.linkedin.com/in/mazizf13/)                              | [Github](https://github.com/mazizf13)                        |
|  3  | C296B4KY4051 | Samda Zain Rozaan              | Cloud Computing    | Active             | [LinkedIn](https://id.linkedin.com/in/samdazain)                              | [Github](https://github.com/samdazain)                        |
|  4  | M296B4KY1657 | Habib Nurrohmad Sugiharto | Machine Learning   | Active             | [LinkedIn](https://id.linkedin.com/in/habib-nurrohmad-sugiharto)              | [Github](https://github.com/habibNurrohmad)                        |
|  5  | M296B4KY0478 | Ananda Putra Wahyu Riyanto     | Machine Learning   | Active             | [LinkedIn](https://id.linkedin.com/in/ananda-putra-wahyu-riyanto-a3a829259)    | [Github](https://github.com/Ndaputtra)                        |
|  6  | M296B4KY4250 | Syahrial Rizky               | Machine Learning   | Active             | [LinkedIn](https://id.linkedin.com/in/syahrial-rizky-b895a1219)                | [Github](https://github.com/SyahrialZky)                        |

---

## Features

### Navigation:

-   **Home**: Quick access to recent documents and as well as the number of folders and number of documents.
-   **List Documents**: View, upload, rename, or delete documents.
-   **Camera**: Scans physical documents and processes them using OCR. And suggests which folder this document should go into.
-   **List Folders**: Create, rename, or delete folders.
-   **Settings**: About Dokumin, FAQ, contact, and logout.

### Core Features:

1. **Document Categorization**: Automatically categorize scanned text into predefined types:
    - Personal Data
    - General Notes
2. **OCR Scanning**: Extract text and copy.
3. **File Management**:
    - Upload files without scanning.
    - Rename and delete files.
4. **Folder Management**:
    - Create, rename, and delete folders.
5. **User Preferences**:
    - About
    - FAQ
    - Contact
    - Logout

---

## Tech Stack

### Application Architecture:

-   **App Deployment**: Google App Engine
-   **Backend Deployment**: Google Cloud Run
-   **Database**: Firestore
-   **Machine Learning**: Hosted on Google Cloud Storage

### Mobile Development:

-   Kotlin
-   Figma
-   Android Studio

### Backend:

-   REST API with Node.js and Express

### Machine Learning:

- Object Detection with tensorflow
- Object Classification with tensorflow
- Image processing with tensorflow and text recognition

---

## Repository
Here are the repositories associated with our project:
### Cloud Computing
- [Dokumin Backend](https://github.com/dokumin-team/dokumin-api)
-  [Dokumin Backend Flask](https://github.com/dokumin-team/dokumin-flask-api)

### Machine Learning
- [Machine Learning](https://github.com/dokumin-team/dokumin-machine-learning)
   
### Mobile Development
- [Dokumin Mobile App](https://github.com/dokumin-team/dokumin-mobile-dev)

---

## Cloud Architecture
![architecture-cloud](https://github.com/user-attachments/assets/2167e616-d921-47a6-b6ce-dc4d0fd62ef7)

---

## Machine Learning Architecture
![ml-architecture](https://github.com/user-attachments/assets/0d7ef974-4feb-4e06-b3c4-4be4d014a711)

---

## API Documentation
This is our [Api-documentation](https://documenter.getpostman.com/view/37337961/2sAYHxnPG3)

---
## Usage

1. Open the app and log in with your credentials.
2. Navigate to the **Camera** tab to scan documents.
3. Scanned documents will be automatically sorted:
    - **Private Folder**: KTP, KK, SIM
    - **Other Folder**: All other documents
4. Manage your documents in the **Folder** tab:
    - Create new folder
    - Upload new files.
    - Rename or delete existing documents.
5. Create and organize folders in the **List Folders** tab.
6. Adjust app settings in the **Settings** tab.

---

## Contributing

We welcome contributions from the community! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

---

## License

Dokumin is open-source software licensed under the MIT License. See the `LICENSE` file for details.
