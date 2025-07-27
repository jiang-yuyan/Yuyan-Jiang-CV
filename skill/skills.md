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
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/role/roles">Academic Role</a>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/project/projects">Research Project</a>
<div class="dropdown">
    <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publications">Publications</a>
    <div class="dropdown-menu">
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2025">2025</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2024">2024</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2023">2023</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2022">2022</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2021">2021</a>
        <a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publication-2020">2020</a>
    </div>
</div>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/exchange/exchanges">Academic Exchange</a>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/honour/honours">Honour</a>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/skill/skills">Professional Skills</a>
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/skill/skills-zh">中文（更新中）</a>
<a>English</a>
</div>

## Professional Skills

**1.** English CET-6

**2.** Jiangsu Province Computer Level 2 - Excellent

**3.** IOP Trusted Reviewer Certification

**4.** Project Management Engineer (RSE-PM)

**5.** Information Security - Penetration Test Engineer (CISP-PTE)
