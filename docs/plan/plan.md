# Plans

## 一天时间安排
（按重要性优先级排列）
1. 
2. 


## 短期目标
<!-- <body>
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
      const targetDate1 = '2025-12-07 08:00:00';
      const targetTime1 = new Date(targetDate1).getTime();
      const currentTime1 = new Date().getTime();
      let difference1 = targetTime1 - currentTime1;
      const timerElement = document.getElementById('countdown-timer');
      if (difference1 <= 0) {
        timerElement.innerHTML = "目标日期已到达！";
        clearInterval(countdownInterval1); 
        return;
      }
      let days1 = Math.floor(difference1 / (1000 * 60 * 60 * 24));
      let hours1 = Math.floor((difference1 % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      let minutes1 = Math.floor((difference1 % (1000 * 60 * 60)) / (1000 * 60));
      let seconds1 = Math.floor((difference1 % (1000 * 60)) / 1000);
      timerElement.innerHTML = `${days1}d ${hours1}h ${minutes1}m ${seconds1}s`;
    }
    const countdownInterval1 = setInterval(updateCountdown, 1000);
    updateCountdown(); 
    </script>
</body> -->

<body>
    <div style="display: flex; justify-content: center; align-items: center; gap: 20px; flex-wrap: wrap; padding: 20px;">
        <div style="background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 12px; padding: 30px 40px; text-align: center; color: #555; font-size: 1.2em; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08); width: 320px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;">
            <p style="margin-top: 0;">
                <span>距离 <strong>放假 </strong> 还剩</span>
            </p>
            <div id="countdown-timer-1" style="font-weight: bold; font-size: 2em; color: #1a1a1a; margin-top: 10px; letter-spacing: 2px;"></div>
        </div>
        <div style="background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 12px; padding: 30px 40px; text-align: center; color: #555; font-size: 1.2em; box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08); width: 320px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;">
            <p style="margin-top: 0;">
                <span>距离 <strong>放假 </strong> 还剩</span>
            </p>
            <div id="countdown-timer-2" style="font-weight: bold; font-size: 2em; color: #1a1a1a; margin-top: 10px; letter-spacing: 2px;"></div>
        </div>
    </div>
    <script>
    /**
     * 为指定的元素创建一个独立的倒计时器
     * Creates an independent countdown timer for a specific element
     * @param {string} elementId - 显示倒计时的元素 ID
     * @param {string} targetDate - 目标日期 'YYYY-MM-DD HH:MM:SS'
     */
    function createCountdown(elementId, targetDate) {
      const timerElement = document.getElementById(elementId);
      if (!timerElement) return; // 确保元素存在
      const targetTime = new Date(targetDate).getTime();
      const intervalId = setInterval(() => {
        const currentTime = new Date().getTime();
        const difference = targetTime - currentTime;
        if (difference <= 0) {
          timerElement.innerHTML = "目标日期已到达！";
          clearInterval(intervalId);
          return;
        }
        const days = Math.floor(difference / (1000 * 60 * 60 * 24));
        const hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        const minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
        const seconds = Math.floor((difference % (1000 * 60)) / 1000);
        timerElement.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
      }, 1000);
      // 立即执行一次以避免页面初次加载时空白一秒
      // Run once immediately to avoid a one-second blank state on page load
       (function runOnce() {
         const currentTime = new Date().getTime();
         const difference = targetTime - currentTime;
         if (difference > 0) {
           const days = Math.floor(difference / (1000 * 60 * 60 * 24));
           const hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
           const minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
           const seconds = Math.floor((difference % (1000 * 60)) / 1000);
           timerElement.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
         } else {
           timerElement.innerHTML = "目标日期已到达！";
         }
       })();
    }
    // --- 初始化你的两个倒计时器 ---
    // --- Initialize your two countdown timers ---
    // 启动第一个倒计时器
    createCountdown('countdown-timer-1', '2025-12-07 08:00:00');
    // 启动第二个倒计时器
    createCountdown('countdown-timer-2', '2025-10-30 00:00:00');
    </script>
</body>


## 养成习惯

## 大目标