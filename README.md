# 📄 Resume Builder - AlmaBetter Capstone Project

A modern and responsive web application that helps users easily create professional resumes using customizable templates.

---

## 🚀 Features

- Select from multiple resume templates
- Fill in details including Bio, Address, Education, Experience, Projects, and Key Skills
- Upload profile picture directly into the resume
- Live preview before downloading
- Save, edit, and delete resumes locally
- Responsive navigation and user experience

---

## 🛠️ Tech Stack

- **Frontend:** React, React Router DOM, Material UI, Vanilla JS, JSX
- **State Management:** Redux Toolkit
- **Form Handling:** React Hook Form
- **PDF Export:** jsPDF
- **Image Handling:** react-avatar-edit
- **Styling:** CSS Modules

---

## 🌐 Live Demo

🔗 [Click Here to Visit the App](https://resume-builder-attempt-2.vercel.app/)

---

## 📁 Folder Structure

|-- src
| |-- assets
| |-- components
| | |-- AppNavBar
| | | |-- Navbar.jsx
| | | |-- NavbarDesktop.jsx
| | | |-- NavbarMobile.jsx
| | | |-- NavbarMobileDrawer.jsx
| | |-- input
| | | |-- Address.jsx
| | | |-- Bio.jsx
| | | |-- Education.jsx
| | | |-- Experience.jsx
| | | |-- KeySkills.jsx
| | | |-- Projects.jsx
| | | |-- UploadImage.jsx
| | |-- preview
| | | |-- Address.jsx
| | | |-- Bio.jsx
| | | |-- Education.jsx
| | | |-- Experience.jsx
| | | |-- KeySkills.jsx
| | | |-- Projects.jsx
| | | |-- ViewPreview.jsx
| | |-- FillDetailButton.jsx
| | |-- FillDetailSideBar.jsx
| | |-- Footer.jsx
| | |-- SuccessSnackbar.jsx
| |-- data
| | |-- aboutData.js
| | |-- details.js
| | |-- social.js
| | |-- templates.js
| |-- pages
| | |-- About.jsx
| | |-- FillDetails.jsx
| | |-- Home.jsx
| | |-- MyResume.jsx
| |-- redux
| | |-- slices
| | | |-- addressSlice.js
| | | |-- bioSlice.js
| | | |-- educationSlice.js
| | | |-- experienceSlice.js
| | | |-- keySkillsSlice.js
| | | |-- projectsSlice.js
| | | |-- sliceDynamicStyle.js
| | | |-- sliceFillDetails.js
| | |-- store.js
| |-- styles
| | |-- footer.module.css
| | |-- home.module.css
| | |-- input.module.css
| | |-- navbar.module.css
| |-- utils
| | |-- colors.js
| | |-- controls.js
| |-- App.jsx
| |-- main.jsx
|-- index.css
|-- index.html
|-- package.json
|-- package-lock.json


---

## 📷 Page Previews

### 🏠 Home Page
Choose a resume template and start building.

![Home Page](https://user-images.githubusercontent.com/100461901/219924028-fb00b130-a794-4c2f-aa43-91feaab95441.png)

### ✍️ Fill Details Page
Enter all necessary information with a user-friendly form layout.

![Details Filling](https://user-images.githubusercontent.com/100461901/219924410-c768a081-9ac8-4cf8-83ed-8b6cc00d0d1f.png)

### 📂 My Resumes
Access and manage saved resumes.

![My Resumes](https://user-images.githubusercontent.com/100461901/219924722-595fdb82-6037-42b2-8639-44541213b01f.png)

### ℹ️ About Page
Information about the app and its purpose.

![About Us](https://user-images.githubusercontent.com/100461901/219925057-16f85fe1-6aa1-416f-9d88-6040e04faae0.png)

---

## 🧩 Installation & Running Locally

```bash
# Clone the repository
git clone https://github.com/your-username/resume-builder.git

# Navigate to the project directory
cd resume-builder

# Install dependencies
npm install

# Start the application
npm run dev
🙌 Contribution Guidelines

Contributions are welcome! Please fork the repository and submit a pull request for any feature suggestions, improvements, or bug fixes.

📬 Contact

For questions or feedback, feel free to open an issue or reach out on GitHub.

© 2025 Resume Builder. All rights reserved.

