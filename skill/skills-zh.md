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
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/role/roles-zh">学术兼职</a>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/project/projects-zh">研究课题</a>
<div class="dropdown">
    <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publications-zh">出版记录</a>
    <div class="dropdown-menu">
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2025-zh">2025</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2024-zh">2024</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2023-zh">2023</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2022-zh">2022</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2021-zh">2021</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2020-zh">2020</a>
    </div>
</div>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/exchange/exchanges-zh">学术交流</a>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/honour/honours-zh">荣誉奖励</a>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/skill/skills-zh">专业技能</a>
<a>中文</a>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/skill/skills">English</a>
</div>

<div id="connection" class="connection">
    <a>姜育彦</a>
    <a>中国，甘肃，兰州</a>
    📧<a href="mailto:jiangyuyancite@163.com">jiangyuyancite@163.com</a>
    👨‍🎓 <a href="https://scholar.google.com/citations?user=QTCEilEAAAAJ">Google Scholar</a>
    <a>微信 & 📱: +86 13372007365</a>
</div>

## 专业技能

**1.** CET-6

**2.** 江苏省计算机等级考试二级 - 优秀

**3.** IOP 可信评审人认证  

**4.** 锐捷项目管理工程师

**5.** 信息安全 - 渗透测试工程师  
