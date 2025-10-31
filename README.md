<html lang="ja">
<head>
<style>
body, h1, p, a {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', 'Helvetica Neue', sans-serif;
}

/* Background & container styling */
body {
    background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 30px;
}

.container {
    background-color: #fff8f0;
    padding: 40px 30px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
    max-width: 600px;
    width: 100%;
    text-align: center;
}

/* Title */
.container h1 {
    font-size: 1.8em;
    color: #d35400;
    margin-bottom: 20px;
}

/* Description text */
#project-description {
    font-size: 1em;
    color: #555;
    line-height: 1.7;
    margin-bottom: 30px;
}

#project-description strong {
    color: #e74c3c;
}

/* Button styling */
.button {
    display: inline-block;
    padding: 15px 30px;
    background-color: #ff6f61;
    color: white;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.2em;
    border-radius: 10px;
    transition: background-color 0.3s ease, transform 0.2s ease;
}

.button:hover {
    background-color: #e14d41;
    transform: scale(1.05);
}
</style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>QRコードを読み取った方への説明</h1>
            <p id="project-description">
                ギタークラフト＆リペアコース１年企画！校内に現れるQRコードマンを読み込んで抽選をしましょう！<br>
                景品は１等はギター、２等は平成レトロCD、３等はぽーる・りーど・炭すの焼き鳥サービス！そして残念ながらはずれも存在します！<br>
                <strong>※１等、２等に関しては交換所（本館６Fロビー）に来た順で交換です。また１等、２等は景品がなくなり次第景品は３等とさせていただきます。ご了承ください。</strong><br>
                <strong>※短時間に何度も抽選はできません。</strong><br><br>
            では下の抽選ボタンで抽選を行ってください↓</p>

        <a href="https://qrcode-man.github.io/Raffle_prize/" id="project-link" class="button" target="_blank">Let's抽選‼</a>
