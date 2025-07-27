<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=300&&section=header&text={TITLE}&fontSize=90&fontAlign=50&fontAlignY=30&desc={SUB_TITLE}&descAlign=50&descSize=30&descAlignY=60&animation=twinkling" />
</p>

<div align="center"> <img height="137px" src="https://github-readme-stats.vercel.app/api?username=3323223659&hide_title=true&hide_border=true&show_icons=trueline_height=21&text_color=000&icon_color=000&bg_color=0,ea6161,ffc64d,fffc4d,52fa5a&theme=graywhite" /> </div>

<div align="center"> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=3323223659&hide_title=true&hide_border=true&layout=compact&langs_count=6&text_color=000&icon_color=fff&bg_color=0,52fa5a,4dfcff,c64dff&theme=graywhite" /> </div>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=idea,java,pycharm,py,vscode,vue,js,html,css" />
  </a>
</p>

<img width="800" src="https://github-readme-activity-graph.vercel.app/graph?username=3323223659&theme=github-compact&hide_border=true&area=true" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=3323223659&layout=compact&hide_border=true&langs_count=10">

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=300&&section=footer&text={TITLE}&fontSize=90&fontAlign=50&fontAlignY=70&desc={SUB_TITLE}&descAlign=50&descSize=30&descAlignY=40&animation=twinkling" />
</p>
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>杨潇 | Java后端开发工程师</title>
    <style>
        :root {
            --primary-color: #0ff;
            --secondary-color: #8a2be2;
            --dark-bg: #0a0a16;
            --card-bg: rgba(21, 21, 55, 0.7);
            --text-color: #e6f1ff;
            --accent-color: #ff6b6b;
            --font-main: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: var(--font-main);
            background: var(--dark-bg);
            color: var(--text-color);
            line-height: 1.6;
            overflow-x: hidden;
            background-image: 
                radial-gradient(circle at 10% 20%, rgba(10, 80, 150, 0.1) 0%, transparent 20%),
                radial-gradient(circle at 90% 80%, rgba(138, 43, 226, 0.1) 0%, transparent 20%),
                linear-gradient(to bottom, #0a0a16, #060613);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .header {
            text-align: center;
            padding: 40px 20px;
            position: relative;
            margin-bottom: 50px;
            overflow: hidden;
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: 
                radial-gradient(circle, var(--primary-color) 0%, transparent 70%),
                repeating-linear-gradient(45deg, 
                    transparent, transparent 10px, 
                    rgba(10, 80, 150, 0.3) 10px, 
                    rgba(10, 80, 150, 0.3) 20px);
            opacity: 0.1;
            z-index: -1;
            animation: rotate 120s linear infinite;
        }
        
        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
        
        .header h1 {
            font-size: 3.5rem;
            margin-bottom: 15px;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 15px rgba(0, 255, 255, 0.3);
            letter-spacing: 1px;
        }
        
        .header h2 {
            font-size: 1.5rem;
            font-weight: 400;
            color: rgba(230, 241, 255, 0.8);
            margin-bottom: 30px;
        }
        
        .neon-divider {
            width: 80%;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--primary-color), transparent);
            margin: 25px auto;
            border-radius: 2px;
            box-shadow: 0 0 10px var(--primary-color);
        }
        
        .card {
            background: var(--card-bg);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(0, 255, 255, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0, 255, 255, 0.2);
            border: 1px solid rgba(0, 255, 255, 0.3);
        }
        
        .card h3 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: var(--primary-color);
            display: flex;
            align-items: center;
        }
        
        .card h3::after {
            content: '';
            flex: 1;
            height: 1px;
            background: linear-gradient(90deg, var(--primary-color), transparent);
            margin-left: 20px;
        }
        
        .about-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .info-item {
            background: rgba(15, 30, 60, 0.5);
            border-radius: 10px;
            padding: 20px;
            border-left: 3px solid var(--primary-color);
        }
        
        .info-item strong {
            color: var(--primary-color);
            display: block;
            margin-bottom: 8px;
            font-size: 1.1rem;
        }
        
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }
        
        .skill-tag {
            background: linear-gradient(135deg, rgba(0, 255, 255, 0.2), rgba(138, 43, 226, 0.2));
            border: 1px solid rgba(0, 255, 255, 0.3);
            padding: 8px 20px;
            border-radius: 30px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            transition: all 0.3s ease;
        }
        
        .skill-tag:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 255, 255, 0.2);
            background: linear-gradient(135deg, rgba(0, 255, 255, 0.3), rgba(138, 43, 226, 0.3));
        }
        
        .skill-tag::before {
            content: '▹';
            margin-right: 8px;
            color: var(--primary-color);
        }
        
        .tools-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 25px;
            margin-top: 25px;
        }
        
        .tool-item {
            text-align: center;
            padding: 20px;
            border-radius: 10px;
            background: rgba(15, 30, 60, 0.4);
            transition: all 0.3s ease;
        }
        
        .tool-item:hover {
            transform: translateY(-8px);
            background: rgba(20, 40, 80, 0.6);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4);
        }
        
        .tool-icon {
            font-size: 3rem;
            margin-bottom: 15px;
            color: var(--primary-color);
            text-shadow: 0 0 15px rgba(0, 255, 255, 0.5);
        }
        
        .tool-name {
            font-weight: 600;
            font-size: 1.1rem;
        }
        
        .languages-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 25px;
        }
        
        .language-item {
            flex: 1;
            min-width: 200px;
            background: rgba(15, 30, 60, 0.4);
            padding: 20px;
            border-radius: 10px;
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: all 0.3s ease;
        }
        
        .language-item:hover {
            background: rgba(20, 40, 80, 0.6);
            transform: translateY(-5px);
        }
        
        .language-name {
            font-size: 1.3rem;
            font-weight: 600;
            margin-bottom: 15px;
            color: var(--accent-color);
        }
        
        .language-bar {
            width: 100%;
            height: 10px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 5px;
            margin-bottom: 15px;
            overflow: hidden;
        }
        
        .language-level {
            height: 100%;
            border-radius: 5px;
            background: linear-gradient(90deg, var(--primary-color), var(--secondary-color));
            box-shadow: 0 0 10px rgba(0, 255, 255, 0.5);
        }
        
        .java .language-level { width: 95%; }
        .python .language-level { width: 75%; }
        .javascript .language-level { width: 85%; }
        .html .language-level { width: 80%; }
        .css .language-level { width: 80%; }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }
        
        .social-link {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 12px 25px;
            border-radius: 30px;
            text-decoration: none;
            color: white;
            background: rgba(255, 255, 255, 0.1);
            transition: all 0.3s ease;
            border: 1px solid rgba(0, 255, 255, 0.2);
        }
        
        .social-link:hover {
            background: linear-gradient(135deg, rgba(0, 255, 255, 0.2), rgba(138, 43, 226, 0.2));
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 255, 255, 0.2);
            border: 1px solid rgba(0, 255, 255, 0.4);
        }
        
        .social-link i {
            font-size: 1.5rem;
        }
        
        .footer {
            text-align: center;
            padding: 40px 0;
            margin-top: 50px;
            font-size: 1.1rem;
            color: rgba(230, 241, 255, 0.7);
        }
        
        @media (max-width: 768px) {
            .header h1 { font-size: 2.5rem; }
            .header h2 { font-size: 1.2rem; }
            .card { padding: 20px; }
            .tools-container { grid-template-columns: repeat(2, 1fr); }
            .social-links { flex-direction: column; align-items: center; }
            .social-link { width: 80%; justify-content: center; }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>杨潇 | Java后端开发工程师</h1>
            <h2>构建高性能后端系统 · 探索前沿技术 · 解决复杂问题</h2>
            <div class="neon-divider"></div>
        </div>
        
        <!-- 个人介绍 -->
        <div class="card">
            <h3><i class="fas fa-user"></i> 个人介绍</h3>
            <div class="about-grid">
                <div class="info-item">
                    <strong>基本信息</strong>
                    <div>姓名：杨潇</div>
                    <div>年龄：20岁</div>
                    <div>学历：全日制本科（广东石油化工学院）</div>
                    <div>专业：计算机科学与技术</div>
                    <div>意向职位：Java后端开发</div>
                </div>
                
                <div class="info-item">
                    <strong>教育背景</strong>
                    <div>广东石油化工学院 (2023.09 - 2027.07)</div>
                    <div>主修课程：Java程序开发、数据库系统概论、软件工程、数据结构</div>
                    <div>专业成绩：GPA 3.2+（本专业前10%），获校级奖学金</div>
                </div>
                
                <div class="info-item">
                    <strong>自我评价</strong>
                    <div>精通Java生态，具备架构设计与调优能力</div>
                    <div>主导多个从0到1项目，协调团队高效交付</div>
                    <div>擅长定位并解决高并发、分布式系统问题</div>
                    <div>持续关注新技术，推动技术创新</div>
                </div>
            </div>
        </div>
        
        <!-- 技术栈 -->
        <div class="card">
            <h3><i class="fas fa-code"></i> 技术栈</h3>
            <div class="skills-container">
                <div class="skill-tag">Java（精通）</div>
                <div class="skill-tag">Spring Boot/Cloud</div>
                <div class="skill-tag">MySQL（事务/索引优化）</div>
                <div class="skill-tag">Redis（高并发优化）</div>
                <div class="skill-tag">JVM调优</div>
                <div class="skill-tag">并发编程（锁机制/AQS）</div>
                <div class="skill-tag">微服务架构</div>
                <div class="skill-tag">分布式解决方案</div>
                <div class="skill-tag">RabbitMQ/Kafka</div>
                <div class="skill-tag">Nginx/Elasticsearch</div>
                <div class="skill-tag">Docker/Jenkins</div>
                <div class="skill-tag">Vue2/Vue3</div>
                <div class="skill-tag">Flask开发</div>
                <div class="skill-tag">3D可视化</div>
                <div class="skill-tag">SpringAI集成</div>
            </div>
        </div>
        
        <!-- 常用生产工具 -->
        <div class="card">
            <h3><i class="fas fa-tools"></i> 常用生产工具</h3>
            <div class="tools-container">
                <div class="tool-item">
                    <div class="tool-icon"><i class="fab fa-java"></i></div>
                    <div class="tool-name">IntelliJ IDEA</div>
                </div>
                <div class="tool-item">
                    <div class="tool-icon"><i class="fas fa-terminal"></i></div>
                    <div class="tool-name">PyCharm</div>
                </div>
                <div class="tool-item">
                    <div class="tool-icon"><i class="fab fa-microsoft"></i></div>
                    <div class="tool-name">VS Code</div>
                </div>
                <div class="tool-item">
                    <div class="tool-icon"><i class="fab fa-git-alt"></i></div>
                    <div class="tool-name">Git/GitHub</div>
                </div>
                <div class="tool-item">
                    <div class="tool-icon"><i class="fab fa-docker"></i></div>
                    <div class="tool-name">Docker</div>
                </div>
                <div class="tool-item">
                    <div class="tool-icon"><i class="fas fa-server"></i></div>
                    <div class="tool-name">Jenkins</div>
                </div>
                <div class="tool-item">
                    <div class="tool-icon"><i class="fas fa-database"></i></div>
                    <div class="tool-name">MySQL Workbench</div>
                </div>
                <div class="tool-item">
                    <div class="tool-icon"><i class="fas fa-cloud"></i></div>
                    <div class="tool-name">阿里云OSS</div>
                </div>
            </div>
        </div>
        
        <!-- 常用语言 -->
        <div class="card">
            <h3><i class="fas fa-language"></i> 常用语言</h3>
            <div class="languages-container">
                <div class="language-item java">
                    <div class="language-name">Java</div>
                    <div class="language-bar">
                        <div class="language-level"></div>
                    </div>
                    <div>精通Java核心、并发编程、JVM原理与调优</div>
                </div>
                <div class="language-item python">
                    <div class="language-name">Python</div>
                    <div class="language-bar">
                        <div class="language-level"></div>
                    </div>
                    <div>熟悉Python开发，用于脚本编写和AI集成</div>
                </div>
                <div class="language-item javascript">
                    <div class="language-name">JavaScript</div>
                    <div class="language-bar">
                        <div class="language-level"></div>
                    </div>
                    <div>熟悉JavaScript，用于前端开发与交互</div>
                </div>
                <div class="language-item html">
                    <div class="language-name">HTML5</div>
                    <div class="language-bar">
                        <div class="language-level"></div>
                    </div>
                    <div>熟悉HTML5，用于前端页面构建</div>
                </div>
                <div class="language-item css">
                    <div class="language-name">CSS3</div>
                    <div class="language-bar">
                        <div class="language-level"></div>
                    </div>
                    <div>熟悉CSS3，用于界面设计与美化</div>
                </div>
            </div>
        </div>
        
        <!-- 联系方式 -->
        <div class="social-links">
            <a href="https://github.com/3323223659" class="social-link" target="_blank">
                <i class="fab fa-github"></i>
                <span>GitHub</span>
            </a>
            <a href="https://blog.csdn.net/230279380280" class="social-link" target="_blank">
                <i class="fas fa-blog"></i>
                <span>CSDN博客</span>
            </a>
            <a href="mailto:3323223659@qq.com" class="social-link">
                <i class="fas fa-envelope"></i>
                <span>3323223659@qq.com</span>
            </a>
            <a href="tel:15918879728" class="social-link">
                <i class="fas fa-phone"></i>
                <span>15918879728</span>
            </a>
        </div>
        
        <div class="footer">
            <p>热爱技术，追求卓越！🚀 期待与您共同创造价值！</p>
            <p>© 2024 杨潇 | Java后端开发工程师</p>
        </div>
    </div>
    
    <script>
        // 添加动画效果
        document.addEventListener('DOMContentLoaded', function() {
            // 卡片动画
            const cards = document.querySelectorAll('.card');
            cards.forEach((card, index) => {
                setTimeout(() => {
                    card.style.opacity = '1';
                    card.style.transform = 'translateY(0)';
                }, 300 * index);
            });
            
            // 滚动动画
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('animate');
                    }
                });
            }, { threshold: 0.1 });
            
            document.querySelectorAll('.info-item, .skill-tag, .tool-item, .language-item').forEach(item => {
                item.style.opacity = '0';
                item.style.transform = 'translateY(20px)';
                item.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                observer.observe(item);
            });
            
            document.querySelectorAll('.info-item, .skill-tag, .tool-item, .language-item').forEach(item => {
                item.addEventListener('mouseenter', function() {
                    this.style.zIndex = '10';
                });
                
                item.addEventListener('mouseleave', function() {
                    this.style.zIndex = '1';
                });
            });
        });
    </script>
</body>
</html>
