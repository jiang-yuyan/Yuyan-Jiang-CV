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
<a href="https://jiang-yuyan.github.io/Yuyan-Jiang-CV/publication/publications-zh">中文（更新中）</a>
<a>English</a>
</div>

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

## Publications

<h3 id="publications-2025">·2025</h3>

[**Are Nature Index journals a valid basis for academic assessment: a study of academic impact and disruptive innovation assessment based on open bibliographic metadata and citation data**](https://www.nature.com/articles/s41599-025-05387-6)  
**Source**：*Humanities and Social Sciences Communications*    
**Year**：2025    
**Volume**：12    
**Issue**：1    
**Page**：1-10    
**Author**：__Jiang Y__, Ma J    
**Tag**：AHCI, SSCI, JIF = 3.6, CAS Q1, JCR Q1, JCI Q1  

[**Evaluation and Comparison of the Academic Quality of Open Access Mega Journals and Authoritative Journals: Disruptive Innovation Evaluation**](https://www.jmir.org/2025/1/e59598)  
**Source**：*Journal of Medical Internet Research*    
**Year**：2025    
**Volume**：27    
**Issue**：-    
**Page**：e59598    
**Author**：__Jiang Y__, Liu X, Wang L    
**Tag**：SCI, JIF = 6.0, CAS Q2 Top, JCR Q1, JCI Q1    

[**The disruptive innovation evaluation and empirical analysis of Chinese, Japanese, Indian and South Korean scientific journals**](https://utppublishing.com/doi/10.3138/jsp-2023-0056)  
**Source**：*Journal of Scholarly Publishing*    
**Year**：2025    
**Volume**：56    
**Issue**：1    
**Page**：60-78    
**Author**：__Jiang Y__, Liu X, Wang L    
**Tag**：AHCI, SSCI, JIF = 0.8, CAS Q2, JCR Q3, JCI Q1 

[**Journal Disruption Index Based on Citation Data Source Optimization and Its Empirical Study**](https://www.cjstp.cn/CN/10.11946/cjstp.202411071210)  
**Source**：*Chinese Journal of Scientific and Technical Periodicals*       
**Year**：2025    
**Volume**：36    
**Issue**：4    
**Page**：512-521    
**Author**：Liu X, __Jiang Y__#    
**Tag**：CSSCI, PKU, CSTPCD    

[**Beware of the Predatory Distortion of Journals in the Open Access Environment**](https://bjxb.cessp.org.cn/ch/reader/view_abstract.aspx?file_no=20250309&flag=1)  
**Source**：*Acta Editologica*     
**Year**：2025    
**Volume**：37    
**Issue**：3    
**Page**：272-277    
**Author**：Lu Y, __Jiang Y__, Zhang Y, Zheng J, Liu X, Fang H    
**Tag**：CSSCI, PKU, CSTPCD   

<h3 id="publications-2024">·2024</h3>

[**Evaluation and Comparison of Academic Impact and Disruptive Innovation Level of Medical Journals: Bibliometric Analysis and Disruptive Evaluation**](https://www.jmir.org/2024/1/e55121)  
**Source**：*Journal of Medical Internet Research*    
**Year**：2024    
**Volume**：26    
**Issue**：-    
**Page**：e55121    
**Author**：__Jiang Y__, Liu X, Wang L    
**Tag**：SCI, JIF = 5.8, CAS Q2 Top, JCR Q1, JCI Q1  

[**A new method of calculating the disruption index based on open citation data**](https://journals.sagepub.com/doi/abs/10.1177/01655515241263545)  
**Source**：*Journal of Information Science*    
**Year**：2024    
**Volume**：26    
**Issue**：-    
**Page**：01655515241263545 (Online First)    
**Author**：__Jiang Y__, Liu X    
**Tag**：SCI, JIF = 1.8, CAS Q4, JCR Q2, JCI Q2, AJG 2 Star 

[**Analysis of Characteristics and Reasons of Retracted Papers from Chinese Universities by International Journals**](https://www.cjstp.cn/CN/10.11946/cjstp.202409020964)  
**Source**：*Chinese Journal of Scientific and Technical Periodicals*     
**Year**：2024    
**Volume**：35    
**Issue**：12    
**Page**：1732-1743    
**Author**：Cao J, Gao J, __Jiang Y__, Zhou Z    
**Tag**：CSSCI, PKU, CSTPCD     

[**Effects of author's internationalization level on journal impact and disruptive innovation in China journals indexed in SCI**](https://www.cjstp.cn/CN/10.11946/cjstp.202405210538)  
**Source**：*Chinese Journal of Scientific and Technical Periodicals*    
**Year**：2024    
**Volume**：35    
**Issue**：11    
**Page**：1611-1618    
**Author**：Zhang Z, Yang X, Liu X, __Jiang Y__    
**Tag**：CSSCI, PKU, CSTPCD    

[**Dynamic changes in paper quantity and impact factor of SCI-indexed journals and influence of paper quantity on impact factor**](https://www.cjstp.cn/CN/10.11946/cjstp.202402130115)  
**Source**：*Chinese Journal of Scientific and Technical Periodicals*    
**Year**：2024    
**Volume**：35    
**Issue**：7    
**Page**：982-994    
**Author**：Wang L, Liu X, __Jiang Y__    
**Tag**：CSSCI, PKU, CSTPCD    

<h3 id="publications-2023">·2023</h3>

[**A construction and empirical research of the journal disruption index based on open citation data**](https://link.springer.com/article/10.1007/s11192-023-04737-y)  
**Source**：*Scientometrics*    
**Year**：2023    
**Volume**：128    
**Issue**：7    
**Page**：3935-3958    
**Author**：__Jiang Y__, Liu X    
**Tag**：SCI, JIF = 3.9, CAS Q3, JCR Q1, JCI Q1, AJG Star 2   

[**A Bibliometric Analysis and Disruptive Innovation Evaluation for the Field of Energy Securit**](https://www.mdpi.com/2071-1050/15/2/969)  
**Source**：*Sustainability*    
**Year**：2023    
**Volume**：15    
**Issue**：2    
**Page**：969    
**Author**：__Jiang Y__, Liu X    
**Tag**：SCI, JIF = 3.9, CAS Q3, JCR Q2, JCI Q2   

[**Innovative evaluation of Chinese SCIE-indexed scientific journals: An empirical study based on the disruption index**](https://www.cjstp.cn/CN/10.11946/cjstp.202302190096)  
**Source**：*Chinese Journal of Scientific and Technical Periodicals*    
**Year**：2023    
**Volume**：34    
**Issue**：8    
**Page**：1060-1068    
**Author**：__Jiang Y__, Wang L, Liu X    
**Tag**：CSSCI, PKU, CSTPCD    

[**Research progress on interdisciplinary evaluation indicators of scientific journals**](https://www.cjstp.cn/CN/10.11946/cjstp.202301130027)  
**Source**：*Chinese Journal of Scientific and Technical Periodicals*    
**Year**：2023    
**Volume**：34    
**Issue**：7    
**Page**：944-952    
**Author**：Zhang Y, __Jiang Y__, Fang H    
**Tag**：CSSCI, PKU, CSTPCD    

[**The relationship between absolute disruptive index, peer review index and CNCI: a study based on virology papers**](https://www.lis.ac.cn/CN/10.13266/j.issn.0252-3116.2023.03.009)  
**Source**：*Library and Information Service*    
**Year**：2023    
**Volume**：67    
**Issue**：3    
**Page**：96-105    
**Author**：__Jiang Y__, Liu X    
**Tag**：CSSCI, PKU, CSTPCD    

<h3 id="publications-2022">·2022</h3>

[**Open peer review: models, technologies, problems and countermeasures**](https://www.cjstp.cn/CN/10.11946/cjstp.202202280120)  
**Source**：*Chinese Journal of Scientific and Technical Periodicals*    
**Year**：2022    
**Volume**：33    
**Issue**：9    
**Page**：1196-1205    
**Author**：__Jiang Y__, Liu X    
**Tag**：CSSCI, PKU, CSTPCD    

[**An innovative evaluation index of scientific journals--Journal Disruption Index (JDI) and its empirical research**](https://www.cjstp.cn/CN/10.11946/cjstp.202205240418)  
**Source**：*Chinese Journal of Scientific and Technical Periodicals*    
**Year**：2022    
**Volume**：33    
**Issue**：7    
**Page**：965-972    
**Author**：__Jiang Y__, Liu X    
**Tag**：CSSCI, PKU, CSTPCD    

[**Protection and Rebirth of Microform Materials from the Perspective of Digital Humanities: Taking Digital Cicognara Library as an Example**](https://dlf.istic.ac.cn/dlf/ch/reader/view_abstract.aspx?file_no=202203007&flag=1)  
**Source**：*Digital Library Forum*    
**Year**：2022    
**Volume**：-    
**Issue**：3    
**Page**：47-52    
**Author**：__Jiang Y__, Liu X    
**Tag**：CSSCI(E), CSTPCD    

[**A new model for promoting reading based on word segmentation indexing of collection titles**]()  
**Source**：*Digital & Micrographic Imaging*    
**Year**：2022    
**Volume**：-    
**Issue**：1    
**Page**：37-40    
**Author**：__Jiang Y__, Liu Y    
**Tag**：-    

<h3 id="publications-2021">·2021</h3>

[**An analysis of the collection construction model of university libraries driven by reader behavior data**]()  
**Source**：*Digital & Micrographic Imaging*    
**Year**：2021    
**Volume**：-    
**Issue**：4    
**Page**：39-42    
**Author**：__Jiang Y__, Liu Y    
**Tag**：-    

[**Reflections on the Construction Mode of Creative Space in Independent Colleges under the Background of Double Creation**]()  
**Source**：*Policy & Scientific Consult*    
**Year**：2021    
**Volume**：-    
**Issue**：6    
**Page**：22-24    
**Author**：Li Y, __Jiang Y__    
**Tag**：-    

<h3 id="publications-2020">·2020</h3>

[**An Analysis of the "Emotion Space Time" Model from the Perspective of Digital Humanity**](https://nytsqb.aiijournal.com/CN/10.13998/j.cnki.issn1002-1248.2020.03.16-0170)  
**Source**：*Journal of Library and Information Science in Agriculture*    
**Year**：2020    
**Volume**：32    
**Issue**：6    
**Page**：23-33    
**Author**：__Jiang Y__, Li Y    
**Tag**：Scopus    

[**Using GitHub Open Sources and Database Methods Designed to Auto-Generate Chinese Tang Dynasty Poetry**](https://link.springer.com/chapter/10.1007/978-981-15-7530-3_32)  
**Source**：*Big Data and Security*    
**Year**：2020    
**Volume**：1210    
**Issue**：-    
**Page**：417-428    
**Author**：Yu H, Li Z, __Jiang Y__    
**Tag**：Scopus

[**Analysis of Research Hotspots in Competitive Intelligence Literature of China in Recent Five Years**]()  
**Source**：*Technology and Economic Guide*    
**Year**：2020    
**Volume**：28    
**Issue**：5    
**Page**：7-9    
**Author**：__Jiang Y__, Li Y    
**Tag**：-    

_Note: All categorised results are based on the highest of the results in the major and minor subdivisions._
