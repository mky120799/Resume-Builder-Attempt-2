# Resume-Builder (AlmaBetter Capstone Project)


## Introduction
* Resume builder is a web application where anyone can create a resume with ease and choose from different available templates.
* It has three tabs: 1) Resume Templates (Home Page), 2)Resumes (Saved Resumes) 3) About us 
* Set profile picture in the resume.
* Before downloading we have a preview option to view your resume.
* You can save resumes to the local hard drive.
* Saved resumes can be deleted as well as modified by the user.

## Used in this project:
* React-Router-Dom
* Material UI
* React-Redux
* Store
* React-Avatar-edit
* Vanilla JS
* JSX
* Uniq ID
* React-Hook-Forms
* Jspdf converter
* Redux connect method
* Images
* Raw data

## Pages
* Home (Resume Templates) <br/> -Choose one from the available templates &amp; <br/> -Navigated to details filling page 
* My Resumes
* About us

## Demo about the pages:
-  *Home Page*
<img width="1120" alt="image" src="https://user-images.githubusercontent.com/100461901/219924028-fb00b130-a794-4c2f-aa43-91feaab95441.png">

- *Details Filling page*
<img width="1117" alt="image" src="https://user-images.githubusercontent.com/100461901/219924410-c768a081-9ac8-4cf8-83ed-8b6cc00d0d1f.png">

- *My Resumes*
<img width="1120" alt="image" src="https://user-images.githubusercontent.com/100461901/219924722-595fdb82-6037-42b2-8639-44541213b01f.png">

- *About us*
<img width="1119" alt="image" src="https://user-images.githubusercontent.com/100461901/219925057-16f85fe1-6aa1-416f-9d88-6040e04faae0.png">

*__Live Link__* <br/>
<b>Click [Here](https://resume-builder-56.netlify.app/)</b>

</hr>

Resume-Builder/
├── public/
│   ├── apple-icon.png
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
│
└── src/
    ├── App.js
    ├── index.css
    ├── index.js
    ├── Store.js
    │
    ├── Components/
    │   ├── CheckSelectedId.js
    │   ├── BackNextBtn/
    │   │   ├── BackNextBtnComponent.js
    │   │   └── BackNextBtnComponent.css
    │   ├── BlackScreen/
    │   │   ├── BlackScreen.js
    │   │   └── BlackScreen.css
    │   ├── DetailFillingSidebar/
    │   │   ├── DetailFillingSidebar.js
    │   │   └── DetailsFillingSideBar.css
    │   ├── Education/
    │   │   ├── EducationComponent.js
    │   │   └── EducationComponent.css
    │   ├── Header/
    │   │   ├── TemplateHeader.js
    │   │   └── TemplateHeader.css
    │   ├── Heading/
    │   │   ├── TemplateHeading.js
    │   │   └── TemplateHeading.css
    │   ├── Input/
    │   │   ├── InputComponent.js
    │   │   └── InputComponent.css
    │   ├── KeySkills/
    │   │   ├── KeySkillsComponent.js
    │   │   └── KeySkillsComponent.css
    │   ├── MainBar/
    │   │   ├── Navbar.js
    │   │   └── Navbar.css
    │   ├── PersonalInfo/
    │   │   ├── PersonalInfoComponent.js
    │   │   └── PersonalInfoComponent.css
    │   ├── Preview/
    │   │   ├── PreviewComponent.js
    │   │   └── PreviewComponent.css
    │   ├── Select/
    │   │   ├── SelectComponent.js
    │   │   └── SelectComponent.css
    │   ├── TemplateEducation/
    │   │   ├── TemplateEducationComponent.js
    │   │   └── TemplateEducationComponent.css
    │   ├── TemplateKeySkill/
    │   │   ├── TemplateKeySkillComponent.js
    │   │   └── TemplateKeySkillComponent.css
    │   ├── TemplateOneExperience/
    │   │   ├── TemplateOneExperienceComponent.js
    │   │   └── TemplateOneExperienceComponent.css
    │   └── WorkExperience/
    │       ├── WorkExperienceComponent.js
    │       └── WorkExperienceComponent.css
    │
    ├── Pages/
    │   ├── AboutUs.js
    │   ├── DetailsFilling.js
    │   ├── Home.js
    │   ├── MyResumes.js
    │   ├── index.js
    │   └── Styles/
    │       ├── DetailsFilling.css
    │       ├── Home.css
    │       └── MyResumes.css
    │
    ├── Redux/
    │   ├── Actions/
    │   │   └── actions.js
    │   └── Reducers/
    │       ├── combinedReducers.js
    │       └── reducers.js
    │
    └── Utils/
        ├── inputChecks.js
        ├── Data/
        │   ├── data.js
        │   └── templates.js
        ├── Images/
        │   ├── aboutCV.jpg
        │   ├── sample_1.jpg
        │   ├── sample_2.jpg
        │   ├── sample_3.jpg
        │   └── sample_4.jpg
        └── Templates/
            ├── Template.css
            ├── Template1.js
            ├── Template2.js
            ├── Template3.js
            ├── Template4.js
            ├── Template5.js
            └── Template6.js