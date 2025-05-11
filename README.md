<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JCY天团共益文化联合理事安理会</title>
    <style>
        :root {
            --primary-color: #ff0000;
            --secondary-color: #333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: "Microsoft YaHei", sans-serif;
        }

        body {
            line-height: 1.6;
            padding: 20px;
            background-color: #f5f5f5;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        h1 {
            color: var(--primary-color);
            text-align: center;
            font-size: 2.5em;
            margin: 40px 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        .section {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
            margin-bottom: 30px;
        }

        .team-list {
            display: grid;
            gap: 20px;
        }

        .team-item {
            padding: 20px;
            border: 1px solid #eee;
            border-radius: 8px;
            transition: transform 0.3s;
            cursor: pointer;
        }

        .team-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .council-members {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .member-card {
            flex: 1;
            min-width: 250px;
            max-width: 300px;
            text-align: center;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        footer {
            text-align: center;
            padding: 40px 0;
            color: #666;
            font-size: 0.9em;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 1.8em;
                margin: 20px 0;
            }

            .section {
                padding: 20px;
            }

            .council-members {
                flex-direction: column;
            }

            .member-card {
                width: 100%;
                max-width: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>JCY天团共益文化联合理事安理会</h1>
        <h1>JCY Team United Council and Security Council</h1>

        <section class="section">
            <h2>联合天团</h2>
            <div class="team-list">
                <div class="team-item">
                    <h3>某某天团</h3>
                    <p>平台：某某平台</p>
                    <p>创始人：XXX</p>
                    <p>外交常驻：XXX</p>
                    <p>可文字自定义</p>
                </div>
                <div class="team-item">
                    <h3>某某天团</h3>
                    <p>平台：某某平台</p>
                    <p>创始人：XXX</p>
                    <p>外交常驻：XXX</p>
                    <p>可文字自定义</p>
                </div>
                <!-- 更多天团 -->
            </div>
        </section>

        <section class="section">
            <h2>理事会介绍</h2>
            <p>“JCY天团联合理事会”全名“在数字时代，互联网已成为全球连接的核心纽带，却也面临网络暴力、信息茧房、数据安全等多重挑战。我们深刻意识到，唯有以团队协作凝聚力量、以共益文化构筑共识，方能守护网络空间的清朗与和平。JCY天团共益文化联合理事安理会（英文全称为“JCY Team United Council and Security Council”，缩写“JCYTUCASC”）于2025年5月11日正式成立，是由一群秉持“共益、共治、共享”理念的同仁发起的非营利性团队合作协会。我们以“构建全球网络和平生态”为愿景，聚焦共益文化在数字领域的实践，通过搭建联合理事机制与安全治理框架，整合行业资源、联动多元主体，开展网络文明倡导、安全风险防控、跨界协作对话等行动，致力于将网络空间建设为包容、安全、充满人文温度的“数字共同体”。我们始终相信，每一次协作都在浇筑和平基石，每一份共益理念都在点亮网络文明。加入我们，让我们以团队之名，共赴数字文明新征程。”</p>
        </section>

        <section class="section">
            <h2>理事会创始人</h2>
            <div class="council-members">
                <div class="member-card">
                    <h3>成缘</h3>
                    <p>平台名：莫名其妙</p>
                    <p>职位：JCY联合安理会会长</p>
                    <p>负责领域：全部范围</p>
                    <p>回森号：2466865401</p>
                </div>
                <!-- 更多创始人 -->
            </div>
        </section>
    </div>

    <footer>
        <p>本网页由JCY天团共益文化联合理事安理会和合作天团拥有所有解释权</p>
        <p>合作栏目区域由合作天团拥有所有解释权</p>
        <p>感谢回森（北京晨钟科技有限公司）提供社交平台和支持</p>
        <p>注：此网面大部分内容为虚构请注意辨别</p>
    </footer>

    <script>
        // 设备识别功能
        function detectDevice() {
            if (/Mobi|Android/i.test(navigator.userAgent)) {
                document.body.classList.add('mobile');
            } else {
                document.body.classList.add('desktop');
            }
        }
        window.onload = detectDevice;
    </script>
</body>
</html>
