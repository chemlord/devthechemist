---
# Front matter (adjust if needed, or keep empty if not using any specific settings)
---
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Alice Wu's Profile</title>
<style>
    body, html {
        margin: 0;
        padding: 0;
        font-family: Arial, sans-serif;
    }

    .container {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f4f4f4;
    }

    .profile {
        background: white;
        width: 70%;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        display: flex;
        flex-direction: row;
        padding: 20px;
    }

    .profile img {
        border-radius: 50%;
        width: 200px;
        height: 200px;
        margin-right: 20px;
    }

    .info {
        width: 80%;
    }

    .info h1 {
        margin-top: 0;
    }

    .title {
        color: #555;
        font-size: 20px;
    }

    .interests ul, .education ul {
        list-style-type: none;
        padding: 0;
    }

    .social-links a {
        margin-right: 10px;
    }
</style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <img src="alice-wu.jpg" alt="Alice Wu">
            <div class="info">
                <h1>Alice Wu 吳愛莉</h1>
                <p class="title">Professor of Artificial Intelligence<br>Stanford University</p>
                <p>Alice Wu is a professor of artificial intelligence at the Stanford AI Lab. Her research interests include distributed robotics, mobile computing, and programmable matter. She leads the Robotic Neurobiology group, which develops self-reconfiguring robots, systems of self-organizing robots, and mobile sensor networks.</p>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.</p>
                <div class="interests">
                    <h2>Interests</h2>
                    <ul>
                        <li>Artificial Intelligence</li>
                        <li>Computational Linguistics</li>
                        <li>Information Retrieval</li>
                    </ul>
                </div>
                <div class="education">
                    <h2>Education</h2>
                    <ul>
                        <li>PhD in Artificial Intelligence, 2012 - Stanford University</li>
                        <li>MEng in Artificial Intelligence, 2009 - Massachusetts Institute of Technology</li>
                        <li>BSc in Artificial Intelligence, 2008 - Massachusetts Institute of Technology</li>
                    </ul>
                </div>
                <div class="social-links">
                    <a href="mailto:alice.wu@example.com"><img src="email-icon.png" alt="Email"></a>
                    <a href="https://twitter.com/alice_wu"><img src="twitter-icon.png" alt="Twitter"></a>
                    <a href="https://github.com/alice_wu"><img src="github-icon.png" alt="GitHub"></a>
                    <a href="https://researchgate.net/profile/Alice_Wu"><img src="researchgate-icon.png" alt="ResearchGate"></a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
