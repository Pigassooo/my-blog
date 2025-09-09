# Plans

## 一天时间安排
（按重要性优先级排列）
1. 
2. 


## 短期目标
- 日语冲刺N2 DDL: 12.7

<body>
    <div style="text-align: center; color: #555; font-family: sans-serif; font-size: 1.2em;">
        <p>
            <span>距离目标日期还剩</span>
            <br>
            <span>Time remaining until the target date:</span>
        </p>
        <div id="countdown-timer" style="font-weight: bold; font-size: 1.5em; color: #000; margin-top: 10px;"></div>
    </div>
    <script>
    function updateCountdown() {
      const targetDate = '2026-12-07 08:00:00'; // 设置你的目标日期和时间
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
</body>


## 养成习惯

## 大目标