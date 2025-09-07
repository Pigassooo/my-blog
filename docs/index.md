---
title: 欢迎来到我的博客
hide:
#   - navigation # 显示右
  - toc #显示左
  - footer
  - feedback
comments: false
hide_comment: true
---

<!-- ---
title: Home
hide:
  # - navigation # 显示右
  # - toc #显示左
  - footer
  - feedback
comments: false
---
# Home

<center><font color= "#4051b5" size="6" class="ml3">
"此时情绪此时天，无事小神仙"
</font></center>
<!--  “循此苦旅 以达星辰”
<script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>
 -->

<!-- <div class="red-box">
  <img src="https://s2.loli.net/2024/04/22/EU9eGydnI4HWzO2.jpg" class="flying-image" alt="Flying image">
</div> -->

<!-- 
<div id="rcorners2" >
  <div id="rcorners1">
    <body>
      <font color="#4351AF">
        <p class="p1"></p>
<script defer>
    function format(newDate) {
        var day = newDate.getDay();
        var y = newDate.getFullYear();
        var m =
            newDate.getMonth() + 1 < 10
                ? "0" + (newDate.getMonth() + 1)
                : newDate.getMonth() + 1;
        var d =
            newDate.getDate() < 10 ? "0" + newDate.getDate() : newDate.getDate();
        var h =
            newDate.getHours() < 10 ? "0" + newDate.getHours() : newDate.getHours();
        var min =
            newDate.getMinutes() < 10
                ? "0" + newDate.getMinutes()
                : newDate.getMinutes();
        var s =
            newDate.getSeconds() < 10
                ? "0" + newDate.getSeconds()
                : newDate.getSeconds();
        var dict = {
            1: "Monday",
            2: "Tuesday",
            3: "Wednesday",
            4: "Thursday",
            5: "Friday",
            6: "Saturday",
            0: "Sunday",
        };
        return (
            y +
            "/" +
            m +
            "/" +
            d +
            "  " +
            dict[day]
            +
            "   "
            +
            h +
            ":" +
            min +
            ":" +
            s
        );
    }
    var timerId = setInterval(function () {
        var newDate = new Date();
        var p1 = document.querySelector(".p1");
        if (p1) {
            p1.textContent = format(newDate);
        }
    }, 1000);
</script>
      </font>
    </body>
  </div>
  <ul>
    <li>Open articles by topic and table of contents</li>
    <ul>
      <li>For Mac/PC, please select the topic in the tab bar above and select the article in the catalog on the left.</li>
      <li>For PE, Please click the icon in the upper left corner to select topics and articles</li>
    </ul>
    <li>Search keywords to open articles</li>
    <li>
      If you encounter web page lags/images that cannot be displayed after opening an article, please use <strong> VPN </strong> to break information barriers.
    </li>
  </ul>
</div>

<body>
    <font color="#B9B9B9">
    <p style="text-align: center; ">
        <span>This site has been running for</span>
        <span id='box1'></span>
    </p>
    <div id="box1"></div>
    <script>
    function timingTime(){
      let start = '2024-04-20 00:00:00'
      let startTime = new Date(start).getTime()
      let currentTime = new Date().getTime()
      let difference = currentTime - startTime
      let m =  Math.floor(difference / (1000))
      let mm = m % 60  // 秒
      let f = Math.floor(m / 60)
      let ff = f % 60 // 分钟
      let s = Math.floor(f/ 60) // 小时
      let ss = s % 24
      let day = Math.floor(s  / 24 ) // 天数
      return day + "days " + ss + "h " + ff + "min " + mm +'s'
    }
    setInterval(()=>{
      document.getElementById('box1').innerHTML = timingTime()
    },1000)
    </script>
  </font>
</body> -->

<!-- /***
 *      ┌─┐       ┌─┐
 *   ┌──┘ ┴───────┘ ┴──┐
 *   │                 │
 *   │       ───       │
 *   │   >        <    │
 *   │                 │
 *   │   ...  ⌒  ...   │
 *   │                 │
 *   └───┐         ┌───┘
 *       │         │
 *       │         │
 *       │         │
 *       │         └──────────────┐
 *       │                        │
 *       │                        ├─┐
 *       │                        ┌─┘
 *       │                        │
 *       └─┐  ┐  ┌───────┬──┐  ┌──┘
 *         │ ─┤ ─┤       │ ─┤ ─┤
 *         └──┴──┘       └──┴──┘
 *                神兽保佑
 *               代码无BUG!
 */ -->


<!-- 在头部添加预加载关键资源 -->
<link rel="preload" href="https://pic4.zhimg.com/v2-a0456a5f527c1923f096759f2926012f_1440w.jpg" as="image" fetchpriority="high">
<link rel="preload" href="https://s1.imagehub.cc/images/2025/07/25/27c0e105ea7efbed5d046d3a8c303e9d.jpeg" as="image">
<!-- https://picx.zhimg.com/v2-fb22186d2490043435a72876950492f5_1440w.jpg -->
<!-- orion-header.html -->
<div class="orion-header-row">
  <!-- 左侧：文字内容 -->
  <div class="orion-header-text">
    <div class="orion-header-title">Orion Pigasso</div>
    <div class="orion-header-subtitle">
      <span class="orion-header-subtitle-inner">
        UNSW undergraduate student
        <svg width="280" height="18" class="orion-header-underline" xmlns="http://www.w3.org/2000/svg">
          <path d="M8,12 Q38,18 68,12 Q98,6 128,12 Q158,18 188,12 Q218,6 248,12 Q278,18 308,12"
            stroke="#6ecbff" stroke-width="5" fill="none"
            stroke-linecap="round" stroke-linejoin="round"
            style="filter: blur(0.2px); opacity: 0.85;" />
        </svg>
      </span>
    </div>
    <!-- <div class="orion-header-motto">Free and diffuse</div> -->
    <div class="orion-header-btns">
      <a href="https://github.com/Pigassooo" target="_blank" class="orion-header-btn">Github</a>
      <a href="zfzf1219632665@gmail.com" class="orion-header-btn">Contact me</a>
    </div>
  </div>
  <!-- 右侧：头像及光辉 -->
  <div class="orion-header-avatar">
    <div class="flip-glow-ultimate">
      <div class="flip-glow-ultimate-glow"></div>
      <div class="flip-glow-ultimate-imgs">
        <img src="https://pic4.zhimg.com/v2-a0456a5f527c1923f096759f2926012f_1440w.jpg" alt="Back Image" class="flip-glow-ultimate-back" loading="eager" fetchpriority="high" width="280" height="280">
        <img src="https://s1.imagehub.cc/images/2025/07/25/27c0e105ea7efbed5d046d3a8c303e9d.jpeg" alt="Front Image" class="flip-glow-ultimate-front" loading="lazy" width="280" height="280">
      </div>
    </div>
  </div>
</div>

<!-- 移动端显示的标语 -->
<div class="mobile-motto">
  <h1>循此苦旅 以达星辰</h1>
</div>

<style>
/* ====== 布局主容器 ====== */
.orion-header-row {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 64px;
  margin: 48px 0 32px 0;
  flex-wrap: wrap;
  min-height: 320px;
}

/* ====== 左侧文字区 ====== */
.orion-header-text {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  min-width: 260px;
  max-width: 420px;
  flex: 1 1 320px;
  padding: 0 8px;
}

.orion-header-title {
  font-size: 3.2rem;
  /* font-family: 'LXGW WenKai', 'Segoe UI', 'PingFang SC', 'Hiragino Sans', Arial, sans-serif; */
  font-weight: 800;
  letter-spacing: 2px;
  margin-bottom: 18px;
  background: linear-gradient(to right, #3a8dde, #6ecbff, #a2d8ff);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-fill-color: transparent;
  display: flex;
  align-items: center;
  text-shadow: 0 2px 10px rgba(106, 203, 255, 0.13);
}

.orion-header-subtitle {
  font-size: 1.7rem;
  font-weight: bold;
  color: #222;
  position: relative;
  margin-bottom: 22px;
  /* font-family: 'LXGW WenKai', 'Segoe UI', 'PingFang SC', Arial, sans-serif; */
  line-height: 1.3;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  white-space: nowrap; /* 防止文本换行 */
}

.orion-header-subtitle-inner {
  color: #757575;
  position: relative;
  display: inline-block;
  padding-bottom: 10px;
  letter-spacing: 0.5px;
  white-space: nowrap; /* 确保文本不会换行 */
  width: auto; /* 确保宽度自适应内容 */
}

/* Safari特定修复 */
@media not all and (min-resolution:.001dpcm) { 
  @supports (-webkit-appearance:none) {
    .orion-header-subtitle-inner {
      display: inline-block;
      width: auto !important;
      min-width: 280px; /* 确保足够宽度容纳文本 */
    }
  }
}

/* 添加深色模式的文字颜色适配 - 更强烈的对比度 */
@media (prefers-color-scheme: dark) {
  .orion-header-subtitle {
    color: #757575;
  }
  
  .orion-header-subtitle-inner {
    color: #757575;
    text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5) !important; /* 增强阴影 */
  }
  
  .orion-header-motto {
    color: #d0d0d0 !important; /* 更亮的灰色 */
  }
  
  /* 确保SVG波浪线在深色模式下可见 */
  .orion-header-underline path {
    stroke: #6ecbff !important; /* 确保波浪线颜色鲜明 */
    opacity: 1 !important;
  }
}

.orion-header-underline {
  position: absolute;
  left: 0;
  bottom: 0;
  pointer-events: none;
}

.orion-header-motto {
  /* font-family: 'LXGW WenKai', sans-serif; */
  font-size: 1.2rem;
  color: #757575;
  letter-spacing: 1px;
  font-weight: 500;
  margin-bottom: 22px;
  opacity: 0.92;
}

.orion-header-btns {
  display: flex;
  gap: 18px;
  margin-top: 8px;
}

.orion-header-btn {
  display: inline-block;
  padding: 7px 22px;
  font-size: 1.08rem;
  font-weight: 500;
  color: #3a8dde;
  background: #f5faff;
  border: 1.5px solid #b6eaff;
  border-radius: 24px;
  text-decoration: none;
  transition: background 0.2s, color 0.2s, border 0.2s;
  box-shadow: 0 2px 8px rgba(106, 203, 255, 0.07);
}
.orion-header-btn:hover {
  background: #e6f4ff;
  color: #222;
  border-color: #3a8dde;
}

/* 夜间模式按钮样式 */
@media (prefers-color-scheme: dark) {
  .orion-header-btn {
    color: #6ecbff;
    background: rgba(30, 41, 59, 0.8);
    border-color: rgba(110, 203, 255, 0.4);
    box-shadow: 0 2px 8px rgba(106, 203, 255, 0.1);
  }
  
  .orion-header-btn:hover {
    background: rgba(110, 203, 255, 0.15);
    color: #ffffff;
    border-color: #6ecbff;
  }
}

/* 为使用 data-md-color-scheme 的主题添加支持 */
[data-md-color-scheme="slate"] .orion-header-btn {
  color: #6ecbff;
  background: rgba(30, 41, 59, 0.8);
  border-color: rgba(110, 203, 255, 0.4);
  box-shadow: 0 2px 8px rgba(106, 203, 255, 0.1);
}

[data-md-color-scheme="slate"] .orion-header-btn:hover {
  background: rgba(110, 203, 255, 0.15);
  color: #ffffff;
  border-color: #6ecbff;
}

/* ====== 右侧头像区 ====== */
.orion-header-avatar {
  display: flex;
  align-items: center;
  justify-content: center;
  min-width: 240px;
  flex: 0 0 280px;
}

.flip-glow-ultimate {
  position: relative;
  width: 280px;
  height: 280px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: center;
}

.flip-glow-ultimate-glow {
  position: absolute;
  top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  width: 320px; height: 320px; /* 从360px减小到320px */
  border-radius: 50%;
  pointer-events: none;
  z-index: 0;
  background:
    radial-gradient(circle at 60% 40%, rgba(255,255,255,0.25) 0%, rgba(255,255,255,0.08) 60%, transparent 100%),
    conic-gradient(from 0deg,
      #ff9edb 0%, #a2d8ff 20%, #a8ffb0 40%, #fff5a8 60%, #ffb0b0 80%, #ff9edb 100%
    );
  filter: blur(50px) brightness(1.1) saturate(1.2); /* 减小模糊半径和亮度 */
  opacity: 0.85; /* 降低不透明度 */
  animation: 
    glow-ultimate-rotate 15s linear infinite, 
    glow-ultimate-breath 5s ease-in-out infinite alternate,
    glow-ultimate-hue 25s linear infinite;
}

@keyframes glow-ultimate-rotate {
  0% { background-position: 0% 50%; }
  100% { background-position: 100% 50%; }
}
@keyframes glow-ultimate-breath {
  0% { opacity: 0.7; filter: blur(50px) brightness(1.05) saturate(1.1); transform: translate(-50%, -50%) scale(0.92);}
  50% { opacity: 0.85; filter: blur(55px) brightness(1.15) saturate(1.25); transform: translate(-50%, -50%) scale(1.0);}
  100% { opacity: 0.7; filter: blur(50px) brightness(1.05) saturate(1.1); transform: translate(-50%, -50%) scale(0.92);}
}

/* 为深色模式添加特定的光辉调整 */
@media (prefers-color-scheme: dark) {
  .flip-glow-ultimate-glow {
    width: 300px; height: 300px; /* 在深色模式下进一步减小 */
    filter: blur(45px) brightness(0.95) saturate(1.1); /* 降低亮度 */
    opacity: 0.75; /* 降低不透明度 */
  }
  
  @keyframes glow-ultimate-breath {
    0% { opacity: 0.65; filter: blur(45px) brightness(0.9) saturate(1.0); transform: translate(-50%, -50%) scale(0.9);}
    50% { opacity: 0.75; filter: blur(50px) brightness(1.0) saturate(1.15); transform: translate(-50%, -50%) scale(0.98);}
    100% { opacity: 0.65; filter: blur(45px) brightness(0.9) saturate(1.0); transform: translate(-50%, -50%) scale(0.9);}
  }
}

@keyframes glow-ultimate-hue {
  0% { filter: blur(60px) brightness(1.2) saturate(1.3) hue-rotate(0deg); }
  50% { filter: blur(60px) brightness(1.2) saturate(1.3) hue-rotate(20deg); }
  100% { filter: blur(60px) brightness(1.2) saturate(1.3) hue-rotate(0deg); }
}

.flip-glow-ultimate-imgs {
  position: relative;
  width: 280px;
  height: 280px;
  perspective: 1200px;
  z-index: 2;
}
.flip-glow-ultimate-imgs img {
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid #fff;
  box-shadow: 0 8px 24px rgba(14, 30, 37, 0.15), 0 0 0 1px rgba(255, 255, 255, 0.2);
  backface-visibility: hidden;
  transition: transform 1.2s cubic-bezier(.4,2,.6,1), box-shadow 0.3s ease;
  background: #fff;
}
.flip-glow-ultimate-imgs img.flip-glow-ultimate-back {
  z-index: 1;
  transform: rotateY(0deg);
}
.flip-glow-ultimate-imgs img.flip-glow-ultimate-front {
  z-index: 0;
  transform: rotateY(180deg);
}
.flip-glow-ultimate-imgs:hover img.flip-glow-ultimate-back {
  transform: rotateY(180deg);
  z-index: 2;
  box-shadow: 0 12px 32px rgba(14, 30, 37, 0.25);
}
.flip-glow-ultimate-imgs:hover img.flip-glow-ultimate-front {
  transform: rotateY(0deg);
  z-index: 3;
  box-shadow: 0 12px 32px rgba(14, 30, 37, 0.25);
}

/* ====== 响应式布局 ====== */
@media (max-width: 1100px) {
  .orion-header-row {
    gap: 32px;
  }
  .orion-header-title {
    font-size: 2.2rem;
  }
  .flip-glow-ultimate,
  .flip-glow-ultimate-imgs {
    width: 200px;
    height: 200px;
  }
  .flip-glow-ultimate-glow {
    width: 260px;
    height: 260px;
  }
}
@media (max-width: 700px) {
  .orion-header-row {
    flex-direction: column-reverse;
    gap: 0px; /* 减少到最小间距 */
    min-height: unset;
    margin: 12px 0 12px 0; /* 减小上下边距 */
  }
  .orion-header-text {
    align-items: center;
    text-align: center;
    max-width: 98vw;
    margin-top: -10px; /* 添加负边距拉近与头像的距离 */
  }
  .orion-header-avatar {
    margin-bottom: 0px; /* 移除底部间距 */
  }
  .orion-header-title {
    margin-bottom: 12px; /* 减小标题下方间距 */
  }
  .orion-header-subtitle {
    margin-bottom: 16px; /* 减小副标题下方间距 */
  }
  .orion-header-motto {
    margin-bottom: 16px; /* 减小座右铭下方间距 */
  }
  
  /* 调整头像大小，使其在移动端更小 */
  .flip-glow-ultimate,
  .flip-glow-ultimate-imgs {
    width: 220px;
    height: 220px;
  }
  .flip-glow-ultimate-glow {
    width: 220px;
    height: 220px;
  }
}
/* 添加一个额外的样式类，可以直接应用到元素上 */
.dark-visible-text {
  color: #ffffff !important;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5) !important;
}

/* 移动端样式 */
.mobile-motto {
  display: none;
  text-align: center;
  padding: 15px 0;
  margin: 10px 0;
}

.mobile-motto h1 {
  font-size: 1.8rem;
  color: #757575;
  /* font-family: 'LXGW WenKai', 'Segoe UI', 'PingFang SC', Arial, sans-serif; */
  font-weight: 500;
  margin: 0;
}

@media (max-width: 700px) {
  /* 隐藏原有头部 */
  .orion-header-row {
    display: none !important;
  }
  
  /* 显示移动端标语 */
  .mobile-motto {
    display: block;
  }
}
</style>


<!-- 移除这个换行符，它会产生额外的空间 -->
<!-- <br class="desktop-only"/> -->

<!-- 修改分隔线上下的间距 -->
<style>
/* 默认显示换行 */
/* .desktop-only {
  display: none; 
} */

/* 减少分隔线的边距 */
hr {
  margin: 0.5rem 0 !important;
}

/* 减少卡片网格的间距 */
.grid.cards {
  margin-top: 0 !important;
  margin-bottom: 0 !important;
}

/* 减少卡片内部的间距 */
.grid.cards > ul > li {
  padding: 0.8rem !important;
}

/* 减少卡片之间的间距 */
.grid.cards > ul {
  gap: 0.5rem !important;
}

/* 减少问候框的边距 */
#greeting {
  margin-bottom: 10px !important;
  padding: 8px !important;
}
</style>

---

<div id="greeting" class="greeting-container">
  <span id="greeting-text" class="greeting-text">加载中...</span>
</div>

<style>
  .greeting-container {
    text-align: center;
    margin-bottom: 20px;
    padding: 15px;
    border-radius: 10px;
    background-color: rgba(240, 240, 240, 0.5);
    border: 1px solid rgba(200, 200, 200, 0.3);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
    transition: all 0.3s ease;
  }
  
  .greeting-text {
    font-size: 1.5rem;
    font-weight: bold;
    color: #555;
    /* font-family: 'LXGW WenKai', sans-serif; */
    /* 添加最小高度避免布局抖动 */
    min-height: 1.5rem;
  }
  
  /* 夜间模式适配 */
  [data-md-color-scheme="slate"] .greeting-container {
    background-color: rgba(30, 41, 59, 0.6);
    border-color: rgba(80, 100, 140, 0.2);
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.15);
  }
  
  [data-md-color-scheme="slate"] .greeting-text {
    color: #e0e0e0;
  }
  
  /* 响应式调整 */
  @media (max-width: 768px) {
    .greeting-container {
      padding: 10px;
      margin-bottom: 15px;
    }
    
    .greeting-text {
      font-size: 1.3rem;
    }
  }
</style>

<script>
  // 优化的问候函数
  function updateGreeting() {
    const greetingElement = document.getElementById('greeting-text');
    if (!greetingElement) {
      // 如果元素不存在，延迟重试
      setTimeout(updateGreeting, 100);
      return;
    }

    const hour = new Date().getHours();
    let greeting;
    
    if (hour >= 0 && hour < 5) {
      greeting = "夜深了，注意休息 🌙";
    } else if (hour >= 5 && hour < 7) {
      greeting = "早安，新的一天开始啦 🌅";
    } else if (hour >= 7 && hour < 9) {
      greeting = "早上好，开始美好的一天 ☀️";
    } else if (hour >= 9 && hour < 11) {
      greeting = "上午好，保持专注 ✨";
    } else if (hour >= 11 && hour < 13) {
      greeting = "中午好，该休息一下了 🍲";
    } else if (hour >= 13 && hour < 15) {
      greeting = "午后时光，继续加油 ☕";
    } else if (hour >= 15 && hour < 18) {
      greeting = "下午好，别忘了喝水 🌤️";
    } else if (hour >= 18 && hour < 20) {
      greeting = "傍晚好，放松一下吧 🌆";
    } else if (hour >= 20 && hour < 22) {
      greeting = "晚上好，享受宁静时光 🌃";
    } else {
      greeting = "夜深了，早点休息哦 🌠";
    }
    
    greetingElement.textContent = greeting;
  }

  // 多重保险的初始化
  if (document.readyState === 'loading') {
    document.addEventListener('DOMContentLoaded', updateGreeting);
  } else {
    // DOM 已经加载完成
    updateGreeting();
  }

  // 额外的后备方案
  if (document.getElementById('greeting-text')) {
    updateGreeting();
  } else {
    // 如果元素还没有加载，等待一下
    setTimeout(updateGreeting, 200);
  }
</script>

---

<div class="grid cards" markdown>

-   :material-notebook-edit-outline:{ .lg .middle } __导航栏__

    ---
    ![image](https://pic1.zhimg.com/80/v2-b9ae6898d33359da6be815bf60626af2_1440w.webp?source=2c26e567){ class="responsive-image" loading="lazy" align=right width="340" height="226" style="border-radius: 2.5em 1.5em 3em 2em / 2em 2.5em 1.5em 3em;" }

    - [x] 通过{==目录==}以打开文章
    - [x] 搜索{~~~>关键词~~}查询文章
    - [x] 如遇页面卡顿，请使用{--科学上网--}
    - [x] 𝕙𝕒𝕧𝕖 𝕒 𝕘𝕠𝕠𝕕 𝕥𝕚𝕞𝕖 !  

    === "Mac/PC端"

        请在上方标签选择分类/左侧目录选择文章

    === "移动端"

        请点击左上角图标选择分类和文章
    
</div>
<style>
    @media only screen and (max-width: 768px) {
        .responsive-image {
            display: none;
        }
    }
</style>


*** 


[^Knowing-that-loving-you-has-no-ending]:太阳总是能温暖向日葵  
[^see-how-much-I-love-you]:All-problems-in-computer-science-can-be-solved-by-another-level-of-indirection

<style>
.md-grid {
  max-width: 1220px;
}
</style>


<style>
body {
  position: relative; /* 确保 body 元素的 position 属性为非静态值 */
}

body::before {
  --size: 35px; /* 调整网格单元大小 */
  --line: color-mix(in hsl, canvasText, transparent 80%); /* 调整线条透明度 */
  content: '';
  height: 100vh;
  /* width: 100%; */
  width: 100vw;
  position: absolute; /* 修改为 absolute 以使其随页面滚动 */
  background: linear-gradient(
        90deg,
        var(--line) 1px,
        transparent 1px var(--size)
      )
      50% 50% / var(--size) var(--size),
    linear-gradient(var(--line) 1px, transparent 1px var(--size)) 50% 50% /
      var(--size) var(--size);
  -webkit-mask: linear-gradient(-20deg, transparent 50%, white);
          mask: linear-gradient(-20deg, transparent 50%, white);
  top: 0;
  transform-style: flat;
  pointer-events: none;
  z-index: -1;
}

@media (max-width: 768px) {
  body::before {
    display: none; /* 在手机端隐藏网格效果 */
  }
}
</style>

<!-- 
  将所有页面级脚本和元数据统一放置在这里 
-->
<head> 
  <!-- Umami Analytics -->
  <script defer src="https://cloud.umami.is/script.js" data-website-id="061b4dea-9b7b-4ffa-9071-74cde70f3dfb"></script>
</head>
  <!-- Google Adsense -->
  <!-- <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-2327435979273742"
     crossorigin="anonymous"></script>
</head> -->

<!-- 
  Google Adsense 广告单元
  (如果需要，可以取消注释)
-->
<!-- 
<ins class="adsbygoogle"
    style="display:block"
    data-ad-client="ca-pub-2327435979273742"
    data-ad-slot="3702206121"
    data-ad-format="auto"
    data-full-width-responsive="true"></ins>
<script>
    (adsbygoogle = window.adsbygoogle || []).push({});
</script>
-->

<!-- [timeline(./docs/timeline/timeindex.json)] -->

<!-- <script type="text/javascript">
    (function(c,l,a,r,i,t,y){
        c[a]=c[a]||function(){(c[a].q=c[a].q||[]).push(arguments)};
        t=l.createElement(r);t.async=1;t.src="https://www.clarity.ms/tag/"+i;
        y=l.getElementsByTagName(r)[0];y.parentNode.insertBefore(t,y);
    })(window, document, "clarity", "script", "sks5yth4qj");
</script> -->


<meta name="algolia-site-verification"  content="3CAAB2C27102AD08" />

<body>
    <font color="#B9B9B9">
    <p style="text-align: center; ">
        <span>This site has been running for</span>
        <span id='box1'></span>
    </p>
    <div id="box1"></div>
    <script>
    function timingTime(){
      let start = '2024-04-20 00:00:00'
      let startTime = new Date(start).getTime()
      let currentTime = new Date().getTime()
      let difference = currentTime - startTime
      let m =  Math.floor(difference / (1000))
      let mm = m % 60  // 秒
      let f = Math.floor(m / 60)
      let ff = f % 60 // 分钟
      let s = Math.floor(f/ 60) // 小时
      let ss = s % 24
      let day = Math.floor(s  / 24 ) // 天数
      return day + "days " + ss + "h " + ff + "min " + mm +'s'
    }
    setInterval(()=>{
      document.getElementById('box1').innerHTML = timingTime()
    },1000)
    </script>
  </font>
</body>