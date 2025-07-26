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
    <a href="./publication/publications">Publications</a>
    <div class="dropdown-menu">
        <a href="./publication/publications-2025">2025</a>
        <a href="./publication/publications-2024">2024</a>
        <a href="./publication/publications-2023">2023</a>
        <a href="./publication/publications-2022">2022</a>
        <a href="./publication/publications-2021">2021</a>
        <a href="./publication/publications-2020">2020</a>
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



<div style="display: flex; margin-bottom: 30px;">
  <!-- 左侧头像区域 -->
    <div style="flex: 0 0 300px; margin-right: 60px;">
        <img src="cat.jpeg" style="width: 300px; height: 300px; object-fit: cover;">
    </div>
  <!-- 右侧个人简介区域 -->
    <div style="flex: 1; display: flex; flex-direction: column; justify-content: center;">
        <h2 style="margin-top: 0;">Yuyan Jiang</h2>
        <p><strong>Not a cat, but a PhD student!</strong></p>
    </div>
</div>

---
  
&#8195;&#8195;I am a researcher specialising in information science and am currently pursuing my PhD Degree in Information Science at the University of Chinese Academy of Sciences (2024-2027). Prior to that, I received my MPhil in Management (Library Information and Records Management, 2021-2024) and BSc in Management (Information Management and Information System, 2017-2021) from Henan Medical University and Nanjing University Jinling College, respectively.  

&#8195;&#8195;My research interests cover a number of cutting-edge areas, mainly focusing on scientometrics, journal publishing, open science and scientific data management. Meanwhile, I am also deeply concerned with peer review and research ethics issues, and committed to promoting academic integrity. In addition, I am actively exploring digital humanities and digital library construction, with special attention to the innovative development of reading promotion activities.  

&#8195;&#8195;Through my interdisciplinary learning background and diversified research directions, I hope to make meaningful contributions to the field of information science and promote the modern development of academic communication and knowledge dissemination.  

