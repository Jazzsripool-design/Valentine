    button:hover {
        background-color: #ff1e4d;
    }

    #message {
        margin-top: 25px;
        font-size: 22px;
        display: none;
    }
</style>
</head>

<body>

<h1>💝 Happy Valentine’s Day 💝</h1>
<p>ถึงคนพิเศษของเรา</p>

<img src="Valentine.JPG" alt="รูปของเรา">

<br>
<button onclick="showLove()">กดเพื่อรับเซอร์ไพรส์ 💌</button>

<div id="message">
    <p>รักเธอมากนะ 💖</p>
    <p>ขอบคุณที่อยู่ข้าง ๆ กันเสมอ</p>
    <p>อยู่ด้วยกันไปนาน ๆ นะ 😊</p>
</div>

<!-- เพลง -->
<audio id="song">
    <source src="Valentine.mp3" type="audio/mpeg">
</audio>

<script>
function showLove() {
    document.getElementById("message").style.display = "block";
    document.getElementById("song").play();
}
</script>

</body>
</html>
