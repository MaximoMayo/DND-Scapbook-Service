# DND-scapbook-service
 This website will be dedicated to note taking and memorialising the fond moments when playing DND. An interactive and intuitive website to make keeping track of whats happening in a session more fun and impactful.

![Screenshot](https://github.com/MaximoMayo/DND-Scapbook-Service/blob/main/images/readMeImage1.png)
![Screenshot](https://github.com/MaximoMayo/DND-Scapbook-Service/blob/main/images/readMeImage2.png)
![Screenshot](https://github.com/MaximoMayo/DND-Scapbook-Service/blob/main/images/readMeImage3.png)
![Screenshot](https://github.com/MaximoMayo/DND-Scapbook-Service/blob/main/images/readMeImage4.png)
![Screenshot](https://github.com/MaximoMayo/DND-Scapbook-Service/blob/main/images/readMeImage5.png)

I enjoyed this entire snippet where I challenged myself to figure it out without using a premade format and being a little creative
/* Scrapbook styles */
#scrapbookBg{
    background-image: url("https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcS5Z1oXI_qgNiG0qj_4Yg817_bGGJ-qhV-PKVwyTEPuyi9cIhjB");
    background-size: 100%;
    background-repeat: no-repeat;
    width: 49%;
    margin-bottom: 65px;
}

#scrapbookImg{
    width: 100%;
    padding-left: 130px;
    padding-top: 120px;
    padding-right: 150px;
}

#scrapbookText{
    background-image: url("https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcS5Z1oXI_qgNiG0qj_4Yg817_bGGJ-qhV-PKVwyTEPuyi9cIhjB");
    background-repeat: no-repeat;
    background-size: 1000px 1000px;
    margin-bottom: 65px;
}

#largeScrapbookBg{
    background-image: url("https://i.redd.it/ya3vuzyoh3z81.jpg");
}

.containerScrapbook{
    border-style: solid;
    border-color: black;
    border-radius: 2%;
    border-width: 5px;
}



<main>
         <div class="container linkBgSetNew">
            <div class="d-flex justify-content-center">
               <div class="container-fluid">
                  <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                     data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                     aria-label="Toggle navigation">
                     <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" fill="currentColor" class="bi bi-list" viewBox="0 0 16 16">
                        <path fill-rule="evenodd" d="M2.5 12a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5m0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5m0-4a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 0 1H3a.5.5 0 0 1-.5-.5"/>
                     </svg>
                  </button>
                  <div class="collapse navbar-collapse" id="navbarSupportedContent">
                     <ul id="addingNumbersList" class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                           <a class="nav-link active" aria-current="page" href="#">Campaign Book Cover</a>
                        </li>
                        <li class="nav-item">
                           <a class="nav-link" href="#">Campaign Description</a>
                        </li>
                        <li class="nav-item dropdown ">
                           <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button"
                              data-bs-toggle="dropdown" aria-expanded="false">
                           Session #
                           </a>
                           <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                              <li><a class="dropdown-item" href="/index.html">Session 0</a></li>
                              <li><a class="dropdown-item" href="#">Session 1</a></li>
                              <li><a class="dropdown-item" href="#">Session 2</a></li>
                           </ul>
                        </li>
                     </ul>
                  </div>
               </div>
            </div>
         </div>
         <div id="largeScrapbookBg">
            <div class="d-flex flex-wrap justify-content-center text-dark">
               <h1>Way Down Under</h1>
            </div>
            <div class="d-flex flex-wrap justify-content-center text-dark pb-5">
               <h4>Session 0</h4>
            </div>
            <div class="container text-dark">
               <div class="row">
                  <div class="col-6 containerScrapbook" id="scrapbookBg">
                     <img src="https://i.pinimg.com/736x/fe/d3/ae/fed3aefe44b870230a3c3c953c49fd0c.jpg" alt="dnd picture" id="scrapbookImg">
                  </div>
                  <div class="col-5 containerScrapbook" id="scrapbookText">
                     <blockquote>
                        I created a half-elf bard named Lirael Moonshadow. 
                        He grew up in a small village where he learned to play the lute and sing from his elven mother. 
                        After a tragic event, he set off on a journey to hone his skills and seek adventure. 
                        Armed with his musical talents, a quick wit, and a desire to bring joy to those he meets, 
                        Lirael uses his charisma and charm to navigate the dangerous world of dungeons and dragons.
                     </blockquote>
                     <blockquote>
                        Name: Lirael Moonshadow<br>
                        Race: Half-Elf<br>
                        Class: Bard<br>
                        Background: Entertainer<br>
                        Alignment: Chaotic Good<br>
                        Strength: 10<br>
                        Dexterity: 14<br>
                        Constitution: 12<br>
                        Intelligence: 13<br>
                        Wisdom: 10<br>
                        Charisma: 16<br>
                        Hit Points: 8<br>
                        Armor Class: 11<br>
                        Speed: 30 ft<br>
                        Skills: Persuasion, Performance, Acrobatics, Deception<br>
                        Equipment: Lute, dagger, entertainer's pack, leather armor, rapier<br>
                        Abilities: Bardic Inspiration, Jack of All Trades, Song of Rest
                     </blockquote>
                  </div>
               </div>
            </div>
         </div>
      </main>

