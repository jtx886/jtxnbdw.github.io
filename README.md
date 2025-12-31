<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2026跨年限定版祝福代码</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Microsoft YaHei', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0c0032, #190061, #240090, #3500d3);
            color: #fff;
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            position: relative;
            z-index: 10;
        }
        
        header {
            text-align: center;
            padding: 40px 0 30px;
        }
        
        .logo {
            font-size: 2.8rem;
            font-weight: bold;
            margin-bottom: 10px;
            background: linear-gradient(to right, #ff8a00, #da1b60);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 15px rgba(255, 138, 0, 0.5);
            letter-spacing: 2px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 30px;
            color: #e6e6fa;
        }
        
        .main-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 40px;
            margin-bottom: 40px;
        }
        
        .countdown-box {
            background: rgba(255, 255, 255, 0.08);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            flex: 1;
            min-width: 300px;
            max-width: 500px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        .countdown-title {
            font-size: 1.8rem;
            margin-bottom: 25px;
            text-align: center;
            color: #ffcc00;
            text-shadow: 0 0 10px rgba(255, 204, 0, 0.5);
        }
        
        .countdown {
            display: flex;
            justify-content: space-around;
            text-align: center;
            margin-bottom: 20px;
        }
        
        .countdown-item {
            display: flex;
            flex-direction: column;
        }
        
        .countdown-number {
            font-size: 3rem;
            font-weight: bold;
            background: linear-gradient(to bottom, #ffcc00, #ff6600);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            line-height: 1;
            margin-bottom: 5px;
            text-shadow: 0 0 15px rgba(255, 102, 0, 0.3);
        }
        
        .countdown-label {
            font-size: 1rem;
            color: #ccccff;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .new-year {
            font-size: 3.5rem;
            font-weight: bold;
            text-align: center;
            margin: 30px 0;
            background: linear-gradient(to right, #ff3366, #ff9933, #33ccff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 20px rgba(255, 51, 102, 0.4);
        }
        
        .message-box {
            background: rgba(255, 255, 255, 0.08);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            flex: 1;
            min-width: 300px;
            max-width: 500px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        .message-title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            text-align: center;
            color: #33ccff;
            text-shadow: 0 0 10px rgba(51, 204, 255, 0.5);
        }
        
        .message-content {
            font-size: 1.2rem;
            line-height: 1.8;
            min-height: 200px;
            padding: 15px;
            background: rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            border-left: 4px solid #ff3366;
        }
        
        .typing-cursor {
            display: inline-block;
            width: 3px;
            height: 1.2rem;
            background-color: #ffcc00;
            margin-left: 2px;
            animation: blink 1s infinite;
        }
        
        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0; }
        }
        
        .code-section {
            background: rgba(255, 255, 255, 0.08);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 30px;
            margin-top: 20px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
        }
        
        .code-title {
            font-size: 1.8rem;
            margin-bottom: 20px;
            text-align: center;
            color: #ff66cc;
            text-shadow: 0 0 10px rgba(255, 102, 204, 0.5);
        }
        
        .code-content {
            font-family: 'Courier New', monospace;
            background: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 10px;
            overflow-x: auto;
            font-size: 1.1rem;
            line-height: 1.6;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .code-line {
            margin-bottom: 8px;
        }
        
        .code-comment {
            color: #66ff66;
        }
        
        .code-keyword {
            color: #ff9966;
        }
        
        .code-string {
            color: #66ccff;
        }
        
        .code-function {
            color: #ffcc66;
        }
        
        .footer {
            text-align: center;
            padding: 30px 0;
            color: #ccccff;
            font-size: 1rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            margin-top: 40px;
        }
        
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .social-icons a {
            color: #fff;
            font-size: 1.5rem;
            transition: all 0.3s ease;
        }
        
        .social-icons a:hover {
            color: #ffcc00;
            transform: translateY(-5px);
        }
        
        /* 飘落效果 */
.snowflake, .confetti {
            position: absolute;
            background: #fff;
            border-radius: 50%;
            pointer-events: none;
            z-index: 1;
        }
        
        .confetti {
            width: 10px;
            height: 10px;
            opacity: 0.8;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .logo {
                font-size: 2.2rem;
            }
            
            .new-year {
                font-size: 2.5rem;
            }
            
            .countdown-number {
                font-size: 2.2rem;
            }
            
            .countdown-title, .message-title, .code-title {
                font-size: 1.5rem;
            }
            
            .countdown-box, .message-box {
                min-width: 100%;
            }
        }
        
        /* 按钮样式 */
        .btn {
            display: inline-block;
            background: linear-gradient(to right, #ff3366, #ff9933);
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 20px;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(255, 51, 102, 0.4);
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(255, 51, 102, 0.6);
        }
        
        .button-container {
            text-align: center;
            margin-top: 30px;
        }
    </style>
</head>
<body>
    <!-- 飘落效果元素 -->
    <div id="snowflakes-container"></div>
    <div id="confetti-container"></div>
    
    <div class="container">
        <header>
            <h1 class="logo">2026跨年限定版祝福代码</h1>
            <p class="subtitle">由杰同学为你生成的新年专属祝福 ✨</p>
        </header>
        
        <div class="main-content">
            <div class="countdown-box">
                <h2 class="countdown-title">距离2026年还有</h2>
                <div class="countdown">
                    <div class="countdown-item">
                        <div class="countdown-number" id="days">000</div>
                        <div class="countdown-label">天</div>
                    </div>
                    <div class="countdown-item">
                        <div class="countdown-number" id="hours">00</div>
                        <div class="countdown-label">时</div>
                    </div>
                    <div class="countdown-item">
                        <div class="countdown-number" id="minutes">00</div>
                        <div class="countdown-label">分</div>
                    </div>
                    <div class="countdown-item">
                        <div class="countdown-number" id="seconds">00</div>
                        <div class="countdown-label">秒</div>
                    </div>
                </div>
                
                <div class="new-year" id="new-year-text">2026</div>
                
                <div class="button-container">
                    <button class="btn" id="share-btn">
                        <i class="fas fa-share-alt"></i> 分享祝福
                    </button>
                </div>
            </div>
            
            <div class="message-box">
                <h2 class="message-title">新年祝福语</h2>
                <div class="message-content" id="typing-message">
                    <!-- 打字机效果将在这里显示 -->
                </div>
                <div class="button-container">
                    <button class="btn" id="new-message-btn">
                        <i class="fas fa-sync-alt"></i>换一条祝福
                    </button>
                </div>
            </div>
        </div>
        
        <div class="code-section">
            <h2 class="code-title">祝福源代码</h2>
            <div class="code-content">
                <div class="code-line"><span class="code-comment">// 2026新年祝福代码</span></div>
                <div class="code-line"><span class="code-comment">// 作者：杰同学</span></div>
                <div class="code-line"><span class="code-comment">// 生成时间：2025年12月31日</span></div>
                <div class="code-line"><br></div>
                <div class="code-line"><span class="code-keyword">function</span> <span class="code-function">newYear2026</span>() {</div>
                <div class="code-line">&nbsp;&nbsp;<span class="code-keyword">const</span> blessings = [</div>
                <div class="code-line">&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-string">"愿2026的你，代码无bug，生活无烦恼！"</span>,</div>
                <div class="code-line">&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-string">"新年快乐！愿你的每一个梦想都能编译成功！"</span>,</div>
                <div class="code-line">&nbsp;&nbsp;&nbsp;&nbsp;<span class="code-string">"2026，愿你的人生算法越来越优化！"</span></div>
                <div class="code-line">&nbsp;&nbsp;];</div>
                <div class="code-line"><br></div>
                <div class="code-line">&nbsp;&nbsp;<span class="code-keyword">const</span> countdown = <span class="code-function">calculateCountdown</span>(<span class="code-string">"2026-01-01"</span>);</div>
                <div class="code-line">&nbsp;&nbsp;<span class="code-function">displayCountdown</span>(countdown);</div>
                <div class="code-line"><br></div>
                <div class="code-line">&nbsp;&nbsp;<span class="code-keyword">const</span> randomBlessing = blessings[<span class="code-function">randomIndex</span>(blessings.<span class="code-keyword">length</span>)];</div>
                <div class="code-line">&nbsp;&nbsp;<span class="code-function">showBlessing</span>(randomBlessing);</div>
                <div class="code-line">}</div>
                <div class="code-line"><br></div>
                <div class="code-line"><span class="code-function">newYear2026</span>(); <span class="code-comment">// 执行祝福函数</span></div>
            </div>
        </div>
        
        <footer class="footer">
            <p>© 2025 杰同学 | 2026跨年限定版祝福代码</p>
            <p>愿这份代码为你带来一整年的好运与快乐！</p>
            
            <div class="social-icons">
               <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-weixin"></i></a>
                <a href="#"><i class="fab fa-qq"></i></a>
                <a href="#"><i class="fab fa-bilibili"></i></a>
                <a href="#"><i class="fab fa-tiktok"></i></a>
            </div>
        </footer>
    </div>

    <script>
        // 倒计时功能
function updateCountdown() {
            const targetDate = new Date('2026-01-01T00:00:00').getTime();
            const now = new Date().getTime();
            const timeLeft = targetDate - now;
            
            if (timeLeft > 0) {
                const days = Math.floor(timeLeft / (1000 * 60 * 60 * 24));
                const hours = Math.floor((timeLeft % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((timeLeft % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((timeLeft % (1000 * 60)) / 1000);
                
                document.getElementById('days').textContent = String(days).padStart(3, '0');
                document.getElementById('hours').textContent = String(hours).padStart(2, '0');
                document.getElementById('minutes').textContent = String(minutes).padStart(2, '0');
                document.getElementById('seconds').textContent = String(seconds).padStart(2, '0');
            } else {
                document.getElementById('days').textContent = '000';
                document.getElementById('hours').textContent = '00';
                document.getElementById('minutes').textContent = '00';
                document.getElementById('seconds').textContent = '00';
                
                // 如果已经到了2026年，更新文字
                document.getElementById('new-year-text').textContent = "2026新年快乐！";
            }
        }
        
        // 初始化倒计时
        updateCountdown();
        setInterval(updateCountdown, 1000);
        
        // 祝福语数组
        const blessings = [
    "杰同学祝你在2026天天开心",
    "新的一年，愿你眼里有光，心中有爱，脚下有路，未来可期。",
    "2026，愿你所求皆所愿，所行皆坦途，多喜乐，长安宁。",
    "愿新年，胜旧年，岁岁常欢愉，年年皆胜意。",
    "新的一年，愿你万事随想，所爱如山，从此眼底是绮丽，周遭是晴朗。",
    "2026，愿你的生活有热汤和甜食，背包里有书本和远方，一切困难都能云淡风轻。",
    "新年快乐！愿家人安康，朋友常在，所爱之人皆伴身旁。",
    "2026，愿你心怀梦想，眼中有光，步履不停，未来可期。",
    "新的一年杰同学祝你，心想事成，天天开心，和喜欢的人永远在一起",
    "愿时光能缓，故人不散，愿你惦念的人能和你道晚安。"
];
        
        // 打字机效果显示祝福语
        let messageIndex = 0;
        let charIndex = 0;
        let isDeleting = false;
        let typingSpeed = 50;
        
        function typeMessage() {
            const messageElement = document.getElementById('typing-message');
            const currentMessage = blessings[messageIndex];
            
            if (isDeleting) {
                // 删除效果
                messageElement.innerHTML = currentMessage.substring(0, charIndex - 1) + '<span class="typing-cursor"></span>';
                charIndex--;
                typingSpeed = 30;
            } else {
                // 打字效果
                messageElement.innerHTML = currentMessage.substring(0, charIndex + 1) + '<span class="typing-cursor"></span>';
                charIndex++;
                typingSpeed = 50;
            }
            
            // 如果打字完成
            if (!isDeleting && charIndex === currentMessage.length) {
                // 暂停2秒后开始删除
                isDeleting = true;
                typingSpeed = 1500;
            } 
            // 如果删除完成
            else if (isDeleting && charIndex === 0) {
                isDeleting = false;
                // 切换到下一条祝福语
                messageIndex = (messageIndex + 1) % blessings.length;
                typingSpeed = 500;
            }
            
            setTimeout(typeMessage, typingSpeed);
        }
        
        // 初始化打字效果
        setTimeout(typeMessage, 1000);
        
        // 换一条祝福按钮
        document.getElementById('new-message-btn').addEventListener('click', function() {
            messageIndex = (messageIndex + 1) % blessings.length;
            charIndex = 0;
            isDeleting = false;
        });
        
        // 分享按钮
        document.getElementById('share-btn').addEventListener('click', function() {
            const shareText = "杰同学祝你2026天天开心";
            if (navigator.share) {
                navigator.share({
                    title: '2026跨年限定版祝福代码',
                    text: shareText,
                    url: window.location.href
                });
            } else {
                // 复制到剪贴板
                const tempInput = document.createElement('input');
                tempInput.value = window.location.href;
                document.body.appendChild(tempInput);
                tempInput.select();
                document.execCommand('copy');
                document.body.removeChild(tempInput);
                
                alert("链接已复制到剪贴板，快去分享给朋友吧！");
            }
        });
        
        // 创建飘落效果
        function createSnowflakes() {
            const container = document.getElementById('snowflakes-container');
            const snowflakeCount = 50;
            
            for (let i = 0; i < snowflakeCount; i++) {
                const snowflake = document.createElement('div');
                snowflake.classList.add('snowflake');
                
                // 随机大小
                const size = Math.random() * 5 + 3;
                snowflake.style.width = `${size}px`;
                snowflake.style.height = `${size}px`;
                
                // 随机位置
                snowflake.style.left = `${Math.random() * 100}vw`;
                snowflake.style.top = `${Math.random() * 100}vh`;
                
                // 随机透明度
                snowflake.style.opacity = Math.random() * 0.5 + 0.3;
                
                // 随机动画
                const duration = Math.random() * 10 + 10;
                snowflake.style.animation = `fall ${duration}s linear infinite`;
                
                // 创建动画
                const keyframes = `
                @keyframes fall {
                    0% {
                        transform: translateY(-100px) rotate(0deg);
                    }
                    100% {
                        transform: translateY(100vh) rotate(360deg);
                    }
                }`;
                
                const styleSheet = document.createElement('style');
                styleSheet.textContent = keyframes;
                document.head.appendChild(styleSheet);
                
                container.appendChild(snowflake);
            }
        }
        
        // 创建彩色纸屑
        function createConfetti() {
            const container = document.getElementById('confetti-container');
            const confettiCount = 100;
            const colors = ['#ff3366', '#ff9933', '#33ccff', '#ffcc00', '#66ff66', '#ff66cc'];
            
            for (let i = 0; i < confettiCount; i++) {
                const confetti = document.createElement('div');
                confetti.classList.add('confetti');
                
                // 随机颜色
                confetti.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
                
                // 随机大小
                const size = Math.random() * 8 + 5;
                confetti.style.width = `${size}px`;
                confetti.style.height = `${size}px`;
                
                // 随机形状
                if (Math.random() > 0.5) {
                    confetti.style.borderRadius = '50%';
                } else {
                    confetti.style.borderRadius = '0';
                }
                
                // 随机位置
                confetti.style.left = `${Math.random() * 100}vw`;
                confetti.style.top = `${Math.random() * 100}vh`;
                
                // 随机动画
                const duration = Math.random() * 15 + 10;
                confetti.style.animation = `fall ${duration}s linear infinite`;
                
                container.appendChild(confetti);
            }
        }
        
        // 初始化飘落效果
createSnowflakes();
        createConfetti();
        
        // 新年文字动画
        const newYearText = document.getElementById('new-year-text');
        let scale = 1;
        let growing = false;
        
        function animateNewYearText() {
            if (growing) {
                scale += 0.005;
                if (scale >= 1.1) {
                    growing = false;
                }
            } else {
                scale -= 0.005;
                if (scale <= 1) {
                    growing = true;
                }
            }
            
            newYearText.style.transform = `scale(${scale})`;
            requestAnimationFrame(animateNewYearText);
        }
        
        // 开始文字动画
        animateNewYearText();
    </script>
</body>
</html>
