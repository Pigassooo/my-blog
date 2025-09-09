# Plans

## 一天时间安排
（按重要性优先级排列）
1. 
2. 


## 短期目标
- 日语冲刺N2 DDL: 12.7
<!-- 
<body>
    <div style="text-align: center; color: #555; font-family: sans-serif; font-size: 1.2em;">
        <p>
            <span>距离目标日期还剩</span>
            <br>
        </p>
        <div id="countdown-timer" style="font-weight: bold; font-size: 1.5em; color: #000; margin-top: 10px;"></div>
    </div>
    <script>
    function updateCountdown() {
      const targetDate = '2025-12-07 08:00:00'; // 设置你的目标日期和时间
      // Set your target date and time here
      const targetTime = new Date(targetDate).getTime();
      const currentTime = new Date().getTime();
      // 计算时间差（未来时间 - 现在时间）
      // Calculate the difference (Future Time - Current Time)
      let difference = targetTime - currentTime;
      // 获取用于显示的元素
      // Get the element for display
      const timerElement = document.getElementById('countdown-timer');
      // 如果时间差小于或等于0，说明目标日期已到或已过
      // If the difference is less than or equal to 0, the target date has arrived or passed
      if (difference <= 0) {
        timerElement.innerHTML = "目标日期已到达！/ The target date has arrived!";
        // 停止定时器，不再更新
        // Stop the interval timer from running
        clearInterval(countdownInterval); 
        return; // 提前结束函数
      }
      // 将毫秒差转换为天、小时、分钟和秒
      // Convert millisecond difference into days, hours, minutes, and seconds
      let days = Math.floor(difference / (1000 * 60 * 60 * 24));
      let hours = Math.floor((difference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      let minutes = Math.floor((difference % (1000 * 60 * 60)) / (1000 * 60));
      let seconds = Math.floor((difference % (1000 * 60)) / 1000);
      // 格式化输出，例如：120d 5h 30m 15s
      // Format the output, for example: 120d 5h 30m 15s
      timerElement.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;
    }
    // 每秒钟调用一次 updateCountdown 函数来更新时间
    // Call the updateCountdown function once every second to update the time
    const countdownInterval = setInterval(updateCountdown, 1000);
    // 页面加载后立即执行一次，避免初始空白
    // Run it once immediately after the page loads to avoid initial blankness
    updateCountdown(); 
    </script>
</body> -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Countdown Timer</title>
    <style>
        /* 整个页面的背景色，让卡片更突出 */
        /* Background color for the whole page to make the card stand out */
        body {
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
        }
        /* 这是倒计时卡片的主容器 */
        /* This is the main container for the countdown card */
        .countdown-container {
            background-color: #ffffff; /* 卡片底色 */
            border: 1px solid #e0e0e0; /* 边框颜色 */
            border-radius: 12px;       /* 圆角边框 */
            padding: 30px 40px;        /* 内边距 (上下 左右) */
            text-align: center;
            color: #555;
            font-size: 1.2em;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08); /* 添加阴影，更有立体感 */
            width: 320px; /* 给一个固定宽度 */
        }
        /* 倒计时数字的样式 */
        /* Style for the countdown numbers */
        #countdown-timer {
            font-weight: bold;
            font-size: 2em; /* 放大数字 */
            color: #1a1a1a; /* 加深数字颜色 */
            margin-top: 10px;
            letter-spacing: 2px; /* 增加字符间距 */
        }
    </style>
</head>
<body>
    <div class="countdown-container">
        <p style="margin-top: 0;">
            <span>距离目标日期还剩</span>
        </p>
        <div id="countdown-timer"></div>
    </div>
    <script>
    function updateCountdown() {
      // 目标日期
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
</html>


## 养成习惯

## 大目标