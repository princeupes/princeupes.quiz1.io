*{
    box-sizing:border-box;
}
body{
margin:0;
background-color:#000;
font-family:sans-serif;
}
.quiz-container{
 max-width: 700px;
 min-height:500px;
 background-color: #000;
 margin:40px auto;

 border-radius:10px;
 padding:30px;
}
.quiz-container::after,.quiz-container::before{
 content: ' ';
 clear: both;
 display: table;

}
.question-number,
.question,
.options,
.button,
.answers-tracker{
 float: left;
 width: 100%;
}
.question-number h3{
 color:lime;
 border-bottom: 3px dotted cyan;
 
 margin:0;
 padding-bottom:10px;
}

.question {
 font-size:24px;
 color:#f00;
 padding:20px 0;
 font-weight:bolder;

}

.options div{
  background-color: #000;
  font-size:18px;
  color:cyan;
  margin-bottom:10px;
  border-radius:3px;
  padding:15px;
  position: relative;
  overflow:hidden;
  cursor: pointer;
  font-weight:bold;
}
.options div.disabled{
 pointer-events: none;
}
.options div.correct{
 z-index: 1;
 color: #fff;
}
.options div.correct::before{
 content: '';
 position: absolute;
 left:0;
 top:0;
 width: 100%;
 height: 100%;
 background-color:#0f0;
 z-index: -1;

 animation: anima 1s ease;
 animation-fill-mode: backwards;
}
@keyframes anima{
 0%{
  transform: translateY(-50%);
 }
 100%{
  transform: translateX(100%);
 }
}
.options div.wrong{
 z-index: 1;
 color: #fff;
}
.options div.wrong::before{
 content: '';
 position: absolute;
 left:0;
 top:0;
 width: 100%;
 height: 100%;
 background-color:#f00;
 z-index: -1;

 animation: anim 1s ease;
 animation-fill-mode: backwards;
}
@keyframes anim{
 0%{
  transform: translateY(-100%);
 }
 100%{
  transform: translateX(100%);
 }
}

.button .btn{
 padding:15px 50px;
 border-radius: 0px 6px 0px 6px;
 cursor: pointer;
 background-color:rgba(20,250,20,0.5);
 font-size:18px;
 color:#ffffff;
 border: none;
 display: inline-block;
 margin:15px 0 20px;
 outline:none ;
}
.answers-tracker{
 border-top:1px solid #ccc;
 padding-top: 15px;
}
.answers-tracker div{
 height: 40px;
 width: 40px;
 background-color: #cccccc;
 display: inline-block;
 border-radius: 50%;
 margin-right:5px;
}

.answers-tracker div.correct{
 background-color:black;
 background-image:url('https://www.dropbox.com/s/9s44gs1p3rxt091/tick1.png?dl=1');
 background-position: center;
 background-repeat: no-repeat;
 background-size: 100%;

}
.answers-tracker div.wrong{
 background-color:#000;
 background-image:url('https://www.dropbox.com/s/8ec45praptsde52/w.png?dl=1');
 background-position: center;
 background-repeat: no-repeat;
 background-size: 100%;
}

.quiz-over{
 position: fixed;
 left:0;
 top:0;
 width: 100%;
 height: 100%;
 background-color:rgba(0,0,0,1);
 z-index: 10;
 display: none;
 align-items: center;
 justify-content: center;
}
.quiz-over.show{
 display: flex;
}
.quiz-over .box{
 background-color: #000;
 padding:30px;
 border-radius:5px;
 text-align: center;
 flex-basis: 700px;
 max-width:700px;
 color:lime;
}

.quiz-over .box h1{
 font-size:36px;
 margin:0 0 20px;
}

.quiz-over .box button{
 padding:15px 50px;
 border:none;
 background-color:#000;
 border-radius:0px 5px 0px 5px;
 font-size:20px;
 margin:15px 0 20px;
 color:#f00;
}
