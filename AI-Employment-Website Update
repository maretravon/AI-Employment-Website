<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI and Its Impact on Employment</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f9;
        }
        header {
            background-color: #2a9d8f;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            background-color: #264653;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        nav ul li a:hover {
            color: #2a9d8f;
        }
        .hero {
            background-color: #e9c46a;
            text-align: center;
            padding: 2rem 0;
        }
        .hero h1 {
            font-size: 2.5rem;
        }
        .hero p {
            margin: 1rem 0;
            font-size: 1.2rem;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            overflow: hidden;
            padding: 2rem;
        }
        .card {
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin: 20px 0;
            padding: 20px;
        }
        .card h2 {
            margin-bottom: 10px;
            color: #264653;
        }
        .card p {
            margin-bottom: 15px;
            line-height: 1.5;
        }
        .cta {
            text-align: center;
            padding: 2rem;
            background-color: #264653;
            color: #fff;
        }
        .cta h2 {
            margin-bottom: 1rem;
        }
        .cta a {
            text-decoration: none;
            color: #fff;
            background-color: #e76f51;
            padding: 10px 20px;
            border-radius: 5px;
            transition: 0.3s;
        }
        .cta a:hover {
            background-color: #f4a261;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #264653;
            color: #fff;
        }
        .ai-assistant {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #264653;
            color: #fff;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 1.5rem;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        .ai-chatbox {
            position: fixed;
            bottom: 90px;
            right: 20px;
            width: 300px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            display: none;
            flex-direction: column;
            overflow: hidden;
        }
        .ai-chatbox-header {
            background-color: #264653;
            color: #fff;
            padding: 10px;
            text-align: center;
            font-weight: bold;
        }
        .ai-chatbox-messages {
            padding: 10px;
            height: 200px;
            overflow-y: auto;
        }
        .ai-chatbox-input {
            display: flex;
            border-top: 1px solid #ccc;
        }
        .ai-chatbox-input input {
            width: 100%;
            padding: 10px;
            border: none;
            outline: none;
        }
        .ai-chatbox-input button {
            background-color: #264653;
            color: #fff;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>AI and Its Impact on Employment</h1>
    <p>Exploring Challenges and Solutions for a Fair Future</p>
</header>

<nav>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#solutions">Solutions</a></li>
        <li><a href="#resources">Resources</a></li>
        <li><a href="#contact">Contact Us</a></li>
    </ul>
</nav>

<section class="hero">
    <h1>How AI is Reshaping the Workforce</h1>
    <p>AI can create new opportunities—but also challenges. Let's explore how we can prepare for the future of work.</p>
</section>

<section class="container" id="multimedia">
    <h1>Interactive Learning</h1>
    <p>Explore the impact of AI on employment through interactive multimedia resources.</p>
    <audio controls>
        <source src="audio/ai-impact.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>
    <img src="images/ai-workforce.jpg" alt="AI Workforce" style="width:100%;border-radius:8px;margin-top:20px;">
</section>

<div class="ai-assistant" id="ai-assistant">🤖</div>
<div class="ai-chatbox" id="ai-chatbox">
    <div class="ai-chatbox-header">Ask the AI Assistant</div>
    <div class="ai-chatbox-messages" id="ai-messages"></div>
    <div class="ai-chatbox-input">
        <input type="text" id="ai-input" placeholder="Type your question here...">
        <button id="ai-send">Send</button>
    </div>
</div>

<script>
    const assistantButton = document.getElementById('ai-assistant');
    const chatbox = document.getElementById('ai-chatbox');
    const sendButton = document.getElementById('ai-send');
    const inputField = document.getElementById('ai-input');
    const messagesContainer = document.getElementById('ai-messages');

    assistantButton.addEventListener('click', () => {
        chatbox.style.display = chatbox.style.display === 'none' ? 'flex' : 'none';
    });

    sendButton.addEventListener('click', () => {
        const userMessage = inputField.value;
        if (userMessage) {
            const messageElement = document.createElement('div');
            messageElement.textContent = You: ${userMessage};
            messagesContainer.appendChild(messageElement);
            inputField.value = '';
        }
    });
</script>

<footer>
    <p>AI Employment Impact © 2024 | Designed to Inform & Inspire</p>
</footer>

</body>
</html>
