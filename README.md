# 2ndmaomao.github.io
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Webpage</title>
  <style>
    body {
      background-image: url("Maomao (1).jpg");
      background-size: cover;
      background-position: centre;
      background-repeat: no-repeat;
      background-attachment: fixed;
      margin: 0;
      font-family: sans-serif;
    }
  .square-card {
  width: 180px;           /* Sets the box width */
  height: 180px;          /* Sets the box height equal to width for a square */
  float: left;            /* Moves the box to the left margin */
  margin-right: 20px;     /* Adds breathing room between the box and your text */
  overflow: hidden;       /* Crops anything outside the square boundaries */
  border-radius: 6px;     /* Optional: rounds the corners of the box */
}
/* Forces the image to fill the square box cleanly */
.square-card img {
  width: 100%;
  height: 100%;
  object-fit: cover;      /* Preserves aspect ratio while filling the square */
}
    .animated-card {
      opacity:0 ;
    transfrom:translateY(30px);
    animation:slideUpFade 0.8s ease-out forwards ;
    }
    @keyframes slideUpFade {
    from{
    opacity: 0;
      transfrom:translateY(30px);}
      to{
      opacity: 1;
        transfrom:translateY(0);}
        }
        btn {
        display: inline-block;
        background: linear-gradient(135deg, var(--accent-yellow), #ea580c);
        color: black;
        padding: 0.8rem 2rem;
        border-radius: 5px;
        text-decoration: none;
        font-weight: bold;
        transition: transform 0.3s, box-shadow 0.3s;
    }
      



    
    </style>
    <body>
<div class="square-card">
    <img src=" download (5).jpg" align="left" width="50" style="margin-right:20px ;"  alt= "Descrpition">
</div>
   <div class="animated-card"> <p> ox bezoar<br>
    aaaaadkdfjoifjiushffff </p>
   </div>
    
    <div><br clear="left">
    </div >
     <footer>
        <a href="https://ayana-sarkar.github.io/1st_rough_jjk/" class="btn" > Home </a>
    </footer>
</body>
</html>
