

# QuaddLabs 

## Welcome to QuaddFinance

QuaddFinance is an innovative project built for the tbDEX Hackathon. It focuses on financial inclusion by offering a simple and secure USSD-powered wallet solution, backed by tbDEX technology. This project consists of two core repositories: the **frontend web app** and the **backend USSD app**.

---

## Overview

### **Team Name:** QuaddLabs  
### **Project Name:** QuaddFinance

### **Repositories:**

- **Frontend Web App**  
  This repository houses the web-based user interface for QuaddFinance. The frontend app is designed to provide users with a seamless experience for managing their wallets, viewing transactions, and interacting with tbDEX features.

- **Backend USSD Service**  
  This repository contains the backend for the USSD wallet, which allows users to access and manage their wallets through simple USSD commands. This service makes financial services accessible to those without internet connectivity, fostering financial inclusion.

---

## Project Structure

### **1. Frontend Repository:**
**Repo URL:** [Link to QuaddFinance Frontend Repo]

#### **Technologies:**
- Nextjs
- Tailwind CSS
- Typescript
- tbDEX SDK integration(Pending ⚙)

#### **UI Features:**
- User registration and authentication
- Wallet management (create, fund, withdraw)
- Transaction history
- Responsive design for desktop(Done) mobile users(Pending)
- Easy-to-navigate UI/UX

#### **Installation & Setup:**
```bash
git clone https://github.com/QuaddBox/quaddfinance-frontend.git
cd quaddfinance-frontend
npm install
npm start
```

#### **Development Guide:**
- Ensure you have Node.js installed.
- Clone the repository and run the commands listed above to start development.
- Modify the configuration file to connect to the backend USSD service.

#### **Environment Variables:**
Create a `.env` file with the following:
```
REACT_APP_TBDEX_API_URL=<API_URL>
REACT_APP_BACKEND_URL=<BACKEND_URL>
```

---

### **2. Backend USSD Repository:**
**Repo URL:** [Link to QuaddFinance Backend Repo]

#### **Technologies:**
- Node.js
- Express.js
- MongoDB
- USSD Integration APIs (Africa's Talking)
- OnRender
- tbDEX SDK

#### **Features:**
- USSD wallet management
- Transaction processing(transfers/funding/receiving)
- Currency conversion via tbDEX


#### **Installation & Setup:**
```bash
git clone https://github.com/QuaddBox/quaddfinance-ussd.git
cd quaddfinance-ussd
npm install
npm start
```

#### **Development Guide:**
- Ensure Node.js and MongoDB are installed.
- Install the dependencies using `npm install`.
- Start the backend service using `npm start`.
- Integrate with USSD APIs by configuring environment variables.

#### **Environment Variables:**
Create a `.env` file with the following:
```
PORT=<Port_Number>
MONGODB_URI=<Your_MongoDB_URI>
TBDEX_API_KEY=<tbDEX_API_Key>
USSD_PROVIDER_API_KEY=<Your_USSD_Provider_API_Key>
```

---

## Contributing

We welcome contributions to improve QuaddFinance. Please fork the repositories and submit pull requests with detailed explanations of changes.

### **Steps for Contribution:**
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Submit a pull request.

---

## License

This project is licensed under the MIT License

---

## Contact

For any questions, feel free to reach out: anthonytwan75official@gmail.com

- **Team** [QuaddBox/QuaddLabs](https://github.com/QuaddBox)
- **Members:**

  <a href="https://github.com/Wutche">Wutche</a>

  <a href="https://github.com/Anthonyushie">Tony</a>

- **Hackathon:** tbDEX Hackathon 2024

---

### Acknowledgments

Special thanks to the tbDEX discord community for their valuable contributions to this project.

--- 


