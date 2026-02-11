
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For My Love</title>
<style>
body {
    text-align: center;
    font-family: "Georgia", serif;
    background: linear-gradient(to bottom, #ffd6e8, #ffe6f2);
}

.box {
    background: rgba(255, 255, 255, 0.85);
    width: 60%;
    margin: 70px auto;
    padding: 25px;
    border-radius: 15px;
    box-shadow: 0px 0px 8px rgba(184, 91, 122, 0.3);
}

h1 {
    color: #b85b7a;
}

button {
    padding: 8px 15px;
    margin: 10px;
    font-size: 14px;
    background: #f2a6c2;
    color: white;
    border: none;
    border-radius: 20px;
    cursor: pointer;
}

button:hover {
    background: #d88aa4;
}

.selected {
    background: #b85b7a !important;
}

.page {
    display: none;
}

input {
    padding: 8px;
    margin: 5px;
    border-radius: 8px;
    border: 1px solid #d89aaa;
}

.question {
    font-size: 16px;
    color: #7a3b52;
}
</style>

<script>
function showPage(pageId) {
    document.getElementById("page1").style.display = "none";
    document.getElementById("page2").style.display = "none";
    document.getElementById("page3").style.display = "none";
    document.getElementById("page4").style.display = "none";

    document.getElementById(pageId).style.display = "block";
}

function selectAnswer(btn) {
    let buttons = btn.parentElement.querySelectorAll("button");
    buttons.forEach(b => b.classList.remove("selected"));
    btn.classList.add("selected");
}
</script>
</head>

<body onload="showPage('page1')">

<h1>for my love 🤍</h1>

<!-- PAGE 1 -->
<div id="page1" class="page">
<div class="box">
<h2>Page 1 — Your Details</h2>
<p>Enter your Name:</p>
<input type="text" placeholder="Your Name"><br><br>

<p>Enter your Date of Birth:</p>
<input type="date"><br><br>

<button onclick="showPage('page2')">Next</button>
</div>
</div>

<!-- PAGE 2 -->
<div id="page2" class="page">
<div class="box">
<h2>Page 2 — Questions</h2>

<div>
<p class="question">1. Does she like dogs?</p>
<button onclick="selectAnswer(this)">Yes</button>
<button onclick="selectAnswer(this)">No</button>
</div>

<div>
<p class="question">2. Does she like food?</p>
<button onclick="selectAnswer(this)">Yes</button>
<button onclick="selectAnswer(this)">No</button>
</div>

<div>
<p class="question">3. Do you miss her?</p>
<button onclick="selectAnswer(this)">Yes</button>
<button onclick="selectAnswer(this)">No</button>
</div>

<div>
<p class="question">4. Do you love her?</p>
<button onclick="selectAnswer(this)">Yes</button>
<button onclick="selectAnswer(this)">No</button>
</div>

<div>
<p class="question">5. Will you marry her?</p>
<button onclick="selectAnswer(this)">Yes</button>
<button onclick="selectAnswer(this)">No</button>
</div>

<br>
<button onclick="showPage('page3')">Next</button>
</div>
</div>

<!-- PAGE 3 -->
<div id="page3" class="page">
<div class="box">
<h2>Page 3 — From my heart</h2>
<h3>To my Ennavan,</h3>
<p style="font-style:italic; line-height:1.6; color:#5a2a3d;">
I love you so much, muu. You are the most important person in my life — without you, I am nothing.  
You are my sun in my life. I am so blessed to have you with me. You are my best friend, my family,  
and the love of my life. I am truly happy with you. I cherish each and every moment we share.  
You are my strength and my backbone. You were there for me when no one else was.  
We have had fights and faced struggles together — let’s have 100 years together  
and always have each other’s back. I am there for you whenever you need me. 🤍
</p>

<button onclick="showPage('page4')">Next</button>
</div>
</div>

<!-- PAGE 4 -->
<div id="page4" class="page">
<div class="box">
<h2>Page 4 — One final question</h2>
<p style="font-size:18px; color:#7a3b52;"><b>Will you be my Valentine?</b></p>

<button onclick="selectAnswer(this)">Yes</button>
<button onclick="selectAnswer(this)">No</button>
</div>
</div>

</body>
</html>
