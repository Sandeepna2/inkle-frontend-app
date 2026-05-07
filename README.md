# Inkle Assignment — Frontend

A frontend assignment built using **React + Vite** as part of Inkle’s interview task. This project includes a dynamic table using **@tanstack/react-table**, an edit modal, API integration, and a country selector — with a clean, responsive, pixel-perfect UI.

## 🚀 Live Demo
🔗 **Project URL:**    
https://inkle-app.netlify.app/

 
## 🎥 Full Demo Video
[🎬 Click here to watch the full demo](https://raw.githubusercontent.com/Sandeepna2/inkle-assignment-frontend-app/main/inkle_recording.webm) 


## 🖼️ App Screenshots 
<table>
  <tr>
    <td>
      <h3>🟣 Table View</h3>
       <img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/55096eee-759b-4819-9086-794b1bd59613" />
    </td>
    <td>
      <h3>🟣 Edit Modal</h3>
      <img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/e1738b53-b032-45c3-9211-9306962098ea" />  
    </td>
  </tr>

  <tr>
    <td>
      <h3>🟣 Country Dropdown</h3>
      <img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/ed15b393-eca0-4ca7-8493-79e719d5b405" />
    </td>
    <td>
      <h3>🟣 Updated Table After Edit</h3>
      <img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/69460721-d1e3-449a-8efe-2ed3e0e057a1" />
    </td>
  </tr>

  <tr>
    <td>
      <h3>🟣 Full Data Table View</h3>
      <img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/abddb621-4896-422a-9d03-a9134412cbb9" />
    </td>
    <td>
      <h3>🟣 Country Filter</h3>
      <img width="600" height="350" alt="image" src="https://github.com/user-attachments/assets/45ba2b77-d765-41c7-bb4f-59c7e57438ac" />
    </td>
  </tr>
</table>


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
- Clicking Save sends Put request
- Table updates immediately

## 🚀 Installation & Setup
- git clone https://github.com/Sandeepna2/inkle-assignment-frontend-app.git
- cd inkle-assignment-frontend-app
- npm install
- npm run dev
