# AI Chatbot for University Registration Using IBM Watson Machine Learning 🤖📚

![Course Registration Chatbot](https://github.com/Gaganabk2/AI-Powered-Course-Registration-Chatbot/blob/master/ibm.jpeg)

> An intelligent chatbot designed to streamline the course registration process using artificial intelligence and natural language processing.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## 🎯 Overview

The AI-Powered Course Registration Chatbot is an intelligent system that helps students navigate the course registration process through natural language interactions. The chatbot can understand student queries, provide course information, assist with registration procedures, and maintain student records efficiently.

## ✨ Features

- **🤖 Natural Language Processing**: Understands and responds to student queries in natural language
- **📊 Course Management**: Provides detailed information about available courses
- **👥 Student Database**: Maintains comprehensive student records and registration history
- **💬 Interactive Chat Interface**: User-friendly web-based chat interface
- **🔍 Smart Search**: Intelligent course search and recommendation system
- **📱 Responsive Design**: Works seamlessly across desktop and mobile devices
- **🔐 Secure Data Handling**: Safe storage and management of student information

## 🛠️ Technologies Used

- **Backend**: Python
- **Database**: SQLite
- **Frontend**: HTML, CSS, JavaScript (Templates)
- **AI/ML**: Natural Language Processing libraries
- **Web Framework**: Flask/Django (based on project structure)

## 🚀 Installation

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/AI-Powered-Course-Registration-Chatbot.git
   cd AI-Powered-Course-Registration-Chatbot
   ```

2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Initialize the database**
   ```bash
   python db.py
   ```

5. **Run the application**
   ```bash
   python main.py
   ```

6. **Access the application**
   Open your web browser and navigate to `http://localhost:5000`

## 💻 Usage

### Starting a Conversation

1. Open the web application in your browser
2. Type your query in the chat interface
3. The chatbot will respond with relevant information or ask follow-up questions

### Example Interactions

```
Student: "I want to register for computer science courses"
Chatbot: "Great! I can help you with CS course registration. What level are you looking for - beginner, intermediate, or advanced?"

Student: "Show me available Python courses"
Chatbot: "Here are the available Python courses: [Course List with details]"

Student: "What are the prerequisites for Data Structures?"
Chatbot: "For Data Structures (CS201), you need: Introduction to Programming (CS101) and Mathematics I (MATH101)"
```

## 📁 File Structure

```
AI-Powered-Course-Registration-Chatbot/
│
├── chatbot.py              # Main chatbot logic and NLP processing
├── db.py                   # Database operations and management
├── main.py                 # Application entry point and web server
├── requirements.txt        # Python dependencies
├── student_details.db      # SQLite database file
├── LICENSE                 # Project license
├── .gitignore             # Git ignore rules
│
├── static/                 # Static web assets
│   ├── css/               # Stylesheets
│   ├── js/                # JavaScript files
│   └── images/            # Image assets
│
└── templates/              # HTML templates
    ├── index.html         # Main chat interface
    ├── base.html          # Base template
    └── components/        # Reusable components
```

## 📸 Screenshots

![Chat Interface](https://via.placeholder.com/600x400/2196F3/FFFFFF?text=Chat+Interface)
*Main chat interface where students interact with the bot*

![Course Information](https://via.placeholder.com/600x400/FF9800/FFFFFF?text=Course+Information)
*Course details and registration information display*

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Gagana BK**

- GitHub: [@Gaganabk2](https://github.com/Gaganabk2)
- Email: bkgagana97@gmail.com

---

⭐ If you found this project helpful, please give it a star!

## 📞 Support

If you have any questions or need support, please feel free to:
- Open an issue on GitHub
- Contact the author via email
- Check the documentation in the code comments

---

*Made with ❤️ by Gagana BK*
