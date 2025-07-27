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
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/index">English</a>
</div>

<div id="connection" class="connection">
    <a>姜育彦</a>
    <a>中国，甘肃，兰州</a>
    📧<a href="mailto:jiangyuyancite@163.com">jiangyuyancite@163.com</a>
    👨‍🎓 <a href="https://scholar.google.com/citations?user=QTCEilEAAAAJ">Google Scholar</a>
    <a>微信 & 📱: +86 13372007365</a>
</div>

## 荣誉奖励

| 奖项 | 年度 | 来源 |
| :-: | :-: | :-: |
| 国家奖学金 | 2023 | 中华人民共和国教育部 |
| 河南省创新之星 | 2024 | 河南省教育厅 |
| 优秀毕业研究生 | 2024 | 河南省教育厅 |
| **First Prize of Scholarship** | 2022 | 河南省教育厅 |
| **First Prize of Scholarship** | 2022 | 河南省教育厅 |
| 校创新之星 | 2024 | 河南医药大学 |
| 校优秀论文 | 2024 | 河南医药大学 |
| **First Prize of Academic Star** | 2023 | Xinxiang Medical University |
| **First Prize of University Scholarship** | 2022 | Xinxiang Medical University |
| **Outstanding Postgraduate Student** | 2022 | Xinxiang Medical University |
| **Outstanding Postgraduate Student** | 2021 | Xinxiang Medical University |
| **Outstanding Postgraduate Student** | 2021 | Xinxiang Medical University |
| **Third Prize of People Scholarship** | 2021 | Nanjing University Jinling College |
| **Single Prize of People Scholarship** | 2020 | Nanjing University Jinling College |
| **First Prize of Academic Star** | 2023 | Henan Research Center for Science Journals |
| **Outstanding Readers** | 2021 | Library of Nanjing University Jinling College |
| 优秀论文三等奖 | 2024 | The 7th Conference on Quality and Development of Chinese Journals |
| 优秀论文一等奖 | 2023 | The 14th National Symposium on Scientometrics & Science and Education Evaluation |
| 优秀论文三等奖 | 2023 | The 6th Tianfu Forum on Scientometrics and Scientific Evaluation |
| 三等奖 | 2019 | The 10th Blue Bridge Cup C/C++ Programming of Jiangsu Province |
| 三等奖 | 2018 | The 9th Blue Bridge Cup C/C++ Programming of Jiangsu Province |
