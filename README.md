# Inkle Assignment — Frontend

A frontend assignment built using **React + Vite** as part of Inkle’s interview task. This project includes a dynamic table using **@tanstack/react-table**, an edit modal, API integration, and a country selector — with a clean, responsive, pixel-perfect UI.

## 🚀 Live Demo
🔗 **Project URL:**    
https://inkle-assignment-frontend-app.netlify.app/


## 🎥 Full Demo Video
[🎬 Click here to watch the full demo](https://raw.githubusercontent.com/Sandeepna2/inkle-assignment-frontend-app/main/inkle_recording.webm) 

## 🖼️ App Screenshots

### 🟣 Table View
<p>
  <img width="600" alt="Table View" src="sandbox:/mnt/data/Screenshot (19).png" />
  <br />
  <b>Screenshot:</b> Main table showing entity, gender, request date, and country.
</p>

### 🟣 Edit Customer Modal
<p>
  <img width="600" alt="Edit Modal" src="sandbox:/mnt/data/Screenshot (20).png" />
  <br />
  <b>Screenshot:</b> Edit modal with pre-filled user values (Name + Country).
</p>

### 🟣 Country Dropdown
<p>
  <img width="600" alt="Country Dropdown" src="sandbox:/mnt/data/Screenshot (21).png" />
  <br />
  <b>Screenshot:</b> Country dropdown showing dynamic country list from API.
</p>

### 🟣 Updated Table After Edit
<p>
  <img width="600" alt="Updated Table" src="sandbox:/mnt/data/Screenshot (22).png" />
  <br />
  <b>Screenshot:</b> Table updated after editing the customer's country.
</p>

### 🟣 Large Dataset View
<p>
  <img width="600" alt="More Data View" src="sandbox:/mnt/data/Screenshot (17).png" />
  <br />
  <b>Screenshot:</b> Table view with multiple customer entries.
</p>

### 🟣 Country Filter Panel
<p>
  <img width="600" alt="Country Filter" src="sandbox:/mnt/data/Screenshot (18).png" />
  <br />
  <b>Screenshot:</b> Country filter menu allowing multi-select filter options.
</p>


## 📌 Features
### ✔️ Fetch & Display Data
- Loads tax data from MockAPI  
- Built using **@tanstack/react-table** for a powerful table UI  

### ✔️ Edit Modal
- Edit **Name** and **Country**
- Country list fetched dynamically from API
- Modal shows existing row values

### ✔️ Update API (PUT Request)
- Merges updated fields with existing record  
- Sends PUT request to backend  
- Table updates instantly after save  

### ✔️ Pixel-Perfect UI
- Matches provided Figma design  
- Fully responsive  
- Clean animations & smooth modal UX  

## 🛠️ Tech Stack
- **React + Vite**
- **@tanstack/react-table**
- **Tailwind CSS**
- **Axios**
- **MockAPI**
- **React Hooks (useState, useEffect)**

## 📂 Folder Structure
<img width="265" height="322" alt="image" src="https://github.com/user-attachments/assets/e97e932e-4a0a-4f49-93ea-06027b38b034" />


## 🔗 API Endpoints
### ➤ Get all tax records
GET https://685013d7e7c42cfd17974a33.mockapi.io/taxes

### ➤ Get all countries
GET https://685013d7e7c42cfd17974a33.mockapi.io/countries

### ➤ Update a record
PUT https://685013d7e7c42cfd17974a33.mockapi.io/taxes/:id

### ✔️ Example Payload
{
  "name": "Ravi",
  "country": "India"
}

## 🧩 How Editing Works
- User clicks Edit on a row
- Modal opens with existing values
- Country list loads from API
- User edits data
- Clicking Save sends PUT request
- Table updates immediately

## 🚀 Installation & Setup
- git clone https://github.com/Sandeepna2/inkle-assignment-frontend-app.git
- cd inkle-assignment-frontend-app
- npm install
- npm run dev
