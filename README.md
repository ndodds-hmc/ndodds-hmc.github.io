<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>90s Tech Nostalgia</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            font-family: 'Courier New', Courier, monospace;
            background-color: #008080; /* Classic Windows 95 Teal */
            color: #000000;
            line-height: 1.6;
            padding: 20px;
        }
        header {
            background: linear-gradient(90deg, #000080, #1084d0); /* Windows Title Bar Gradient */
            color: white;
            padding: 15px;
            text-align: center;
            border: 3px outset #fff;
            margin-bottom: 20px;
            box-shadow: 5px 5px 0px #000;
        }
        header h1 {
            font-size: 2.5rem;
            text-shadow: 2px 2px #000;
            letter-spacing: 2px;
        }
        header p {
            font-size: 1.1rem;
            margin-top: 5px;
            color: #ffff00;
            font-weight: bold;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: #c0c0c0; /* Classic Grey App Background */
            border: 4px outset #fff;
            padding: 20px;
            box-shadow: 8px 8px 0px #000;
        }
        .welcome-box {
            background-color: #fff;
            border: 3px inset #808080;
            padding: 15px;
            margin-bottom: 25px;
        }
        .welcome-box h2 {
            color: #000080;
            margin-bottom: 10px;
            border-bottom: 2px solid #000080;
            padding-bottom: 5px;
        }
        .tech-card {
            background-color: #c0c0c0;
            border: 3px outset #fff;
            padding: 15px;
            margin-bottom: 20px;
            box-shadow: 4px 4px 0px #000;
        }
        .tech-card h3 {
            background-color: #000080;
            color: white;
            padding: 5px 10px;
            margin-bottom: 10px;
            font-size: 1.2rem;
        }
        .tech-card p {
            background: #fff;
            padding: 10px;
            border: 2px inset #808080;
        }
        .cta-section {
            text-align: center;
            margin: 30px 0 10px 0;
            padding: 20px;
            background-color: #fff;
            border: 3px inset #808080;
        }
        .btn {
            display: inline-block;
            background-color: #c0c0c0;
            color: #000;
            padding: 10px 20px;
            text-decoration: none;
            font-weight: bold;
            border: 3px outset #fff;
            box-shadow: 3px 3px 0px #000;
            font-size: 1.1rem;
        }
        .btn:hover {
            cursor: pointer;
            background-color: #d5d5d5;
        }
        .btn:active {
            border: 3px inset #fff;
            box-shadow: none;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9rem;
            color: #fff;
            text-shadow: 1px 1px #000;
        }
        .blink {
            animation: blinker 1.5s linear infinite;
            color: #ff0000;
            font-weight: bold;
        }
        @keyframes blinker {
            50% { opacity: 0; }
        }
    </style>
</head>
<body>

    <header>
        <h1>The 90s Tech Time Capsule</h1>
        <p>Welcome to the Golden Era of Dial-Up and Floppy Disks!</p>
    </header>

    <div class="container">
        <section class="welcome-box">
            <h2><span class="blink">📢 NOW LOADING...</span> Welcome to 1995</h2>
            <p>Dust off your CRT monitors and grab your mousepads. This page celebrates the paradigm-shifting hardware, software, and cultural milestones that defined the 1990s digital revolution. Before high-speed fiber optics, we survived on pure patience and 56k modems.</p>
        </section>

        <section class="tech-grid">
            <div class="tech-card">
                <h3><a href="floppy.html" style="color: white;">💾 The 3.5" Floppy Disk (Click for Details)</a></h3>
                <p>Boasting a staggering 1.44 MB of data storage! It held your school essays, pixelated bitmap images, and maybe a text-based game. Today, it survives exclusively as the universal 'Save' icon.</p>
            </div>

            <div class="tech-card">
                <h3>📞 Dial-Up Internet & AOL</h3>
                <p><em>"Pshhhkkkkkkrrrr​kakingkakingtshchchchchchch..."</em> The unforgettable symphony of connecting to the World Wide Web. You couldn't use the house telephone while surfing the web, but hearing "You've Got Mail!" made it all worth it.</p>
            </div>

            <div class="tech-card">
                <h3>📟 Beepers & Pagers</h3>
                <p>Long before smartphones, the pager was the ultimate status symbol. If you wanted to talk, you sent a numeric code like "911" for emergencies or "143" for "I love you," then hunted down a nearby payphone.</p>
            </div>

            <div class="tech-card">
                <h3>💿 CD-ROMs & Multimedia Explodes</h3>
                <p>The 90s marked the transition from floppy disks to shiny discs that could hold a massive 650 MB. Suddenly, video games and interactive encyclopedias like <em>Encarta '95</em> came to life with actual video clips and sound.</p>
            </div>
        </section>

        <section class="cta-section">
            <p style="margin-bottom: 15px; font-weight: bold;">Sign our Guestbook or download our custom cursor pack!</p>
            <a href="#" class="btn">ENTER THE CHATROOM</a>
        </section>
    </div>

    <footer>
        <p>&copy; 1997 RetroTech Web Design Corp. Best viewed in Netscape Navigator 3.0 at 800x600 resolution.</p>
    </footer>

</body>
</html>
