# 📄 Resume Builder - AlmaBetter Capstone Project

A modern and responsive web application that helps users effortlessly create professional resumes using customizable templates.

---

## 🚀 Features

- Choose from multiple pre-built resume templates
- Fill in personal information: Bio, Address, Education, Experience, Projects, Key Skills
- Upload a profile picture directly into your resume
- Live preview before downloading
- Download resumes as PDFs
- Save, edit, and delete resumes using local storage
- Fully responsive UI for mobile and desktop

---

## 🛠️ Tech Stack

- **Frontend**: React, React Router DOM, JSX
- **State Management**: Redux Toolkit
- **Styling**: Material UI, CSS Modules
- **Form Handling**: React Hook Form
- **PDF Export**: jsPDF
- **Image Upload**: react-avatar-edit

---

## 🌐 Live Demo

🔗 [Click Here to Try the App](https://resume-builder-attempt-2.vercel.app/)

---

## 📷 Screenshots

### 🏠 Home Page  
Choose a resume template.

![Home Page](https://user-images.githubusercontent.com/100461901/219924028-fb00b130-a794-4c2f-aa43-91feaab95441.png)

### 📝 Fill Details Page  
Enter your resume data step-by-step.

![Fill Details](https://user-images.githubusercontent.com/100461901/219924410-c768a081-9ac8-4cf8-83ed-8b6cc00d0d1f.png)

### 📂 My Resumes  
Manage your saved resumes.

![My Resumes](https://user-images.githubusercontent.com/100461901/219924722-595fdb82-6037-42b2-8639-44541213b01f.png)

### ℹ️ About Page  
Get to know about the app.

![About Page](https://user-images.githubusercontent.com/100461901/219925057-16f85fe1-6aa1-416f-9d88-6040e04faae0.png)

---

## 📁 Folder Structure

<pre>
|-- src
    |-- assets 
    |-- components
        |-- AppNavBar 
            |-- Navbar.jsx 
            |-- NavbarDesktop.jsx 
            |-- NavbarMobile.jsx 
            |-- NavbarMobileDrawer.jsx
        |-- input
            |-- Address.jsx
            |-- Bio.jsx
            |-- Education.jsx
            |-- Experience.jsx 
            |-- KeySkills.jsx
            |-- Projects.jsx
            |-- UploadImage.jsx
        |-- preview
            |-- Address.jsx
            |-- Bio.jsx
            |-- Education.jsx
            |-- Experience.jsx 
            |-- KeySkills.jsx
            |-- Projects.jsx
            |-- ViewPreview.jsx
        |-- FillDetailButton.jsx
        |-- FillDetailSideBar.jsx
        |-- Footer.jsx
        |-- SuccessSnackbar.jsx
    |-- data
        |-- aboutData.js
        |-- details.js 
        |-- social.js
        |-- templates.js 
    |-- pages
        |-- About.jsx 
        |-- FillDetails.jsx 
        |-- Home.jsx 
        |-- MyResume.jsx 
    |-- redux
        |-- slices
            |-- addressSlice.js
            |-- bioSlice.js 
            |-- educationSlice.js 
            |-- experienceSlice.js 
            |-- keySkillsSlice.js 
            |-- projectsSlice.js 
            |-- sliceDynamicStyle.js 
            |-- sliceFillDetails.js 
        |-- store.js  
    |-- styles
        |-- footer.module.css 
        |-- home.module.css 
        |-- input.module.css 
        |-- navbar.module.css 
    |-- utils 
        |-- colors.js 
        |-- controls.js 
    |-- App.jsx 
    |-- main.jsx 
|-- index.css 
|-- index.html
|-- package.json
|-- package-lock.json
</pre>

---

## 🧪 Getting Started

To run the app locally:

```bash
# Clone the repository
git clone https://github.com/your-username/resume-builder.git

# Navigate to the project directory
cd resume-builder

# Install dependencies
npm install

# Start the app
npm run dev
