<style>
    /* 设置导航栏固定在页面顶部 */
    .navigation {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background-color: white;
        z-index: 1000;
        padding: 10px;
        border-bottom: 1px solid #ccc;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 10px; /* 统一设置元素间距 */
    }
    
    /* 添加分隔符样式 */
    .navigation a:not(:last-child)::after {
        content: " | ";
        margin-left: 10px;
        color: #666;
    }
    
    /* 为页面主体添加顶部内边距，避免内容被导航栏遮挡 */
    body {
        padding-top: 60px;
        padding-bottom: 60px;
    }

    /* 设置底部连接栏固定在页面底部 */
    .connection {
        position: fixed;
        bottom: 0;
        left: 0;
        width: 100%;
        background-color: white;
        z-index: 1000;
        padding: 10px;
        border-top: 1px solid #ccc;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 10px; /* 统一设置元素间距 */
    }

    .connection a:not(:last-child)::after {
        content: " | ";
        margin-left: 10px;
        color: #666;
    }

    /* 下拉菜单样式 */
    .dropdown {
        position: relative;
        display: inline-block;
    }

    .dropdown-menu {
        display: none;
        position: absolute;
        background-color: white;
        min-width: 100px;
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
        z-index: 1001;
        border: 1px solid #ccc;
        top: 100%;
        left: 0;
    }

    .dropdown-menu a {
        color: black;
        padding: 8px 12px;
        text-decoration: none;
        display: block;
        font-size: 14px;
    }

    .dropdown-menu a:hover {
        background-color: #f1f1f1;
    }

    .dropdown:hover .dropdown-menu {
        display: block;
    }

    .dropdown-menu a::after {
        content: none !important;
    }
</style>

<div class="navigation">
<a href="#education">Education</a>
<a href="#research-direction">Research Direction</a>
<a href="#academic-role">Academic Role</a>
<a href="#research-project">Research Project</a>
<div class="dropdown">
    <a href="./publications">Publications</a>
    <div class="dropdown-menu">
        <a href="#publications-2025">2025</a>
        <a href="#publications-2024">2024</a>
        <a href="#publications-2023">2023</a>
        <a href="#publications-2022">2022</a>
        <a href="#publications-2021">2021</a>
        <a href="#publications-2020">2020</a>
    </div>
</div>
<a href="#academic-exchange">Academic Exchange</a>
<a href="#honour">Honour</a>
<a href="#professional-skills">Professional Skills</a>
<a href="./index-zh">中文（更新中）</a>
<a>English</a>
</div>

<div id="connection" class="connection">
    <a>Yuyan Jiang</a>
    <a>Lanzhou, Gansu, China</a>
    📧<a href="mailto:jiangyuyancite@163.com">jiangyuyancite@163.com</a>
    👨‍🎓 <a href="https://scholar.google.com/citations?user=QTCEilEAAAAJ">Google Scholar</a>
    <a>WeChat & 📱: +86 13372007365</a>
</div>

<div style="display: flex; align-items: flex-start; gap: 20px; margin: 20px 0;">
  <!-- 左侧图像区域 -->
  <div style="flex-shrink: 0;">
    <img src="https://github.com/你的用户名.png"  style="width: 300px; height: 300px; border-radius: 50%; object-fit: cover; border: 3px solid #e1e4e8;">
  </div>
  
  <!-- 右侧个人简介区域 -->
  <div style="flex: 1; min-width: 0;">
    <h2 style="margin-top: 0; color: #0366d6;">张三</h2>
    <h3 style="color: #586069; font-weight: normal;">全栈开发工程师</h3>
    
    <p style="line-height: 1.6; color: #24292e;">
      👋 你好！我是一名热爱技术的开发者，专注于Web开发和人工智能领域。拥有5年的软件开发经验，熟练掌握JavaScript、Python、React等技术栈。
    </p>
    
    <div style="margin: 15px 0;">
      <strong>技能专长：</strong><br>
      • 前端开发：React, Vue.js, TypeScript<br>
      • 后端开发：Node.js, Python, Java<br>
      • 数据库：MySQL, MongoDB, Redis<br>
      • 云服务：AWS, Docker, Kubernetes
    </div>
