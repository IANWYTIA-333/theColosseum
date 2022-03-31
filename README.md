<!doctype html>
<html lang="en">
<style>
  /* Create a sticky/fixed navbar */
#navbar {
  overflow: hidden;
  background-color: #d5e7f0;
  padding: 90px 10px; /* Large padding which will shrink on scroll (using JS) */
  transition: 0.4s; /* Adds a transition effect when the padding is decreased */
  position: fixed; /* Sticky/fixed navbar */
  width: 100%;
  top: 0; /* At the top */
  z-index: 99;
}

/* Style the navbar links */
#navbar a {
  float: left;
  color: black;
  text-align: center;
  padding: 12px;
  text-decoration: none;
  font-size: 18px;
  line-height: 25px;
  border-radius: 4px;
}

/* Style the logo */
#navbar #logo {
  font-size: 35px;
  font-weight: bold;
  transition: 0.4s;
}

/* Links on mouse-over */
#navbar a:hover {
  background-color: #add7ed;
  color: black;
}

/* Style the active/current link */
#navbar a.active {
  background-color: dodgerblue;
  color: white;
}

/* Display some links to the right */
#navbar-right {
  float: right;
}

/* Add responsiveness - on screens less than 580px wide, display the navbar vertically instead of horizontally */
@media screen and (max-width: 580px) {
  #navbar {
    padding: 20px 10px !important; /* Use !important to make sure that JavaScript doesn't override the padding on small screens */
  }
  #navbar a {
    float: none;
    display: block;
    text-align: left;
  }
  #navbar-right {
    float: none;
  }
}
  /* Style the Image Used to Trigger the Modal */
#myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (Image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image (Image Text) - Same Width as the Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation - Zoom in the Modal */
.modal-content, #caption {
  animation-name: zoom;
  animation-duration: 0.6s;
}

@keyframes zoom {
  from {transform:scale(0)}
  to {transform:scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}
      .left {
        padding-left: 0px;
      }
      .right {
        padding-right: 0px:
      }
.container {
  max-width:100px
}
  
/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
}
</style>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>the Colosseum</title>
    <link rel="shortcut icon" href="https://cdn.britannica.com/36/162636-050-932C5D49/Colosseum-Rome-Italy.jpg" />

  </head>
  <body>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>

      <h1>the Colosseum </h1>
    <div id="navbar">
  <a href="" id="logo" style="color:ghostwhite;">the Colosseum</a>
  <div id="navbar-right">
    <script>
      window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 90 || document.documentElement.scrollTop > 90) {
    document.getElementById("navbar").style.padding = "30px 10px";
    document.getElementById("logo").style.fontSize = "25px";
  } else {
    document.getElementById("navbar").style.padding = "80px 10px";
    document.getElementById("logo").style.fontSize = "35px";
  }
}

    </script>
  </div>
</div>
    
    <br></br>
    <br></br>
    <br></br>
    <br></br>
    <div class='container'>
      <h3><b>The Original Construction</b></h3>
      <p>The Colosseum is an amphitheatre situated in Rome. It was built as a gift for the Roman people during that time. The construction began around A.D. 70. It took about 10 years for the whole thing to be built and it still had tons of modifications after it was finished. Its shape wasn’t exactly a circle. It was about 189 metres by 156 metres. Its 48 metres tall! Not only was it huge but it had 80 entrances! 2 of those were just for the emperor! It was used mainly to host gladiatorial fights or even public executions.</p>
      <hr>
      <h3><b>Features</b></h3>
      <h4><b>A.D. 70 – A.D. 80</b></h4>
      <p>The Roman Colosseum is a Roman Amphitheatre that was built under Flavian and Titus, his son. Its construction began around A.D. 70. It was completed in A.D. 80 and is still standing today. It wasn’t made with any old rock, it was made using specific rocks chosen to help it stand for a while. At the base it was made of tuff (a rock made with volcanic ash), lime and other materials. The whole thing was made of travertine, tuff, concrete, bricks, iron clamps, marble, lime, mortar, and stone. At the time it was situated around the middle of Rome to allow easier access.</p>
      <hr>
      <h4><b>Use & Purpose</b></h4>
      <p>It was built for gladiator fights, public executions and shows. Around 400,000 gladiators were killed battling in the Colosseum. About 100,000 animals were killed in the Colosseum too. Its purpose was to entertain the Roman people at the time. It was only used for entertainment for about 300-400 years. It could house about 50,000 people at once, about an 18th of the whole population at the time.</p>
      
      <p>The battles that took place weren’t basic. Gladiators did have fights against animals and other gladiators in the Colosseum, but these weren’t the only things that happened. Emperors also hosted ‘mock naval battles’ in the Colosseum. They would flood the entire Colosseum with water and place boats inside to host recreations of naval battles in the Colosseum. Events would cost about 175,000 sesterces (a Roman coin) for the emperor to pay.</p>

<svg xmlns="http://www.w3.org/2000/svg" style="display: none;">
  <symbol id="check-circle-fill" fill="currentColor" viewBox="0 0 16 16">
    <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zm-3.97-3.03a.75.75 0 0 0-1.08.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-.01-1.05z"/>
  </symbol>
  <symbol id="info-fill" fill="currentColor" viewBox="0 0 16 16">
    <path d="M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16zm.93-9.412-1 4.705c-.07.34.029.533.304.533.194 0 .487-.07.686-.246l-.088.416c-.287.346-.92.598-1.465.598-.703 0-1.002-.422-.808-1.319l.738-3.468c.064-.293.006-.399-.287-.47l-.451-.081.082-.381 2.29-.287zM8 5.5a1 1 0 1 1 0-2 1 1 0 0 1 0 2z"/>
  </symbol>
  <symbol id="exclamation-triangle-fill" fill="currentColor" viewBox="0 0 16 16">
    <path d="M8.982 1.566a1.13 1.13 0 0 0-1.96 0L.165 13.233c-.457.778.091 1.767.98 1.767h13.713c.889 0 1.438-.99.98-1.767L8.982 1.566zM8 5c.535 0 .954.462.9.995l-.35 3.507a.552.552 0 0 1-1.1 0L7.1 5.995A.905.905 0 0 1 8 5zm.002 6a1 1 0 1 1 0 2 1 1 0 0 1 0-2z"/>
  </symbol>
</svg>

<div class="alert alert-primary d-flex align-items-center" role="alert">
  <svg class="bi flex-shrink-0 me-2" width="24" height="24" role="img" aria-label="Info:"><use xlink:href="#info-fill"/></svg>
  <div>
    <i>Did you know?</i> When the Colosseum was flooded the water went up to almost 2 metres high!
  </div>
</div>
      
      <hr>
      <div class="card">
  <img src="OldColosseum1.png" class="card-img-top" alt="..." height='270' style="max-width: 750px;">
  <div class="card-body">
    <h5 class="card-title"><b>The Original Look</b></h5>
    <p class="card-text">The Colosseum looked different before! It didn’t have the orange/taupe colour it has now. According to a research project in October 2013, it said that the original colour of the Colosseum <i>could</i> have been red. The Colosseum did not have the ‘<i>broken</i>’ part of wall it has today. Parts of the Colosseum were stripped off and sold for another purpose. Some were broken down due to earthquakes over hundreds of years. Only about a third of the original Colosseum is standing today. It may look like it is still intact but in reality, time has shaped the structure a lot</p>
</div>
      </div>
      
      <hr>
      <h4><b>What happened to it over 2,000 years?</b></h4>
      <p>Many activities were hosted for a long period of time. After a while people began to abuse it and use it incorrectly. It was neglected, misused and many unfortunate things happened to it. In 1349 an earthquake damaged part of it, but it is still standing after about two thousand years. After many years of, in the 1900s when the Roman government decided to put more effort into preserving it.</p>
      <hr>

      <div class="card">
  <img src="Hypogeum1.png" class="card-img-top" alt="..." height='300' style="max-width: 600px;">
  <div class="card-body">
    <h5 class="card-title"><b>The Colosseum's Hypogeum</b></h5>
    <p class="card-text">If you have looked at the Colosseum you might think there is something under. Well, there is! The hypogeum is an underground chamber or tomb where animals, resources and costumes were stored. Animals and gladiators would come out from a trapdoor situated in the hypogeum. It had many passages inside it and two bigger tunnels to allow it to be easier to move around and access things. It was only built about 10 years after A.D. 80.</p>
    <div class="accordion" id="accordionPanelsStayOpenExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsStayOpen-headingFour">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseFour" aria-expanded="true" aria-controls="panelsStayOpen-collapseFour">
        Image showing the Hypogeum
      </button>
    </h2>
    <div id="panelsStayOpen-collapseFour" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingThree">
      <div class="accordion-body">
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="panelsStayOpen-headingOne">
        <img src="Hypogeum2.jpeg" class="card-img-top" alt="..." height='300' style="max-width: 600px;">
        <hr>
      The image above shows the Hypogeum today
      </div>
    </div>
  </div>
</div>
  </div>
  </div>
</div>
      <hr>
            <div class="card">
  <img src="Velarium1.png" class="card-img-top" alt="..." height='300' style="max-width: 600px;">
  <div class="card-body">
    <h5 class="card-title"><b>The Velarium</b></h5>
    <p class="card-text">Looking up at the Colosseum, you might realise that there is no roof. You might think that when it was used there was no shade so it must have been very hot on sunny days, but a large awning called the ‘velarium’ was used to shade people in the Colosseum. It was not designed to be used on rainy days, it was only taken out on sunny days. It was detachable and you would hang it up when it was needed. It was predicted that it was made up of linen or fabric. The word ‘Velarium’ originated from a Latin word meaning ‘sail’. It was extremely big, so it needed several days to be pulled up. It was a boring task, and it took around 1,000 men just to pull it up.</p>
    <div class="accordion" id="accordionPanelsStayOpenExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsStayOpen-headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseTwo" aria-expanded="true" aria-controls="panelsStayOpen-collapseTwo">
        Larger image of the Velarium
      </button>
    </h2>
    <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingTwo">
      <div class="accordion-body">
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="panelsStayOpen-headingOne">
        <img src="ColosseumOLD1.jpeg.crdownload" class="card-img-top" alt="..." height='300' style="max-width: 600px;">
        <hr>
        The image above shows the Colosseum being used with the <i>Velarium</i> present in the picture.
      </div>
    </div>
  </div>
</div>
  </div>
  </div>
</div>
      <hr>
      <h4><b>Seating</b></h4>
      <p>The Colosseum wasn’t just big, it could house around 50,000 people! The seats weren’t made as if it was a football stadium, they were made to reflect on Ancient Roman hierarchy and status. The higher your status, the lower you sit in the seats. The lower your stats (e.g. slave, woman), the higher you sit in the seats. People like senators, magistrates and priests were in the front row.</p>
<div class="alert alert-warning d-flex align-items-center" role="alert">
  <svg class="bi flex-shrink-0 me-2" width="24" height="24" role="img" aria-label="Warning:"><use xlink:href="#exclamation-triangle-fill"/></svg>
  <div>
    <i>Did you know?</i> It is estimated that over 90% of the Colosseum seats were for poor people.
  </div>
</div>
<div class="accordion" id="accordionPanelsStayOpenExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="panelsStayOpen-headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="true" aria-controls="panelsStayOpen-collapseThree">
        Image showing the seating in the Colosseum
      </button>
    </h2>
    <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingThree">
      <div class="accordion-body">
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="panelsStayOpen-headingOne">
        <img src="Ch-4-Seating-in-the-Arena.png" class="card-img-top" alt="..." height='300' style="max-width: 600px;">
        <hr>
      The image above shows the Colosseum with the seating and hierarchy
      </div>
    </div>
  </div>
</div>
  </div>
      <hr>
      <h4><b>The End</b></h4>
      <p>Over hundreds of years the Colosseum has been many things, from 'castles' to its normal purpose, a Roman Amphitheatre. It is luckily the oldest ampitheatre ever built that is standing today!</p>
      <hr>
    </div>
  </body>
</html>
