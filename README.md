# AI Email Reply Generator Extension

This is an AI-powered email extension that automatically generates replies based on the received email content. The extension can be integrated into a user's email account and conveniently appears to the left of the "Send" button.

## Features
- **AI-Powered Replies**: Automatically generate email replies based on the context of the received email.
- **Easy Integration**: Seamlessly integrates into the user's email interface.
- **User-Friendly Design**: Accessible right next to the "Send" button for effortless use.

---

## Built With
- **Backend**: Spring Boot
- **Frontend**: ReactJS, JavaScript
- **AI API**: Gemini API

---

## Prerequisites
- Java Development Kit (JDK)
- Node.js and npm (for frontend)
- A valid Gemini API key and URL
- Google Chrome browser for installing the extension

---

## How to Run

### 1. Clone the Project
```bash
git clone <[repository-url](https://github.com/Sumit-hubgit/Email.git)>
cd Email
```

### 2. Start the Backend Server
Navigate to the `email-writer-sb` folder inside the `Email` project folder:
```bash
cd email-writer-sb
```

Replace the Gemini API key and URL with your own credentials in the backend code.

Start the backend server:
```bash
./mvnw spring-boot:run
```

### 3. Set Up the Chrome Extension
1. Open Chrome and navigate to `chrome://extensions/`.
2. Enable **Developer mode** in the top-right corner.
3. Click on **Load unpacked** and select the `email-writer-extension` folder inside the `Email` project folder.
4. Pin the extension to your toolbar for easy access.

---

## Usage
1. Open your email client in Chrome.
2. Compose a reply to an email.
3. Use the extension to generate a reply with AI assistance before sending the email.

---

## Folder Structure
```
Email/
│
├── email-writer-sb/                # Backend folder
│   └── src/                 # Backend source code
│
├── email-writer-extension/  # Chrome extension folder
│   └── src/                 # Frontend source code for extension
```

---

## Notes
- Ensure that the Gemini API key and URL are correctly configured in the backend before starting the server.
- The backend server must be running for the extension to function properly.

---



## Contact
For any questions or issues, please feel free to contact the developer:
- **Email**: sumitsahu7017@gmail.com
- **LinkedIn**: [linkedin.com/in/sumit-sahu-b53178225/]([https://linkedin.com/in/sumit](https://www.linkedin.com/in/sumit-sahu-b53178225/))

---

### Happy Emailing! 🚀
