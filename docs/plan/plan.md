# Plans

## 一天时间安排
（按重要性优先级排列）
1. 
2. 


## 短期目标
<body>
    <div style="background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 12px; padding: 30px 40px; text-align: center; color: #555; font-size: 1.2em; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08); width: 320px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;">
        <p style="margin-top: 0;">
            <span>距离找到实习</span>
        </p>
        <div id="countdown-timer" style="font-weight: bold; font-size: 2em; color: #1a1a1a; margin-top: 10px; letter-spacing: 2px;"></div>
    </div>
    <script>
    function updateCountdown() {
      const targetDate = '2025-10-30 00:00:00';
      const targetTime = new Date(targetDate).getTime();
      const currentTime = new Date().getTime();
      let difference = targetTime - currentTime;
      const timerElement = document.getElementById('countdown-timer');
      if (difference <= 0) {
        timerElement.innerHTML = "目标日期已到达！";
        clearInterval(countdownInterval); 
        return;
      }
      let days = Math.floor(difference / (1000 * 60 * 60 * 24));
      let hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      let minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
      let seconds = Math.floor((difference % (1000 * 60)) / 1000);
      timerElement.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
    }
    const countdownInterval = setInterval(updateCountdown, 1000);
    updateCountdown(); 
    </script>
</body>

<body>
    <div style="background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 12px; padding: 30px 40px; text-align: center; color: #555; font-size: 1.2em; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08); width: 320px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;">
        <p style="margin-top: 0;">
            <span>距离日语N2</span>
        </p>
        <div id="countdown-timer" style="font-weight: bold; font-size: 2em; color: #1a1a1a; margin-top: 10px; letter-spacing: 2px;"></div>
    </div>
    <script>
    function updateCountdown() {
      const targetDate = '2025-12-07 08:00:00';
      const targetTime = new Date(targetDate).getTime();
      const currentTime = new Date().getTime();
      let difference = targetTime - currentTime;
      const timerElement = document.getElementById('countdown-timer');
      if (difference <= 0) {
        timerElement.innerHTML = "目标日期已到达！";
        clearInterval(countdownInterval); 
        return;
      }
      let days = Math.floor(difference / (1000 * 60 * 60 * 24));
      let hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      let minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
      let seconds = Math.floor((difference % (1000 * 60)) / 1000);
      timerElement.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
    }
    const countdownInterval = setInterval(updateCountdown, 1000);
    updateCountdown(); 
    </script>
</body>


## 养成习惯

## 大目标