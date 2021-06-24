# Tribute-Project
The first project for Freecodecamp

<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>CodePen - Tribute page</title>
  <link rel="stylesheet" href="./style.css">

</head>
<html>
  
  
<body>
<!-- partial:index.partial.html -->

<title> 
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</title>
<body>

    <div id="main">
          <figure id="img-div"> 
           
    <img id="image" src="https://i.ibb.co/5Rn55mC/Three-eyed-ravin.png">
            <figcaption id="img-caption">
           Three-eyed Ravin
         </figcaption>
  </figure>
        <h1 id="title">Three-Eyed Raven</h1>
         <p>The Three-Eyed Raven was the last greenseer, a human living among the last of the Children of the Forest beyond the Wall. His real name is unknown. Under the guise of a three-eyed raven, he appears in Bran Stark's vision-dreams, following his fall and injury, prompting his quest beyond the Wall and guiding him to the cave in which his real human body resides. There, Bran is trained in the magic of Greensight.</p>  
       
            
  <section id="tribute-info">       <h2>Appearances</h2>
 <ul>
            <li>Season One appearances: After his fall from the tower and awakening from the subsequent coma, the raven appears to Bran Stark multiple times in his dreams. In them, it appears as Bran is about to fire an arrow and causes him to stop before he shoots. Then, the raven lands on the head of a direwolf statue, cries once and then flies deep into the Stark family crypt.</li>  
            <li>Season Two appearances: Bran asks Osha about the significance of the Three-Eyed Raven but she does not divulge anything.

                The Three-Eyed Raven watches Maester Luwin send ravens as Theon is attacking Winterfell.</li> 
            <li>Season There appearances: While traveling north, Bran dreams once again of the Three-Eyed Raven. In the dream he's able to walk and attempts to shoot at him with a bow and arrow. A strange boy then appears in the dream, and tells Bran that he cannot kill the raven, because Bran is the raven.</li> 
            <li>Season Four appearances: Bran and his group eventually reach the giant weirwood tree on the hill, but are attacked by a group of wights hiding beneath the ice. Jojen is fatally stabbed and Meera attempts to save him, but Jojen tells her to leave him for dead. They are helped by a child of the forest, who leads them into a cave. 
            <li>Season Six appearances: The Three-Eyed Raven monitors Bran as he experiences a vision of Winterfell during the childhood of Lyanna and Ned Stark that reveals Hodor's true name, Wylis. 
            </li>  
        </ul>
        <hr>
        <hr>
    </section>
                   
        <q>I have been watching you. All of you. All of your lives, with a thousand eyes and one.</q>   
        </div>   
       <footer>
            <a href="https://gameofthrones.fandom.com/wiki/Three-Eyed_Raven" id="tribute-link" target="_blank" rel="noopener noreferrer">For More Information On <i class="fas fa-crow"></i>, Click Here.</a>
    </footer>
      
</body>
</html>
<!-- partial -->
body {
    background: url(https://s3-us-west-2.amazonaws.com/s.cdpn.io/1415658/wood_1_%402X.png);
}



#main {
    background: url("https://www.toptal.com/designers/subtlepatterns/patterns/ricepaper.png");
    filter: sepia(25%);
    padding:  20px 25px;
    margin: 30px 30px;
    border-radius: 25px;
    line-height: 1.6rem;
    box-shadow: currentColor;
    width: 50rem;
    height: 70rem;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;   
 
}



#title {
        color: #000000;
        text-shadow: 2px 2px 4px #abb863;
        font-size: 30px;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
  
}



ul {
    font-weight: initial; 
    font-size: 1rem;
  }
li:hover {
    background-color: rgb(218, 226, 198);
  }

#image {

  height: auto;
  border-radius: 10px;
  object-fit: cover;
  max-width: 100%;
  display: block;
 margin:auto;
}


#img-div {
     padding: 20px;
     background-color:rgb(191, 206, 168);
     height: 23em;
     margin: 0 auto;
      text-align: center;
}

#img-caption{
     size:small;
     padding:1px;
}


q {
    font-style: italic;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; 
    font-weight: bolder;
    padding: 50px 40px;
    font-size: 15px;
}



footer {
    text-align: center;
}
    


a[target="_blank"] {
    background-color: rgb(226, 253, 162);
    text-align: center;
}
