<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>张三的简历</title>
    <style>
        body {
            font-family: 'Microsoft YaHei', Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        .header {
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid #3498db;
            padding-bottom: 20px;
        }
        h1 {
            color: #2c3e50;
            margin-bottom: 5px;
        }
        .contact-info {
            margin: 10px 0;
        }
        .section {
            margin-bottom: 25px;
        }
        .section-title {
            background-color: #f8f9fa;
            padding: 8px 15px;
            border-left: 4px solid #3498db;
            color: #2c3e50;
            font-weight: bold;
            margin-bottom: 15px;
        }
        .job, .education {
            margin-bottom: 20px;
        }
        .job-title, .degree {
            font-weight: bold;
            margin-bottom: 5px;
        }
        .company, .school {
            font-weight: bold;
            color: #3498db;
        }
        .date {
            color: #7f8c8d;
            font-style: italic;
            margin-bottom: 5px;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
        }
        .skill {
            background-color: #e8f4fc;
            padding: 5px 10px;
            margin: 0 10px 10px 0;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>黄维强2209010042</h1>
        <div class="contact-info">
            电话: 138-1234-5678 | 邮箱: zhangsan@example.com | 地址: 北京市海淀区
        </div>
        <div class="contact-info">
            LinkedIn: linkedin.com/in/zhangsan | GitHub: github.com/zhangsan
        </div>
    </div>

    <div class="section">
        <div class="section-title">个人简介</div>
        <p>拥有5年全栈开发经验的软件工程师，擅长JavaScript、Python和Java开发。在Web应用开发和系统架构设计方面有丰富经验，曾主导多个高并发系统的设计与实现。热爱技术分享，持续学习新技术。</p>
    </div>

    <div class="section">
        <div class="section-title">工作经历</div>
        
        <div class="job">
            <div class="job-title">高级软件工程师</div>
            <div class="company">ABC科技有限公司</div>
            <div class="date">2020年6月 - 至今</div>
            <ul>
                <li>负责公司核心产品的架构设计和开发，使用React和Node.js构建高性能Web应用</li>
                <li>带领5人开发团队，实施敏捷开发流程，提升团队开发效率30%</li>
                <li>设计并实现微服务架构，系统吞吐量提升200%</li>
                <li>优化数据库查询，将关键API响应时间从500ms降低到150ms</li>
            </ul>
        </div>
        
        <div class="job">
            <div class="job-title">软件工程师</div>
            <div class="company">XYZ软件公司</div>
            <div class="date">2018年3月 - 2020年5月</div>
            <ul>
                <li>参与企业级ERP系统的开发，使用Java Spring框架</li>
                <li>负责前端界面重构，采用Vue.js提升用户体验</li>
                <li>实现自动化测试框架，减少回归测试时间40%</li>
            </ul>
        </div>
    </div>

    <div class="section">
        <div class="section-title">教育背景</div>
        <div class="education">
            <div class="degree">计算机科学与技术 硕士</div>
            <div class="school">清华大学</div>
            <div class="date">2015年9月 - 2018年6月</div>
            <p>研究方向: 分布式系统 | GPA: 3.8/4.0</p>
        </div>
        <div class="education">
            <div class="degree">软件工程 学士</div>
            <div class="school">北京大学</div>
            <div class="date">2011年9月 - 2015年6月</div>
            <p>主修课程: 数据结构、算法、操作系统、计算机网络</p>
        </div>
    </div>

    <div class="section">
        <div class="section-title">专业技能</div>
        <div class="skills">
            <div class="skill">JavaScript/TypeScript</div>
            <div class="skill">React/Vue.js</div>
            <div class="skill">Node.js</div>
            <div class="skill">Python</div>
            <div class="skill">Java</div>
            <div class="skill">Spring Boot</div>
            <div class="skill">MySQL</div>
            <div class="skill">MongoDB</div>
            <div class="skill">Docker</div>
            <div class="skill">Kubernetes</div>
            <div class="skill">AWS</div>
            <div class="skill">Git</div>
            <div class="skill">敏捷开发</div>
        </div>
    </div>

    <div class="section">
        <div class="section-title">项目经验</div>
        <div class="job">
            <div class="job-title">电商平台重构项目</div>
            <div class="date">2021年3月 - 2021年12月</div>
            <ul>
                <li>将单体架构重构为微服务架构，使用Spring Cloud和Docker</li>
                <li>设计并实现商品搜索服务，支持每秒5000+查询</li>
                <li>引入Redis缓存，将热门商品页加载时间从1.2s降低到300ms</li>
                <li>项目上线后，系统稳定性提升至99.99%，销售额增长25%</li>
            </ul>
        </div>
    </div>

    <div class="section">
        <div class="section-title">证书与荣誉</div>
        <ul>
            <li>AWS认证解决方案架构师 - 专业级 (2022)</li>
            <li>公司年度最佳员工 (2021)</li>
            <li>全国大学生编程竞赛一等奖 (2017)</li>
        </ul>
    </div>
</body>
</html>
