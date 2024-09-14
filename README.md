<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            background-color: #333;
            color: #fff;
            font-family: Arial, sans-serif;
        }
        a {
            color: #1e90ff;
        }
        .light-mode {
            display: none;
        }
        .dark-mode .light-mode {
            display: block;
        }
        .dark-mode .dark-mode {
            display: none;
        }
        .mode-toggle {
            margin: 20px;
        }
    </style>
    <title>Sonika Pant</title>
</head>

<body class="dark-mode">
    <h1 align="center">Hi 👋, I'm Sonika Pant</h1>
    <h3 align="center">A Passionate Developer</h3>

    <p align="center">
        <img src="https://img.shields.io/badge/Role-Wordpress%20Developer-brightgreen" alt="Role" />
        <img src="https://img.shields.io/badge/Learning-AWS-blue" alt="Learning" />
    </p>

    <p>🔭 I’m currently working as a Wordpress Developer.  
    🌱 I’m currently learning AWS.  
    📫 Feel free to reach me at <a href="mailto:sonikapant02@gmail.com">sonikapant02@gmail.com</a>.</p>

    <h3 align="left">Connect with me:</h3>
    <p align="left">
        <a href="https://www.linkedin.com/in/sonika-pant-874787268/" target="_blank" rel="noreferrer">
            <img src="https://img.shields.io/badge/LinkedIn-Connect%20with%20me-blue" alt="LinkedIn" />
        </a>
    </p>

    <h3 align="left">Languages:</h3>
    <p align="left">
        <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
        </a>
        <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
        </a>
        <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
        </a>
        <a href="https://dart.dev/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/dartlang/dartlang-icon.svg" alt="dart" width="40" height="40"/>
        </a>
    </p>

    <h3 align="left">Frameworks:</h3>
    <p align="left">
        <a href="https://flutter.dev" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/>
        </a>
        <a href="https://getbootstrap.com" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/>
        </a>
    </p>

    <h3 align="left">Backend Services:</h3>
    <p align="left">
        <a href="https://firebase.google.com/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/>
        </a>
    </p>

    <h3 align="left">Tools:</h3>
    <p align="left">
        <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
            <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
        </a>
        <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/>
        </a>
    </p>

    <div class="mode-toggle">
        <button onclick="toggleMode()">Switch to Light Mode</button>
    </div>

    <script>
        function toggleMode() {
            document.body.classList.toggle('dark-mode');
            const isDarkMode = document.body.classList.contains('dark-mode');
            document.querySelector('.mode-toggle button').textContent = isDarkMode ? 'Switch to Light Mode' : 'Switch to Dark Mode';
        }
    </script>
</body>
</html>
