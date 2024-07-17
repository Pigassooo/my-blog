---
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

<div class="red-box">
  <img src="https://s2.loli.net/2024/04/22/EU9eGydnI4HWzO2.jpg" class="flying-image" alt="Flying image">
</div>

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
</body>


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