<!DOCTYPE html> <!--This is the main tag-->
<html lang="en">
<head>
    <meta charset="UTF-8"> <!--This the character set tag-->
    <meta http-equiv="X-UA-Compatible" content="IE=edge"> <!--this is again the browser compatibilty tag-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!--this is for the type of device-->
    <title>LegendsForever</title> <!--This is the tab name of the website-->
    <link rel="stylesheet" href="css/main.css"> <!--this tag helps us link the html document to the css doc-->
</head>
<body> <!--This is where all the action starts-->
   <div class="navbar"> <!--This is one of the most used tags. It classifies this division as navbar-->
       <div class="container">
           <a class="logo" href="#">Legends<span>Forever</span></a> <!--this is the hyperlink tag-->
                <!--The span tag is used to diffreciante two parts in a sentence-->
           <img id="mobile-cta" class="mobile-menu" src="Images/menu.svg" alt="Menu icon"> <!--The id attribute is used for javascript and class is used for css edits-->
           <nav> <!--The nav tag is used for navigations links and also helps screen readers-->
               <img id="mobile-exit" class="mobile-menu-exit" src="images/exit.svg" alt="Exit Menu">
               <ul class="primary-nav"> <!--THe ul tag is used for unordered lists.-->
                   <li class="current"><a href="#">Home</a></li> <!--The li tag is used for one list under ul tag.-->
                   <li><a href="#">About us</a></li><!--All these are for links to different parts of the website-->
                   <li><a href="#">Features</a></li>
               </ul>
              
               <ul class="secondary-nav">
                <li><a href="#">Clashing tips</a></li>
                <li class="community"><a href="#">Join our Community</a></li>                
            </ul>
           </nav>
       </div>
   </div> 
   
   <section class="hero ">
       <div class="container">
        <div class="left-col">
            <p class="subhead">The best was to start clashing!</p>
            <h1>A community that helps you turn into a pro clasher</h1>

            <div class="hero-cta">
                <a href="#" class="primary-cta">Subscribe today</a>
                <a href="#" class="watch-video-cta">
                    <img class="learn-more" src="images/learn-more.svg" alt="Learn more">Learn more 
                </a>
            </div>
        </div>
        <img src="images/illustration.svg" class="hero-img" alt="Illustration">

       </div>
   </section>

   <section class="features-section">
       <div class="container">
        <ul class="features-list">
            <li>Attacking strategies</li>
            <li>Townhall 1-Townhall 14 gameplay</li>
            <li>Free to play series</li>
            <li>Huge community</li>
            <li>Best base designs</li>
            <li>Video based content</li>
        </ul>

        <img class="base-des" src="Images/coc.jpg" alt="A base design">        
       </div>
   </section>

   <section class="players-section">
       <div class="conatainer">
           <ul>
               <li>
                   <img class="player1" src="images/player1.jpg" alt="Klaus's Review">
                   
                   <blockquote>"Good content for begginers and amaterus. The attack strategies in particular are very creative and effective</blockquote>
                   <cite>Klaus</cite>                                
                </li>
                <li>
                    <img class="player2" src="images/player2.jpg" alt="Klaus's Review">
                    
                    <blockquote>"Good content for begginers and amaterus. The attack strategies in particular are very creative and effective</blockquote>
                    <cite>Judo Sloth</cite>                                
                 </li>
                 <li>
                    <img class="player1" src="images/player1.jpg" alt="Klaus's Review">
                    
                    <blockquote>"Good content for begginers and amaterus. The attack strategies in particular are very creative and effective</blockquote>
                    <cite>Klaus</cite>                                
                 </li> 
           </ul>
       </div>
   </section>

   <section class="contact-section">
       <div class="container">
           <div class="contact-left">
               <h2>Contact us</h2>

               <a href="https://forms.gle/3SdetAUXWyLXQNuH6" class="form" target="_blank">
                <img class="forms-logo" src="images/forms-logo.svg" alt="Fill out the form">
            </a>             
               <a href="mailto:krishangm1@gmail.com" class="email" >
                   <img class="mail-logo" src="images/mail-icon.svg" alt="Mail us">
               </a>          
               <a href="https://www.instagram.com/clashofclans/" class="Instagram page" target="_blank">
                    <img class="instagram-logo" src="images/instagram-logo.svg" alt="Instagram page">
            </a>               
           </div>

            <div class="contact-right">
                <iframe src="https://supercell.com/en/games/clashofclans/" frameborder="0" allowfullscreen="" height="550px" width="800px" aria-hidden="false" tabindex="0"></iframe>
            </div>
       </div>
   </section>
   <h5 class="copyright">&copy;Content owned by krishang and all rights reserved by the owner</h5>
</body>
</html>
