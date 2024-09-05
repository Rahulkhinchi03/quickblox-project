# Quickblox Chatbot in React with Vite

This repository contains the source code for a simple chatbot built using [Quickblox](https://quickblox.com/) in a React application with Vite. The project demonstrates how to integrate Quickblox's real-time communication platform and its React UI Kit to create a functional chatbot application.

## 🚀 Getting Started

Follow these instructions to set up the project locally and get it running on your machine.

### Prerequisites

Make sure you have the following installed on your system:

- **Node.js** (v14 or above)
- **npm** (v6 or above)

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/quickblox-chatbot.git
   cd quickblox-chatbot
2. **Install dependencies**:
   ```bash
   npm install
3. **Set up Quickblox configuration**:
   Create a new file named qbConfig.js in the src directory and add your Quickblox credentials:
   ```bash
   const QBConfig = {
   appId: 'YOUR_APP_ID',
   authKey: 'YOUR_AUTH_KEY',
   authSecret: 'YOUR_AUTH_SECRET',
   accountKey: 'YOUR_ACCOUNT_KEY',
   };

   export default QBConfig;

  Replace 'YOUR_APP_ID', 'YOUR_AUTH_KEY', 'YOUR_AUTH_SECRET', and 'YOUR_ACCOUNT_KEY' with your actual Quickblox credentials.

4. Running the Project
   To run the project locally:
   ```bash
   npm run dev

This command will start the development server. Open your browser and navigate to http://localhost:3000 to see the chatbot in action!

### 🛠️ Features

- Quick Setup: Uses Vite for fast and easy project setup.
- Real-Time Communication: Powered by Quickblox for seamless chat functionality.
- React UI Kit: Incorporates Quickblox's React UI Kit for pre-built chat components.

### 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you have any questions or suggestions.

- Fork the repository.
- Create a new branch (git checkout -b feature/new-feature).
- Commit your changes (git commit -m 'Add a new feature').
- Push to the branch (git push origin feature/new-feature).
- Open a pull request.

### 📚 Resources
- [Quickblox Documentation](https://docs.quickblox.com/)
- [Quickblox React UI Kit](https://docs.quickblox.com/docs/react-uikit-overview)
- [Quickblox Code Samples](https://docs.quickblox.com/docs/code-samples)

### 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

### 🙌 Acknowledgments
Big thanks to [Quickblox](https://quickblox.com/) for providing a great platform for real-time communication and making this project possible!
