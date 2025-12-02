<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>壹米说电脑</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #0a1a2f;
      color: #e8f1ff;
      overflow-x: hidden;
    }

    /* 粒子背景容器 */
    #particles-js {
      position: fixed;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      z-index: -1;
      background: radial-gradient(ellipse at center, #0a1a2f 0%, #030b16 100%);
    }

    header {
      text-align: center;
      padding: 40px 20px;
      color: #fff;
    }

    header img.logo {
      width: 120px;
      height: auto;
      margin-bottom: 15px;
    }

    header h1 {
      margin: 0;
      font-size: 36px;
      letter-spacing: 2px;
    }

    header p {
      margin-top: 8px;
      font-size: 18px;
      opacity: 0.85;
    }

    .container {
      width: 92%;
      max-width: 1000px;
      margin: 20px auto;
    }

    .section {
      background: rgba(10, 30, 60, 0.6);
      backdrop-filter: blur(6px);
      border-radius: 14px;
      padding: 25px;
      margin-bottom: 35px;
      box-shadow: 0 8px 30px rgba(0,0,0,0.25);
      border: 1px solid rgba(255,255,255,0.06);
    }

    .section h2 {
      margin-top: 0;
      border-left: 5px solid #4da3ff;
      padding-left: 10px;
      font-size: 22px;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: rgba(255,255,255,0.06);
      padding: 20px;
      border-radius: 10px;
      transition: 0.2s;
      border: 1px solid rgba(255,255,255,0.08);
    }

    .card:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.25);
      background: rgba(255,255,255,0.12);
    }

    a {
      color: #4da3ff;
      text-decoration: none;
      font-weight: bold;
    }

    /* 二维码区 */
    .qrcode-box {
      text-align: center;
      margin-top: 25px;
    }

    .qrcode-box img {
      width: 180px;
      height: 180px;
      border-radius: 10px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.35);
    }

    .footer {
      text-align: center;
      padding: 20px;
      color: #88a4c7;
      margin-top: 40px;
      font-size: 14px;
    }
  </style>

  <!-- 粒子效果库 -->
  <script src="https://cdn.jsdelivr.net/npm/particles.js"></script>

</head>

<body>

  <div id="particles-js"></div>

  <header>
    <img src="images/微信图片_20250609201357.png" class="logo" alt="壹米说电脑 Logo" />
    <h1>壹米说电脑</h1>
    <p>专注电脑硬件｜系统技巧｜维修经验分享</p>
  </header>

  <div class="container">

    <div class="section">
      <h2>个人简介</h2>
      <p>从事电脑维修行业多年，坚持分享真实实用的电脑知识与技巧。</p>
    </div>

    <div class="section">
      <h2>技能特长</h2>

      <div class="skills">
        <div class="card">电脑维修</div>
        <div class="card">维修故事案例</div>
        <div class="card">硬件评测</div>
        <div class="card">
        <h3> 壹米说电脑工具箱</h3>
        <p>电脑维修检测、各种常用软件、定制工具箱</p>
        <a href="https://pan.baidu.com/s/1rs0AVBK9UjF9YFB-yZfFww?pwd=zhxc" target="_blank" rel="noopener noreferrer">网盘下载</a>
</div>
        <div class="card">
        <h3>软件技巧分享</h3>
        <p>壹米说电脑分享的软件合集</p>
        <a href="https://pan.baidu.com/s/5K19zjFNfDDXftIR3TrgSlA" target="_blank" rel="noopener noreferrer">知识库</a></div>
        <div class="card">系统重装与优化</div>
      </div>

    </div>

    <div class="section">
      <h2>精选项目</h2>

      <div class="projects">

        <div class="card">
          <h3>公众号</h3>
          <p>提供最新的维修技巧与硬件知识。</p>
          <a href="https://mp.weixin.qq.com/s/havu_WZ8Miv27NmwWuRsOw" target="_blank" rel="noopener noreferrer">查看文章</a>
        </div>

        <div class="card">
          <h3>今日头条号</h3>
          <p>发布电脑技术相关视频内容</p>
          <a href="https://www.toutiao.com/c/user/token/Cia_1cp4wTlFYV0nDzG1WckdQlQJQoI7aqen6BgMhWbgqGGSHtqUiRpJCjwAAAAAAAAAAAAAT791-tpl6KJg312RKFVizIbYlxK9n0ePMWFfIg7SNXzUANYlMEt0V4rIlV11SZb5v_oQ_6aCDhjDxYPqBCIBA9CBvLQ=/?source=list&log_from=ac989b9e65c1a_1763894140325" target="_blank" rel="noopener noreferrer">查看视频</a>
        </div>

        <div class="card">
          <h3>电脑维修服务</h3>
          <p>线上/线下全方位电脑维修服务</p>
          <p>1039696919@qq.com</p>
        </div>

      </div>
    </div>

    <!-- 二维码 section -->
    <div class="section qrcode-box">
      <h2>关注「壹米说电脑」公众号</h2>
      <img src="images/qrcode_for_gh_ea20302ac613_430.jpg" alt="公众号二维码" />
      <p style="margin-top: 10px;">获取更多电脑技巧与实用工具</p>
    </div>

  </div>

  <div class="footer">© 2025 壹米说电脑</div>

  <!-- 粒子配置 -->
  <script>
    particlesJS("particles-js", {
      "particles": {
        "number": { "value": 80 },
        "size": { "value": 3 },
        "color": { "value": "#4da3ff" },
        "line_linked": {
          "enable": true,
          "color": "#4da3ff",
          "opacity": 0.3
        },
        "move": { "speed": 2 }
      }
    });
  </script>

</body>
</html>





