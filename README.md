# ABOUT
index47 was started in May of 2026, by programmers on 13100 47 Beavers. This was started
through observations that many people in the ftc community are not always caught up with references,
definitions, or acroynyms. This website simply solves all of these problems!

# CONTRIBUTING
When contributing, use the templete below, make sure that formatting of text, textboxes,
links, and fonts are uniform. Look below for templete

## NEW FILES

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title><!-- nameOfSearch --> | Index47</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle at center, #0b1220 0%, #05070d 100%);
            font-family: Arial, sans-serif;
            color: white;
            overflow: hidden;
        }

        .grid-lines {
            position: absolute;
            width: 200%;
            height: 200%;
            background-image: linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
                              linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);
            background-size: 70px 70px;
            transform: rotate(25deg);
            top: -50%;
            left: -50%;
            z-index: 0;
            pointer-events: none;
        }

        .container {
            text-align: center;
            transform: scale(0.7142857);
            position: relative;
            z-index: 1;
            max-width: 1000px;
        }

        .logo-glow {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 600px;
            height: 600px;
            background: radial-gradient(circle, rgba(0,140,255,0.18), transparent 60%);
            filter: blur(25px);
            z-index: -1;
        }

        .tag {
            font-size: 18px;
            letter-spacing: 6px;
            color: rgba(180, 190, 255, 0.6);
            margin-bottom: 20px;
        }

        .title {
            font-size: 70px;
            letter-spacing: 12px;
            color: #cfd8ff;
            margin-bottom: 35px;
            text-shadow: 0 0 25px rgba(0,140,255,0.25);
        }

        .card {
            background: rgba(10, 15, 25, 0.75);
            border: 1px solid rgba(0,140,255,0.35);
            border-radius: 18px;
            padding: 45px 55px;
            box-shadow: 0 0 45px rgba(0,140,255,0.12);
            backdrop-filter: blur(8px);
        }

        .definition {
            font-size: 22px;
            line-height: 1.8;
            color: rgba(220, 230, 255, 0.85);
        }

        .highlight {
            color: #7fb7ff;
            font-weight: bold;
        }

        a {
            color: #7fb7ff;
            text-decoration: underline;
            transition: 0.2s;
        }

        a:visited {
            color: #7fb7ff;
        }

        a:hover {
            color: #ffffff;
        }

        .back {
            margin-top: 35px;
            font-size: 14px;
            letter-spacing: 3px;
            color: rgba(160, 180, 255, 0.6);
            cursor: pointer;
            transition: 0.2s;
        }

        .back:hover {
            color: rgba(0,140,255,0.9);
        }
    </style>
</head>

<body>

<div class="grid-lines"></div>

<div class="container">

    <div class="logo-glow"></div>

    <div class="title">OPR</div>

    <div class="card">
        <div class="definition">
            <span class="highlight"><!-- Acronym (if any) Title of section --></span> 
            <!-- Description; the content that people should know -->
            <!-- Embedding links within description should be done as shown on the line below -->
             <a href="<!-- link with https -->" target="_blank"><!-- link without https --></a>
        </div>
    </div>

    <div class="back" onclick="window.location.href='index.html'">
        ← RETURN TO INDEX47
    </div>

</div>
</body>
</html>


