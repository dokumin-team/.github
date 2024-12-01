# Dokumin

## Team Member

| No  | ID Student   | Name Student                                                   | Path               |
| :-: | :----------- | :------------------------------------------------------------- | :----------------- |
|  1  | A296B4KX0942 | [Cinta Ramayanti](https://github.com/cintarmynti)              | Mobile Development |
|  2  | C296B4KY3146 | [Mukhamad Aziz Firmansyah](https://github.com/mazizf13)        | Cloud Computing    |
|  3  | C296B4KY4051 | [Samda Zain Rozaan](https://github.com/samdazain)              | Cloud Computing    |
|  4  | M296B4KY4250 | [Syahrial Rizky](https://github.com/SyahrialZky)               | Machine Learning   |
|  5  | M296B4KY1657 | [Habib Nurrohmad Sugiharto](https://github.com/habibNurrohmad) | Machine Learning   |
|  6  | M296B4KY0478 | [Ananda Putra Wahyu Riyanto](https://github.com/Ndaputtra)     | Machine Learning   |

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

---

## Introduction

**Dokumin** is a document management application designed to make organizing your documents effortless. With OCR (Optical Character Recognition) technology powered by Tesseract, Dokumin allows users to scan physical documents into text, categorize them using Machine Learning, and store them securely in designated folders. Users can also upload, rename, and manage their documents and folders manually.

---

## Features

### Navigation:

-   **Home**: Quick access to recent documents and as well as the number of folders and number of documents.
-   **List Documents**: View, upload, rename, or delete documents.
-   **Camera**: Scans physical documents and processes them using OCR. And suggests which folder this document should go into.
-   **List Folders**: Create, rename, or delete folders.
-   **Settings**: Manage dark mode, logout, and reset password options.

### Core Features:

1. **Document Categorization**: Automatically categorize scanned text into predefined types:
    - Personal Data
    - General Notes
2. **OCR Scanning**: Extract text from images using Tesseract.
3. **File Management**:
    - Upload files without scanning.
    - Rename and delete files.
4. **Folder Management**:
    - Create, rename, and delete folders.
5. **User Preferences**:
    - Dark mode toggle.
    - Logout and forgot password functionalities.

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

-   Tensorflow
-   Keras

---

## Usage

1. Open the app and log in with your credentials.
2. Navigate to the **Camera** tab to scan documents.
3. Review the OCR output and accept the suggested category or reassign manually.
4. Manage your documents in the **List Documents** tab:
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
