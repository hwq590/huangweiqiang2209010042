<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的简历</title>
    <style>
        body {
            font-family: 'Microsoft YaHei', sans-serif;
            line-height: 1.5;
            max-width: 700px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            border-bottom: 1px solid #ddd;
            padding-bottom: 10px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section-title {
            font-weight: bold;
            margin-bottom: 10px;
        }
        .job, .education {
            margin-bottom: 15px;
        }
        .date {
            color: #666;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <h1>张三</h1>
    <p>电话: 123-4567-8910 | 邮箱: example@email.com</p>
    
    <div class="section">
        <div class="section-title">个人简介</div>
        <p>拥有3年开发经验的软件工程师，熟悉前端开发和后端技术。</p>
    </div>
    
    <div class="section">
        <div class="section-title">工作经历</div>
        <div class="job">
            <p><strong>前端开发工程师</strong> - ABC公司</p>
            <p class="date">2020年6月 - 至今</p>
            <ul>
                <li>负责公司官网开发与维护</li>
                <li>使用Vue.js开发后台管理系统</li>
            </ul>
        </div>
    </div>
    
    <div class="section">
        <div class="section-title">教育背景</div>
        <div class="education">
            <p><strong>计算机科学与技术 本科</strong> - XX大学</p>
            <p class="date">2016年9月 - 2020年6月</p>
        </div>
    </div>
    
    <div class="section">
        <div class="section-title">技能</div>
        <p>HTML/CSS, JavaScript, Vue.js, Node.js</p>
    </div>
</body>
</html>
