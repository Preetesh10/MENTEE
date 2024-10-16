<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mentee Jecrc</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Navigation Bar -->
    <header>
        <nav>
            <h1>MENTEE</h1>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Mentors</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <section class="hero">
            <div class="hero-text">
                <h2>Connect with Alumni and Experts</h2>
                <p>Find mentorship and career guidance from established professionals.</p>
                <button class="cta-btn">Get Started</button>
            </div>
        </section>

        <section class="mentors">
            <h3>Our Mentors</h3>
            <div class="mentor-card">
                <h4>Preetesh Sharma</h4>
                <p>Tech Expert</p>
                <button class="chat-btn" onclick="openChat()">Chat</button>
            </div>
            <div class="mentor-card">
                <h4>Swastik Bala and Arohi Jain</h4>
                <p>Career Counselor</p>
                <button class="chat-btn" onclick="openChat()">Chat</button>
            </div>
        </section>
    </main>

    <!-- Chat Box -->
    <div id="chat-box" class="chat-box">
        <div class="chat-header">
            <h4>Chat with Mentor</h4>
            <button class="close-btn" onclick="closeChat()">X</button>
        </div>
        <div class="chat-body">
            <p>Hello! How can I assist you today?</p>
        </div>
        <div class="chat-footer">
            <input type="text" placeholder="Type a message...">
            <button>Send</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
