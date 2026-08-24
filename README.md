<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>For Someone Special ❤️</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:linear-gradient(135deg,#12001f,#25003d,#10001c);
    color:white;
    overflow-x:hidden;
}

/* Floating hearts */

.heart{
    position:fixed;
    bottom:-20px;
    font-size:20px;
    animation:float 6s linear forwards;
    pointer-events:none;
    z-index:0;
}

@keyframes float{
    0%{
        transform:translateY(0) rotate(0deg);
        opacity:1;
    }

    100%{
        transform:translateY(-110vh) rotate(360deg);
        opacity:0;
    }
}


/* HERO */

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:30px;
    position:relative;
    z-index:1;
}

.hero-content{
    max-width:800px;
}

.small{
    color:#ff9de2;
    font-size:18px;
    letter-spacing:3px;
    margin-bottom:20px;
}

h1{
    font-size:65px;
    margin-bottom:20px;
}

h1 span{
    color:#ff69c9;
}

.hero p{
    font-size:20px;
    line-height:1.7;
    color:#ddd;
}

.start-btn{
    margin-top:35px;
    padding:15px 35px;
    border:none;
    border-radius:30px;
    background:#ff4fc3;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:.3s;
    box-shadow:0 0 25px #ff4fc377;
}

.start-btn:hover{
    transform:scale(1.08);
    box-shadow:0 0 40px #ff4fc3;
}


/* SECTIONS */

section{
    padding:100px 8%;
    position:relative;
    z-index:1;
}

.section-title{
    text-align:center;
    font-size:40px;
    margin-bottom:50px;
}

.section-title span{
    color:#ff69c9;
}


/* CARDS */

.cards{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:25px;
    max-width:1100px;
    margin:auto;
}

.card{
    background:#ffffff0d;
    border:1px solid #ffffff18;
    padding:35px 25px;
    border-radius:25px;
    text-align:center;
    backdrop-filter:blur(10px);
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
    border-color:#ff69c9;
    box-shadow:0 10px 40px #ff69c322;
}

.card .icon{
    font-size:45px;
    margin-bottom:20px;
}

.card h3{
    margin-bottom:15px;
    font-size:22px;
}

.card p{
    color:#ccc;
    line-height:1.6;
}


/* DISTANCE */

.distance{
    text-align:center;
}

.distance-box{
    max-width:800px;
    margin:auto;
    padding:50px 30px;
    border-radius:30px;
    background:#ffffff0c;
    border:1px solid #ffffff20;
}

.distance-number{
    font-size:80px;
    margin:20px;
}

.distance-box p{
    color:#ccc;
    font-size:19px;
    line-height:1.7;
}


/* SURPRISE */

.surprise{
    text-align:center;
}

.surprise-btn{
    padding:18px 40px;
    border:none;
    border-radius:30px;
    background:linear-gradient(90deg,#ff4fc3,#a855f7);
    color:white;
    font-size:19px;
    cursor:pointer;
    transition:.3s;
}

.surprise-btn:hover{
    transform:scale(1.08);
}

.hidden-message{
    max-width:700px;
    margin:30px auto 0;
    padding:30px;
    border-radius:25px;
    background:#ffffff0d;
    border:1px solid #ff69c944;
    display:none;
    animation:appear .7s ease;
}

@keyframes appear{
    from{
        opacity:0;
        transform:translateY(20px);
    }

    to{
        opacity:1;
        transform:translateY(0);
    }
}


/* FINAL */

.final{
    min-height:70vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
}

.final-box{
    max-width:800px;
}

.final-box h2{
    font-size:50px;
    margin-bottom:25px;
}

.final-box p{
    font-size:20px;
    line-height:1.8;
    color:#ddd;
}

.signature{
    margin-top:35px;
    color:#ff69c9;
    font-size:24px;
}


/* FOOTER */

footer{
    text-align:center;
    padding:30px;
    color:#888;
}


/* MOBILE */

@media(max-width:800px){

    h1{
        font-size:42px;
    }

    .hero p{
        font-size:17px;
    }

    .cards{
        grid-template-columns:1fr;
    }

    .section-title{
        font-size:32px;
    }

    .distance-number{
        font-size:60px;
    }

    .final-box h2{
        font-size:38px;
    }

}

</style>
</head>


<body>


<!-- HERO -->

<div class="hero">

    <div class="hero-content">

        <div class="small">
            A LITTLE SOMETHING FOR YOU 💌
        </div>

        <h1>
            For My <span>Special Friend</span> ❤️
        </h1>

        <p>
            Distance may keep us far away,
            but somehow you still manage to be there
            whenever I need you.
        </p>

        <button class="start-btn" onclick="scrollToSection()">
            Open This Little Surprise ✨
        </button>

    </div>

</div>



<!-- APPRECIATION -->

<section id="special">

    <h2 class="section-title">
        Things I <span>Appreciate</span> About You 💗
    </h2>


    <div class="cards">

        <div class="card">

            <div class="icon">🫶</div>

            <h3>Your Care</h3>

            <p>
                You somehow notice the little things.
                Even when I don't say anything,
                you still ask if I'm okay.
            </p>

        </div>


        <div class="card">

            <div class="icon">✨</div>

            <h3>Your Compliments</h3>

            <p>
                The way you appreciate me and
                randomly make me feel good about myself
                honestly means more than you probably realize.
            </p>

        </div>


        <div class="card">

            <div class="icon">🤍</div>

            <h3>Always Being There</h3>

            <p>
                Even with all the distance between us,
                you somehow make it feel a little smaller
                just by being there.
            </p>

        </div>

    </div>

</section>



<!-- DISTANCE -->

<section class="distance">

    <h2 class="section-title">
        About This <span>Distance</span> 🌎
    </h2>

    <div class="distance-box">

        <div class="distance-number">
            🌎 ↔️ ❤️
        </div>

        <p>
            We might be in different places,
            different cities and living our own lives...
            but that doesn't change the fact that
            some people can still become important
            even from miles away.
        </p>

        <br>

        <p>
            Maybe distance is annoying 😭
            but at least it gave me one thing —
            a reason to appreciate how special
            our friendship actually is.
        </p>

    </div>

</section>



<!-- SURPRISE -->

<section class="surprise">

    <h2 class="section-title">
        I Have A <span>Little Secret</span> 🤫
    </h2>

    <button class="surprise-btn" onclick="showMessage()">
        Don't Click This 👀
    </button>


    <div class="hidden-message" id="message">

        <h2>Okay... You Clicked It 😭❤️</h2>

        <br>

        <p>
            So here's the truth...
        </p>

        <br>

        <p>
            I may not always say it,
            but I genuinely appreciate having you in my life.
        </p>

        <br>

        <p>
            Your care, your random compliments,
            your availability and the way you actually
            worry about me...
            all of it matters.
        </p>

        <br>

        <h3>
            Thank you for being you. 🫶
        </h3>

    </div>

</section>



<!-- FINAL MESSAGE -->

<section class="final">

    <div class="final-box">

        <h2>
            Until We Meet... ❤️
        </h2>

        <p>
            Until the distance becomes just a memory,
            keep smiling, keep annoying me,
            keep giving me unnecessary compliments 😭
            and most importantly...
            keep being the amazing person you are.
        </p>

        <div class="signature">
            — From someone who appreciates you more than he says ❤️
        </div>

    </div>

</section>



<footer>

    Made with ❤️ and a little bit of ur hardworking boy 

</footer>



<script>

/* Scroll button */

function scrollToSection(){

    document.getElementById("special").scrollIntoView({
        behavior:"smooth"
    });

}


/* Surprise */

function showMessage(){

    let message = document.getElementById("message");

    message.style.display = "block";

    createHearts();

}


/* Floating hearts */

function createHearts(){

    for(let i = 0; i < 20; i++){

        setTimeout(()=>{

            let heart = document.createElement("div");

            heart.classList.add("heart");

            heart.innerHTML =
                ["❤️","💗","💖","💕","✨","🫶"][Math.floor(Math.random()*6)];

            heart.style.left =
                Math.random()*100 + "vw";

            heart.style.fontSize =
                (15 + Math.random()*25) + "px";

            heart.style.animationDuration =
                (4 + Math.random()*4) + "s";

            document.body.appendChild(heart);


            setTimeout(()=>{

                heart.remove();

            },8000);

        },i*150);

    }

}


/* Automatically create a few hearts */

setInterval(()=>{

    let heart = document.createElement("div");

    heart.classList.add("heart");

    heart.innerHTML =
        ["❤️","💗","✨"][Math.floor(Math.random()*3)];

    heart.style.left =
        Math.random()*100 + "vw";

    heart.style.fontSize =
        (15 + Math.random()*20) + "px";

    document.body.appendChild(heart);


    setTimeout(()=>{

        heart.remove();

    },7000);

},1200);

</script>

</body>
</html>
