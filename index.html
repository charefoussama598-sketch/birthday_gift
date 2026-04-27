<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Special Gift for You 🎁</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: radial-gradient(circle, #fff0f6 0%, #fcc2d7 100%);
            font-family: 'Poppins', sans-serif;
            overflow: hidden;
            touch-action: manipulation;
        }

        #hint-bar {
            position: fixed;
            top: 40px;
            background: rgba(255, 255, 255, 0.8);
            padding: 10px 20px;
            border-radius: 30px;
            color: #d6336c;
            font-weight: bold;
            z-index: 200;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .gift-container {
            position: absolute;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            z-index: 100;
            user-select: none;
            -webkit-tap-highlight-color: transparent;
        }

        .gift-box {
            font-size: 80px;
            filter: drop-shadow(0 10px 15px rgba(0,0,0,0.1));
        }

        #celebration {
            display: none;
            text-align: center;
            padding: 20px;
            animation: popIn 1s ease-out forwards;
        }

        @keyframes popIn {
            0% { opacity: 0; transform: scale(0.5); }
            100% { opacity: 1; transform: scale(1); }
        }

        .main-title { color: #d6336c; font-size: 2.2rem; margin: 10px 0; }
        .sub-text { color: #862e9c; font-size: 1.2rem; }

        .particle {
            position: absolute;
            pointer-events: none;
            animation: floatUp 4s linear forwards;
            z-index: 50;
        }

        @keyframes floatUp {
            0% { transform: translateY(110vh) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-10vh) rotate(360deg); opacity: 0; }
        }

        @keyframes shake {
            0%, 100% { transform: rotate(0); }
            25% { transform: rotate(10deg); }
            75% { transform: rotate(-10deg); }
        }
    </style>
</head>
<body>

    <div id="hint-bar">
        Tap the gift! 🎁 <br>
        <span id="counter">Remaining: 5</span>
    </div>

    <div class="gift-container" id="gift-section" onclick="handleInteraction()">
        <div class="gift-box" id="actual-gift">🎁</div>
    </div>

    <div id="celebration">
        <div style="font-size: 80px;">🌸</div>
        <h1 class="main-title">Happy Birthday, Gorgeous! ✨</h1>
        <p class="sub-text">Wishing you a year as lovely as you are.</p>
        <div style="font-size: 40px; margin-top: 20px;">🎂💖👑</div>
    </div>

    <script>
        let touchCount = 0;
        const maxTouches = 5; 
        const giftContainer = document.getElementById('gift-section');
        const giftEmoji = document.getElementById('actual-gift');
        const hint = document.getElementById('hint-bar');
        const counterText = document.getElementById('counter');

        function handleInteraction() {
            if (touchCount < maxTouches) {
                // تحريك الهدية
                const padding = 80;
                const newX = Math.random() * (window.innerWidth - padding * 2) + padding;
                const newY = Math.random() * (window.innerHeight - padding * 2) + padding;
                
                giftContainer.style.left = (newX - 40) + 'px';
                giftContainer.style.top = (newY - 40) + 'px';
                
                touchCount++;
                counterText.innerText = "Remaining: " + (maxTouches - touchCount);

                if (touchCount === maxTouches) {
                    counterText.innerText = "You won! ✨";
                    hint.style.background = "#fff0f6";
                    giftContainer.style.left = "50%";
                    giftContainer.style.top = "50%";
                    giftContainer.style.transform = "translate(-50%, -50%)";
                    giftEmoji.style.animation = "shake 0.5s infinite";
                    giftEmoji.innerHTML = "💝"; 
                }
            } else {
                openSurprise();
            }
        }

        function openSurprise() {
            giftContainer.style.display = 'none';
            hint.style.display = 'none';
            document.getElementById('celebration').style.display = 'block';
            document.body.style.background = "#fff5f8";
            setInterval(createParticle, 150);
        }

        function createParticle() {
            const symbols = ['💖', '🌸', '✨', '💕', '🎈'];
            const p = document.createElement('div');
            p.classList.add('particle');
            p.innerHTML = symbols[Math.floor(Math.random() * symbols.length)];
            p.style.left = Math.random() * 100 + 'vw';
            p.style.fontSize = (Math.random() * 20 + 20) + 'px';
            document.body.appendChild(p);
            setTimeout(() => p.remove(), 4000);
        }

        window.onload = () => {
            giftContainer.style.left = "50%";
            giftContainer.style.top = "50%";
            giftContainer.style.transform = "translate(-50%, -50%)";
        };
    </script>
</body>
</html>
