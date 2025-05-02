# 📁 File Metadata Microservice

This project is part of the [freeCodeCamp Back End Development and APIs Certification](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/file-metadata-microservice).

## 📌 Overview

The File Metadata Microservice allows users to upload a file and receive metadata about it, including its original name, MIME type, and file size. It's a simple API that demonstrates handling file uploads using Node.js and Express.

## 🔍 Features

- Accepts file uploads via a form or API request.
- Returns metadata of the uploaded file:
  - Original filename
  - File MIME type
  - File size in bytes

## 📡 API Endpoint

### POST /api/fileanalyse

Submit a file to receive metadata.

**Form field name**: `upfile`

**Response:**
{
  "name": "example.png",
  "type": "image/png",
  "size": 12345
}

## ⚙️ Technologies Used

- Node.js
- Express.js
- Multer (for handling multipart/form-data)
- dotenv (for environment variables)
- CORS middleware

## 🛠️ Getting Started Locally

1. **Clone the repository**:
```bash
git clone https://github.com/giannis07/fcc_file_metadata_microservice.git
cd fcc_file_metadata_microservice
```

2. **Install dependencies**:
```bash
npm install
```

3. **Start the server**:
```bash
npm start
```

The server will be running on `http://localhost:3000`

## 📁 File Uploads

Uploaded files are temporarily stored in the directory:  
`/public/data/uploads/`


## 💻 Source Code

🔗 https://github.com/giannis07/fcc_file_metadata_microservice

