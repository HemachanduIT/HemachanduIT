<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub README Preview - Hemachandu</title>
    <style>
        body {
            background: #0d1117;
            color: #c9d1d9;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 1012px;
            margin: 0 auto;
            background: #0d1117;
            padding: 20px;
        }
        .center {
            text-align: center;
        }
        .header-3d {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 60px 20px;
            border-radius: 20px;
            margin-bottom: 30px;
            box-shadow: 0 20px 60px rgba(102, 126, 234, 0.4);
            position: relative;
            overflow: hidden;
        }
        .header-3d::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
            animation: shine 3s infinite;
        }
        @keyframes shine {
            0% { transform: translateX(-100%) translateY(-100%) rotate(45deg); }
            100% { transform: translateX(100%) translateY(100%) rotate(45deg); }
        }
        .name-3d {
            font-size: 4em;
            font-weight: 900;
            color: #fff;
            text-shadow: 
                0 1px 0 #ccc,
                0 2px 0 #c9c9c9,
                0 3px 0 #bbb,
                0 4px 0 #b9b9b9,
                0 5px 0 #aaa,
                0 6px 1px rgba(0,0,0,.1),
                0 0 5px rgba(0,0,0,.1),
                0 1px 3px rgba(0,0,0,.3),
                0 3px 5px rgba(0,0,0,.2),
                0 5px 10px rgba(0,0,0,.25),
                0 10px 10px rgba(0,0,0,.2),
                0 20px 20px rgba(0,0,0,.15);
            letter-spacing: 5px;
            margin: 20px 0;
            animation: float 3s ease-in-out infinite;
            position: relative;
            z-index: 1;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        .subtitle-3d {
            font-size: 1.5em;
            color: #fff;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            margin: 20px 0;
            position: relative;
            z-index: 1;
        }
        .tagline {
            font-size: 1.1em;
            color: rgba(255,255,255,0.8);
            font-style: italic;
            margin-top: 10px;
            position: relative;
            z-index: 1;
        }
        .divider {
            width: 100%;
            height: 3px;
            background: linear-gradient(90deg, transparent, #00d9ff, transparent);
            margin: 30px 0;
            box-shadow: 0 0 20px rgba(0, 217, 255, 0.5);
        }
        h2 {
            color: #58a6ff;
            border-bottom: 1px solid #21262d;
            padding-bottom: 10px;
            margin-top: 30px;
            font-size: 1.8em;
        }
        h3 {
            color: #8b949e;
            font-weight: 600;
            margin: 20px 0;
            font-size: 1.3em;
        }
        .badge-container {
            display: flex;
            gap: 10px;
            justify-content: center;
            flex-wrap: wrap;
            margin: 20px 0;
        }
        .tech-badges {
            display: flex;
            gap: 8px;
            flex-wrap: wrap;
            margin: 15px 0;
        }
        .code-block {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 16px;
            margin: 20px 0;
            text-align: left;
            font-family: 'Courier New', monospace;
            font-size: 14px;
            line-height: 1.6;
            color: #79c0ff;
            overflow-x: auto;
        }
        .stats-container {
            display: flex;
            gap: 10px;
            justify-content: center;
            flex-wrap: wrap;
            margin: 30px 0;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        .gif-container {
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="center">
            <div class="header-3d">
                <div class="name-3d">HEMACHANDU BENUBOYINA</div>
                <div class="subtitle-3d">Full Stack Developer | AI/ML Engineer | DevOps Enthusiast</div>
                <div class="tagline">✨ Turning Ideas Into Reality With Code ✨</div>
            </div>
            
            <div class="gif-container">
                <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700" alt="Coding Animation">
            </div>
            
            <div class="divider"></div>
            
            <div class="badge-container">
                <a href="mailto:hemachandubenuboyina@gmail.com">
                    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                </a>
                <a href="https://www.linkedin.com/in/hemachanduit/">
                    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                </a>
                <img src="https://komarev.com/ghpvc/?username=HemachanduIT&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile views">
            </div>
        </div>

        <h2>👨‍💻 About Me</h2>
        
        <div class="code-block">
<span style="color: #ff7b72;">const</span> <span style="color: #79c0ff;">hemachandu</span> <span style="color: #ff7b72;">=</span> {
    <span style="color: #79c0ff;">currentFocus</span>: [<span style="color: #a5d6ff;">"Full Stack Development"</span>, <span style="color: #a5d6ff;">"AI/ML"</span>, <span style="color: #a5d6ff;">"Python"</span>, <span style="color: #a5d6ff;">"Java"</span>],
    <span style="color: #79c0ff;">learning</span>: [<span style="color: #a5d6ff;">"DevOps"</span>, <span style="color: #a5d6ff;">"Cloud Technologies"</span>],
    <span style="color: #79c0ff;">collaboration</span>: [<span style="color: #a5d6ff;">"Full Stack Projects"</span>, <span style="color: #a5d6ff;">"AI/ML Solutions"</span>],
    <span style="color: #79c0ff;">expertise</span>: [<span style="color: #a5d6ff;">"Full Stack Tools"</span>, <span style="color: #a5d6ff;">"AI/ML Frameworks"</span>],
    <span style="color: #79c0ff;">pronouns</span>: <span style="color: #a5d6ff;">"He/Him"</span>
};
        </div>

        <h2>🚀 Tech Stack</h2>
        
        <h3>Languages</h3>
        <div class="tech-badges">
            <img src="https://img.shields.io/badge/-Python-000?&logo=Python" alt="Python">
            <img src="https://img.shields.io/badge/-JavaScript-000?&logo=JavaScript" alt="JavaScript">
            <img src="https://img.shields.io/badge/-C-000?&logo=C" alt="C">
            <img src="https://img.shields.io/badge/-Java-000?&logo=Java&logoColor=007396" alt="Java">
            <img src="https://img.shields.io/badge/-TypeScript-000?&logo=TypeScript" alt="TypeScript">
            <img src="https://img.shields.io/badge/-SQL-000?&logo=MySQL" alt="SQL">
        </div>

        <h3>Technologies</h3>
        <div class="tech-badges">
            <img src="https://img.shields.io/badge/-React-000?&logo=React" alt="React">
            <img src="https://img.shields.io/badge/-Node.js-000?&logo=node.js" alt="Node.js">
            <img src="https://img.shields.io/badge/-PyTorch-000?&logo=PyTorch" alt="PyTorch">
            <img src="https://img.shields.io/badge/-TensorFlow-000?&logo=TensorFlow" alt="TensorFlow">
            <img src="https://img.shields.io/badge/-Linux-000?&logo=Linux" alt="Linux">
            <img src="https://img.shields.io/badge/-Spring-000?&logo=Spring" alt="Spring">
            <img src="https://img.shields.io/badge/-Docker-000?&logo=Docker" alt="Docker">
        </div>

        <h2>📊 GitHub Stats</h2>
        <div class="stats-container">
            <img src="https://github-readme-stats.vercel.app/api?username=HemachanduIT&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" height="180" alt="GitHub Stats">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=HemachanduIT&theme=tokyonight&hide_border=true&background=0D1117" height="180" alt="GitHub Streak">
        </div>

        <div class="center" style="margin-top: 40px;">
            <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" alt="Footer">
        </div>
    </div>
</body>
</html>