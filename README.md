## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hacker Portfolio</title>
    <style>
        body {
            background-color: black;
            color: lime;
            font-family: 'Courier New', monospace;
            text-align: center;
            overflow: hidden;
        }
        .glitch {
            font-size: 3rem;
            font-weight: bold;
            position: relative;
            display: inline-block;
            text-transform: uppercase;
            animation: glitch 1.5s infinite alternate;
        }
        @keyframes glitch {
            0% { text-shadow: 2px 2px 5px red, -2px -2px 5px blue; }
            50% { text-shadow: -2px -2px 5px red, 2px 2px 5px blue; }
            100% { text-shadow: 2px -2px 5px red, -2px 2px 5px blue; }
        }
        .rgb-text {
            font-size: 2rem;
            animation: rgb 2s infinite alternate;
        }
        @keyframes rgb {
            0% { color: red; }
            33% { color: green; }
            66% { color: blue; }
            100% { color: red; }
        }
        .skills {
            margin-top: 20px;
            font-size: 1.5rem;
        }
        .skills img {
            width: 50px;
            height: 50px;
            margin: 5px;
        }
        .social-media img {
            width: 50px;
            height: 50px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <h1 class="glitch">Welcome to My Hacker Portfolio</h1>
    <p class="rgb-text">Full Stack Developer | Machine Learning | Hacking | Cloud | Web Development</p>
    <div class="skills">
        <p>Languages:</p>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" alt="Go">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-plain.svg" alt="Rust">
        <p>Frameworks:</p>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-original.svg" alt="Django">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" alt="Flask">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" alt="Express">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch">
        <p>Tools:</p>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" alt="Kubernetes">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" alt="AWS">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" alt="Azure">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/debian/debian-original.svg" alt="Debian">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redhat/redhat-original.svg" alt="RedHat">
    </div>
    <div class="social-media">
        <p>Connect with me:</p>
        <a href="https://www.instagram.com/" target="_blank">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/instagram/instagram-original.svg" alt="Instagram">
        </a>
        <a href="https://www.facebook.com/" target="_blank">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/facebook/facebook-original.svg" alt="Facebook">
        </a>
        <a href="https://www.linkedin.com/" target="_blank">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="LinkedIn">
        </a>
        <a href="https://www.tiktok.com/" target="_blank">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tiktok/tiktok-original.svg" alt="TikTok">
        </a>
    </div>
</body>
</html>
