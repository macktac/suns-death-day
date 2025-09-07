<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Final Countdown</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Courier New', monospace;
            background: linear-gradient(135deg, #0c0c0c 0%, #1a0000 50%, #330000 100%);
            color: #ff4444;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow-x: hidden;
            position: relative;
        }

        /* Animated stars background */
        .stars {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .star {
            position: absolute;
            background: white;
            border-radius: 50%;
            animation: twinkle 2s infinite alternate;
        }

        @keyframes twinkle {
            0% { opacity: 0.3; }
            100% { opacity: 1; }
        }

        .container {
            text-align: center;
            z-index: 10;
            max-width: 1200px;
            padding: 20px;
        }

        h1 {
            font-size: clamp(2rem, 8vw, 6rem);
            margin-bottom: 20px;
            text-shadow: 0 0 20px #ff4444, 0 0 40px #ff2222, 0 0 60px #ff0000;
            animation: glow 3s ease-in-out infinite alternate;
            letter-spacing: 2px;
        }

        @keyframes glow {
            0% { text-shadow: 0 0 20px #ff4444, 0 0 40px #ff2222, 0 0 60px #ff0000; }
            100% { text-shadow: 0 0 30px #ff6666, 0 0 50px #ff4444, 0 0 80px #ff2222; }
        }

        .subtitle {
            font-size: clamp(1rem, 3vw, 1.5rem);
            margin-bottom: 40px;
            opacity: 0.8;
            color: #ffaaaa;
        }

        .countdown-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin: 40px 0;
            max-width: 1000px;
        }

        .time-unit {
            background: rgba(255, 68, 68, 0.1);
            border: 2px solid #ff4444;
            border-radius: 15px;
            padding: 20px;
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
        }

        .time-unit:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(255, 68, 68, 0.3);
            border-color: #ff6666;
        }

        .time-number {
            font-size: clamp(1.5rem, 4vw, 2.5rem);
            font-weight: bold;
            display: block;
            margin-bottom: 10px;
            color: #fff;
            text-shadow: 0 0 10px #ff4444;
        }

        .time-label {
            font-size: clamp(0.8rem, 2vw, 1rem);
            text-transform: uppercase;
            letter-spacing: 1px;
            opacity: 0.7;
        }

        .sun-animation {
            width: 100px;
            height: 100px;
            background: radial-gradient(circle, #ffff44 0%, #ff8844 50%, #ff4444 100%);
            border-radius: 50%;
            margin: 30px auto;
            animation: pulse 4s ease-in-out infinite;
            box-shadow: 0 0 50px #ffaa44, 0 0 100px #ff8844;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); opacity: 0.8; }
            50% { transform: scale(1.1); opacity: 1; }
        }

        .description {
            max-width: 800px;
            margin: 40px auto;
            line-height: 1.8;
            font-size: clamp(0.9rem, 2.5vw, 1.1rem);
            opacity: 0.8;
            color: #ffcccc;
        }

        .warning {
            background: rgba(255, 0, 0, 0.1);
            border: 1px solid #ff4444;
            border-radius: 10px;
            padding: 20px;
            margin: 30px auto;
            max-width: 600px;
            font-style: italic;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .countdown-grid {
                grid-template-columns: repeat(2, 1fr);
                gap: 15px;
            }
            
            .time-unit {
                padding: 15px;
            }
        }

        @media (max-width: 480px) {
            .countdown-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="stars" id="stars"></div>
    
    <div class="container">
        <h1>THE FINAL COUNTDOWN</h1>
        <p class="subtitle">Time until the Sun becomes a Red Giant</p>
        <p class="subtitle">reminder to be kind today </p>
        
        <div class="sun-animation"></div>
        
        <div class="countdown-grid">
            <div class="time-unit">
                <span class="time-number" id="billion-years">0</span>
                <span class="time-label">Billion Years</span>
            </div>
            <div class="time-unit">
                <span class="time-number" id="years">0</span>
                <span class="time-label">Years</span>
            </div>
            <div class="time-unit">
                <span class="time-number" id="days">0</span>
                <span class="time-label">Days</span>
            </div>
            <div class="time-unit">
                <span class="time-number" id="hours">0</span>
                <span class="time-label">Hours</span>
            </div>
            <div class="time-unit">
                <span class="time-number" id="minutes">0</span>
                <span class="time-label">Minutes</span>
            </div>
            <div class="time-unit">
                <span class="time-number" id="seconds">0</span>
                <span class="time-label">Seconds</span>
            </div>
        </div>
        
        <div class="description">
            <p>In approximately 5 billion years, our Sun will exhaust its hydrogen fuel and begin to expand into a red giant star. During this phase, it will grow so large that it may engulf Mercury, Venus, and possibly Earth, marking the end of life as we know it on our planet.</p>
        </div>
        
        <div class="warning">
            ⚠️ Don't worry too much about this deadline - humanity has plenty of time to figure things out!
        </div>
    </div>

    <script>
        // Calculate 5 billion years from now in milliseconds
        const now = Date.now();
        const millisecondsPerYear = 365.25 * 24 * 60 * 60 * 1000; // Account for leap years
        const fiveBillionYears = 5000000000 * millisecondsPerYear;
        const targetTime = now + fiveBillionYears;

        // Create animated stars
        function createStars() {
            const starsContainer = document.getElementById('stars');
            const numStars = 150;
            
            for (let i = 0; i < numStars; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                star.style.left = Math.random() * 100 + '%';
                star.style.top = Math.random() * 100 + '%';
                star.style.width = Math.random() * 3 + 1 + 'px';
                star.style.height = star.style.width;
                star.style.animationDelay = Math.random() * 2 + 's';
                star.style.animationDuration = (Math.random() * 3 + 1) + 's';
                starsContainer.appendChild(star);
            }
        }

        function updateCountdown() {
            const currentTime = Date.now();
            const difference = targetTime - currentTime;

            if (difference > 0) {
                // Calculate all time units from the total difference
                const totalSeconds = Math.floor(difference / 1000);
                const totalMinutes = Math.floor(totalSeconds / 60);
                const totalHours = Math.floor(totalMinutes / 60);
                const totalDays = Math.floor(totalHours / 24);
                const totalYears = Math.floor(totalDays / 365.25);
                
                // Break down into display units
                const billionYears = Math.floor(totalYears / 1000000000);
                const remainingYears = totalYears % 1000000000;
                const days = totalDays % Math.floor(365.25);
                const hours = totalHours % 24;
                const minutes = totalMinutes % 60;
                const seconds = totalSeconds % 60;

                // Update display
                document.getElementById('billion-years').textContent = billionYears.toLocaleString();
                document.getElementById('years').textContent = remainingYears.toLocaleString();
                document.getElementById('days').textContent = days.toLocaleString();
                document.getElementById('hours').textContent = hours.toString().padStart(2, '0');
                document.getElementById('minutes').textContent = minutes.toString().padStart(2, '0');
                document.getElementById('seconds').textContent = seconds.toString().padStart(2, '0');
            } else {
                // The sun has died (theoretically)
                document.querySelector('h1').textContent = 'THE SUN HAS DIED';
                document.querySelector('.subtitle').textContent = 'The end has come...';
                
                document.querySelectorAll('.time-number').forEach(el => {
                    el.textContent = '00';
                });
            }
        }

        // Initialize
        createStars();
        updateCountdown();
        setInterval(updateCountdown, 1000);

        // Add some interactive effects
        document.querySelectorAll('.time-unit').forEach(unit => {
            unit.addEventListener('mouseenter', () => {
                unit.style.transform = 'translateY(-8px) scale(1.05)';
            });
            
            unit.addEventListener('mouseleave', () => {
                unit.style.transform = 'translateY(0) scale(1)';
            });
        });
    </script>
</body>
</html>
