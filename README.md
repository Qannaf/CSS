# CSS

## 1. Afichage et posiyionnement - image
* Afichage et posiyionnement - image.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>Afichage et positionnement</title>
    <link rel="stylesheet" href="Afichage et posiyionnement - image.css">
</head>
<body>
    <h1>Bonjour!</h1>
        <img class=" fLeft" src="v.jpg" alt="" >
        <p>
            Bhello jfync kjhu ksyf kjhfj tout le monde comment cv va vous allez bien moi je vais bien merci bcp jdj zkjhdkjz kjhduhd jahduhd jhduedh hduzehd zeehdlidhid hdudh khdudh hdiéhd hdhd diododj ehduhd hduehd uhduh
            aaa  firste phrase en english hello worled  </p>
        
        <p> Bhello jtout le monde comment cv va vous allez bien moi je vais bien merci bcp
            sjdj  firste phrase en english hello worled jhlée ékjdhkhéd kjhdked jdkhd khadkha kjahdkhd jahdkhd khdudhhdkhd 
        khdkhd adjlhd dhlkabdd dhkdhd jhdjhd hdkh zddg hdgd hdgd hghfhgf hghgf hhgch fhgfhgqf dfhfkjhf jhfhdfd jhfjddf dhhfjkhf khfjkdf jdhfjdhf dhfjhfh fkjhfjhdf hdhdhd hbdhdhd hdhgdh hhgdhdghjsd shdhgdhjd kkkhd jhkhd jhhdhd hkhdd jqhdhd hdhhjd jhddhjd hdkhdkj khdkhd hkhjkhekh khfkhf  jhh kfh jfkhf jhj jhfhf hfkzf kf hqd kjhdhhd jhdkhdkd hghdgsd hdhsgsdghd dhjgdhdg  jhfhf kjhfkjh kjjfkhf khjkqhf d adhddkze zjdkjd kjdhhd khdh jh gdcyd khdy jdyd kldt dkdt mhdu  dlyd hyf lkcbu flyf lfhudf lssyf ifyèf oifyidyf qkfyf fuyussh ufhdiuf iff h doad dyd oid i dodyd aldyd dlmyd ohddbad_db oayd çd_dbdoièdz dyadh </p>
    <hr>

    <header>
        Bonjour!
    </header>
    <section>
        <p> Bhello jtout le monde comment cv va vous allez bien moi je vais bien merci bcp
            sjdj  firste phrase en english hello worled jhlée ékjdhkhéd kjhdked jdkhd khadkha kjahdkhd jahdkhd khdudhhdkhd 
        khdkhd adjlhd dhlkabdd dhkdhd jhdjhd hdkh zddg hdgd hdgd hghfhgf hghgf hhgch </p>
    </section>
    <aside>
        <img class=" fLeft" src="v.jpg" alt="" >
        <p>Bhello jfync kjhu ksyf kjhfj tout </p>
    </aside>
    <footer>
  hhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhh
    </footer>   
</body>
</html>
````

* Afichage et posiyionnement - image.css
```CSS
/* Un commentaire*/
/*
    1) display, visibility, opacity
    2) position : relative, absolute, fix   left,top,z-index
    3) flota
    4) clear



*/


html
{
    background-color: #FFF;
    background-color: rgb(36, 185, 173);
}



body
{
    background-color: #DDD;
    margin: auto;
    width: 1000px;   
}

.fLeft
{
    float: left;
    /*float: right;*/
}
.header
{
    clear:left;
    background-color: indigo;
    margin: auto;
    width: 80px;
    height: 1000px;
}

.section
{
    background-color: rgb(0, 130, 65);
    margin: auto;
    height: 800px;
    width: 300px;
}
.footer
{
    background-color: rgb(13, 15, 138);
    margin: auto;
    width: 30px;
    height: 1000px;
}

.aside
{
    background-color: rgb(172, 228, 19);
    margin: auto;
    width: 200px;
}
````
### Output
![alt text](images/01.PNG?raw=true "sortie de code")





## 2. Afichage et posiyionnement
* Afichage et posiyionnement.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>Afichage et positionnement</title>
    <link rel="stylesheet" href="Afichage et posiyionnement.css">
</head>
<body>
    <h1>Bonjour!</h1>
        <img src="v.jpg" alt="" ><img src="v.jpg" alt="" >
        <p>
            Bhello jfync kjhu ksyf kjhfj tout le monde comment cv va vous allez bien moi je vais bien merci bcp jdj zkjhdkjz kjhduhd jahduhd jhduedh hduzehd zeehdlidhid hdudh khdudh hdiéhd hdhd diododj ehduhd hduehd uhduh
            aaa <span class="a"> firste phrase en english hello worled  </span> jhgjhg jhgug khkhku 
        </p>
    <h2>Titre 2</h2>
        <p>
            Bhello jtout le monde comment cv va vous allez bien moi je vais bien merci bcp
            sjdj <span class="b"> firste phrase en english hello worled </span>
        </p>
    
    
    <!----<img src="1.jpg", alt="image1" > ---->



<hr>
    <h1>2 éme partie</h1>
    <div class="aa">Dev1 </div>
    <div class="bb">Dev2 </div>
    <div class="cc">Dev3</div>
</body>
</html>
````

* Afichage et posiyionnement.css
```CSS
/* Un commentaire*/
/*
    1) display, visibility, opacity
    2) position : relative, absolute, fix   left,top,z-index
    3) flota



*/


html
{
    background-color: #FFF;
    background-color: rgb(36, 185, 173);
}



body
{
    background-color: #DDD;
    margin: auto;
    width: 1000px;   
}

p
{
    border: 1px dashed black;
    /*display: inline;*/
    /*display: inline-block;*/
    /*visibility: hidden;*/
}

.a{display: inline-block;}
.b{display: list-item;}

img
{
    opacity: 0.5;
}
img:hover
{
    opacity: 1;
}

div
{
    width: 40px;
    height: 50px;
}
.aa{background-color:red;}
.bb
{
    background-color:white;
    position: relative;
    /*left: 100px;*/
}
.cc{background-color: black;}


````
### Output
![alt text](images/02.PNG?raw=true "sortie de code")




## 3. Boite
* Boite.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>Boite</title>
    <link rel="stylesheet" href="Boite.css">
</head>
<body>
    <div>
        <p>
            Bonjour! tout le monde comment cv va vous allez bien moi je vais bien merci bcp .......................
            .......................................................................................................
            ....
        </p>
    </div>    

</body>
</html>
````

* Boite.css
```CSS
/* Un commentaire*/

/*         1) width, min-width, max-width
           2) Marge interieur :   padding, padding-top, adding-left,...
           3) Marge exterieur :   margin 
           4) overflow        :   auto,scroll,  overflow-x,overflow-y,overflow-warp
           5)                    */


html
{
    background-color: #FFF;
    background-color: indigo;
}
body
{
    background-color: #DDD;
    width: 400px;
    height: 500px;
}
div
{
    background-color: #888;
    width: 200px;
    height: 400px;
}
p
{
    background-color: #c76f6f;
    width: 100px;
    height: 50%;
    padding: 30px 20px 50px 15px;
    margin: 30px ;
    /*overflow-x: scroll;*/
    /*overflow-wrap: break-word;*/
   /* overflow-wrap: ;*/
    
}
````
### Output
![alt text](images/03.PNG?raw=true "sortie de code")



## 04. BoiteAvannce
* BoiteAvannce.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>Boite</title>
    <link rel="stylesheet" href="BoiteAvance.css">
</head>
<body>
    <div id="div1">
        <p>
            div1 Bonjour! tout le monde comment cv va vous allez bien moi je vais bien merci bcp 
            skjj kHDKJ QSKDJHQSD LKHDQ DHQSD DIHDhd DdhD 
        </p>
    </div>    


    <hr>
    <div id="div2">

        <div class="block1">
            block1 Bonjour! tout le monde comment cv va vous allez bien moi je vais bien merci bcp 
            skjj kHDKJ QSKDJHQSD LKHDQ DHQSD DIHDhd DdhD 
        </div>
        <div class="block2">
            block2 Bonjour! tout le monde comment cv va vous allez bien moi je vais bien merci bcp 
            skjj kHDKJ QSKDJHQSD LKHDQ DHQSD DIHDhd DdhD 
        </div>
    </div>    

</body>
</html>
````

* BoiteAvannce.css
```CSS
/*                  */


body
{
    background-color:gray;
    width: 600px;
    margin: auto;
}
#div1
{
   background-color: honeydew;
   border: 1px solid #333;
   box-shadow: 0 0 3px #111;
   margin-top: 50px;
   padding: 5px;  
}

#div2{border: 3px solid darkblue;}
#div2.block1, .block2
{
    width: 100%;
}


.block1, .block2
{
    box-sizing: border-box;
}

.block1{ background-color: hotpink;}
.block2
{ 
    background-color: rgb(150, 105, 255);
    border: 5px dashed red; 
    padding: 15%;
    outline:10px solid rgb(216, 202, 11);
}
````
### Output
![alt text](images/04.PNG?raw=true "sortie de code")












## 5. Bordures & contours
* Bordures & contours.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>Bordures & contours</title>
    <link rel="stylesheet" href="Bordures & contours.css">
</head>
<body>
    <div>
        <p>
            Bonjour! tout le monde comment cv va vous allez bien moi je vais bien merci bcp .......................
            .......................................................................................................
            ....
        </p>
    </div> 
    
    <!----<img src="1.jpg", alt="image1" > ---->

</body>
</html>
````

* Bordures & contours.css
```CSS
/* Un commentaire*/
/*          1) border      :  <width> <style> <color>
                              border-width:
                              border-style:dotted, dashed, solid, double, groove, ridge, inset, outset
                              border-color:
                border-top,left ....
            2) border-image : border-image.com
            3) border-radius: border-top-left-radius
            4) outline      :



*/


html
{
    background-color: #FFF;
    background-color: rgb(36, 185, 173);
}

body,div,p{margin: auto;}

body
{
    background-color: #DDD;
    border: 5px dashed blue;
    /*border-top: 5px dashed blue;*/
    border-radius:  35px;
    outline:5px double rgb(255, 0, 0) ;
    outline-offset: 12px;
    width: 400px;
    height: 500px;
    
}

div
{
    background-color: #888;
    width: 200px;
    height: 400px;
}

p
{
    background-color: #c76f6f;
    width: 100px;
    height: 50%;
    padding: 30px 20px 50px 15px;
    margin: 30px ;
    /*overflow-x: scroll;*/
    overflow-wrap: break-word;
    
}




/*img
{
    width: 200px;
    height: autos;
}
*/

````
### Output
![alt text](images/05.PNG?raw=true "sortie de code")















## 06. couleurFond
* couleurFond.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>style text2-Css</title>
    <link rel="stylesheet" href="couleurFond.css">
</head>

<body>
    <h1>Mon site</h1>

    <img src="1.jpg" alt="" width="200" height="auto">

    <p class="modifB">bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla <a href="#">hettps//:google.com/halabak</a> bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla bla </p>


    
    <p>bla bla bla bla bla bla bla bla bla bla blabla bla bla bla bla bla bla bla bla bla blabla bla bla bla bla bla bla bla bla bla blabla bla bla bla bla bla bla bla bla bla blabla bla bla bla bla bla bla bla bla bla blabla bla bla bla bla bla bla bla bla bla blabla bla bla bla bla bla bla bla bla bla blabla bla bla bla bla bla bla bla bla bla blabla bla bla bla bla bla bla bla bla bla bla</p>

    <p>Source : <a href="hattps://fr.wikipedia">Chat Wékipidia</a></p>

</body>
</html>
````

* couleurFond.css
```CSS
/* Un commentaire*/
body
{   
    margin: auto;
    width: 500px;
    color: indigo;
    /*background-color: #DDD;*/
    background-image: url(1.jpg);
    background-position: center top;
    background-repeat: no-repeat;
    background-size: cover;
    background-origin: content-box;
    background-clip: border-box;
    background-attachment: local;

}

p.modifB
{   
    /*color:rgba(255,0,0,0.5)*/
    /*color: hsl(300, 0, 0.5)*/
    
}
````
### Output
![alt text](images/06.PNG?raw=true "sortie de code")





## 7. Flixbox
* Flixbox.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>FlixBox</title>
    <link rel="stylesheet" href="Flixbox.css">
</head>

<body>
    <div class="div">
        <div class="div1 prioritaire">a</div>
        <div class="div1 order1">AAA</div>
        <div class="div1 order2">BBB</div>
        <div class="div1 order3">CCC</div>
        <div class="div1 order4">DDD</div>
        <div class="div1 order5">EEE</div>
        <div class="div1 order6">FFF</div>
        <div class="div1 order7">GGG</div>
        <div class="div1 order8">HHH</div>
        <div class="div1 order9">III</div>
        <div class="div1 order10">JJJ</div>
        <div class="div1 order11">KKK</div>
        <div class="div1 order12">LLL</div>
        <div class="div1 order13">MMM</div>
        <div class="div1 order14">NNN</div>
        <div class="div1 order15">OOO</div>
        <div class="div1 order16">VVV</div>
        <div class="div1 order17">QQQ</div>
        <div class="div1 order19">RRR</div>
    </div>    


   
</body>
</html>
````

* Flixbox.css
```CSS
/*       display:flex/inline-flex
         1)flex-direction:row/column/row-reverse/column-reverse
         2)flex-wrap:
         3)flex-flow:<direction><wrap>  = 1)+2)   
         justify-content:  
         align-items:
         order:<int>         
         flex-gow:<int>   flex-basis                    
         aligne-self                         */


body
{
    background-color: rgb(197, 231, 240);
    margin: auto;
    width: 100%;
}

.div
{
    background-color: springgreen;
    height: 200px;
    display: flex;
    flex-direction: row;/*flex-direction: column;*/
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-end;/*align-items: flex-start;*/

}


.div1
{
    background-color: violet;
    border: 1px solid red;
    order:2;
}





.order1{order: 1;}
.order2{order: 2;}
.order3{order: 3;}
.order4{order: 4;}
.order5{order: 5;}
.order6{order: 6;}
.order7{order: 7;}
.order8{order: 8;}
.order9{order: 9;}
.order10{order: 10;}
.order11{order: 11;}
.order12{order: 12;}
.order13{order: 13;}
.order14{order: 14;}
.order15{order: 15;}
.order16{order: 16;}
.order17{order: 17;}
.order18{order: 18;}
.order19{order: 19;}

.prioritaire{order:1;}



.order1{flex-grow:1; flex-shrink: 1;}
.order2{flex-grow:4;flex-shrink: 1;}
.order3{flex-grow:1;flex-shrink: 1;}
.order4{flex-grow:2;flex-shrink: 1;}
.order5{flex-grow:3;flex-shrink: 1;}
.order6{flex-grow:1;flex-shrink: 1;}
.order7{flex-grow:1;flex-shrink: 1;}
.order8{flex-grow:1;flex-shrink: 1;}
.order9{flex-grow:1;flex-shrink: 1;}
.order10{flex-grow:1;flex-shrink: 1;}
.order11{flex-grow:1;flex-shrink: 1;}
.order12{flex-grow:1;flex-shrink: 1;}
.order13{flex-grow:1;flex-shrink: 1;}
.order14{flex-grow:1;flex-shrink: 1;}
.order15{flex-grow:1;flex-shrink: 1;}
.order16{flex-grow:1;flex-shrink: 1;}
.order17{flex-grow:5;flex-shrink: 1;}
.order18{flex-grow:4;flex-shrink: 1;}
.order19{flex-grow:1;flex-shrink: 1;}



.order2{align-self: start;}
````
### Output
![alt text](images/07.PNG?raw=true "sortie de code")







## 7. 
* .html
```HTML

````

* .css
```CSS

````
### Output
![alt text](images/07.PNG?raw=true "sortie de code")


















## 8. grid 
* grid.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>grid</title>
    <link rel="stylesheet" href="grid.css">
</head>

<body>
    <div class="div">
        <div class="div1 prioritaire">a</div>
        <div class="div1 order1">AAA</div>
        <div class="div1 order2">BBB</div>
        <div class="div1 order3">CCC</div>
        <div class="div1 order4">DDD</div>
        <div class="div1 order5">EEE</div>
        <div class="div1 order6">FFF</div>
        <div class="div1 order7">GGG</div>
        <div class="div1 order8">HHH</div>
        <div class="div1 order9">III</div>
        <div class="div1 order10">JJJ</div>
        <div class="div1 order11">KKK</div>
        <div class="div1 order12">LLL</div>
        <div class="div1 order13">MMM</div>
        <div class="div1 order14">NNN</div>
        <div class="div1 order15">OOO</div>
        <div class="div1 order16">VVV</div>
        <div class="div1 order17">QQQ</div>
        <div class="div1 order19">RRR</div>
    </div>    


   
</body>
</html>
````

* grid.css
```CSS
/*   
    container : display
                grid-template-colums
                grid-auto-colums







    celluel  :    
    

*/


body
{
    background-color: rgb(197, 231, 240);
}

.div
{
   height: 800px;
    width: 800px;
    border: 2px dashed red;
    display: grid;
    /*grid-template-columns: 100px 100px 100px 100px 100px;*/
    /*grid-template-columns:repeat(3,1fr);*/
    grid-template-columns:repeat(5,minmax(min-content,max-content));
    grid-template-rows: 100px 100px 100px 100px;
    grid-auto-flow: row;
}


.div1
{
    background-color: rgb(238, 99, 238);
    border: 1px solid rgb(88, 21, 175);
    color: seashell;
    font-weight: bolder;
    padding: 10px;
}


.order1
{
    grid-column: 1/3;
}

.order9{grid-row-start: 5;}
````
### Output
![alt text](images/08.PNG?raw=true "sortie de code")
















## 9. grid2
* grid2.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>grid</title>
    <link rel="stylesheet" href="grid2.css">
</head>

<body class= "container">

    <header calss="div1">
        <h1>Mon site</h1>
    </header>

    <section calss="div1">
        <p>g hfdsf jhfsd oiuff iuf kjf iufn hvif ifnf jfhîfu ifnssv sdjff kjvjv kfjij ijffj jsfirg jsfjkff hgf k fdsskjs kjqnn
            bfkjhqf fhf kflkfir dsf sdfhdf sdfhsddfnfj sdfjhsfdnd sdfjhsdf sdjfhds sdjfhsf shsf svio vv fvjhg sj v
        </p>
        <p>g hfdsf jhfsd oiuff iuf kjf iufn hvif ifnf jfhîfu ifnssv sdjff kjvjv kfjij ijffj jsfirg jsfjkff hgf k fdsskjs kjqnn
            bfkjhqf fhf kflkfir dsf sdfhdf sdfhsddfnfj sdfjhsfdnd sdfjhsdf sdjfhds sdjfhsf shsf svio vv fvjhg sj v
        </p>
    </section>

    <aside calss="div1">
        <h2>Une sidebar</h2>
        <p>g hfdsf jhfsd oiuff iuf kjf iufn hvif ifnf jfhîfu ifnssv sdjff kjvjv kfjij ijffj jsfirg jsfjkff hgf k fdsskjs kjqnn
            bfkjhqf fhf kflkfir dsf sdfhdf sdfhsddfnfj sdfjhsfdnd sdfjhsdf sdjfhds sdjfhsf shsf svio vv fvjhg sj v
        </p>
    </aside>

    <footer calss="div1">
        <p>Copyright 2020 - mon site</p>
    </footer>
   
</body>
</html>
````

* grid2.css
```CSS

body
{
    background-color: rgb(197, 231, 240);
}

.container
{
    border: 3px dashed red;
    display: grid;
    grid-template-rows: 1fr 1fr 1fr;
    grid-template-columns: 1fr 25px 1fr;
    grid-template-areas:"entete entete entete"
                        "principale  . lateral"
                        "pied pied pied";
}

.div1
{
    border: 1px solid  blue;
    background-color: blue;
    color: blanchedalmond;
    font-weight: bolder;
    padding: 10px;
}


header{grid-area: entete;}
section{grid-area: principale;}
aside{grid-area: lateral;}
footer{grid-area: pied;}


````
### Output
![alt text](images/09.PNG?raw=true "sortie de code")














## 10. grid3 
* grid3.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>grid</title>
    <link rel="stylesheet" href="grid3.css">
</head>

<body>
    <div class="div">
        <div class="div1 order1">AAA</div>
        <div class="div1 order2">BBB</div>
        <div class="div1 order3">CCC</div>
        <div class="div1 order4">DDD</div>
        <div class="div1 order5">EEE</div>
        <div class="div1 order6">FFF</div>
        <div class="div1 order7">GGG</div>
        <div class="div1 order8">HHH</div>
        <div class="div1 order9">III</div>
        <div class="div1 order10">JJJ</div>
        <div class="div1 order11">KKK</div>
        <div class="div1 order12">LLL</div>
        <div class="div1 order13">MMM</div>
        <div class="div1 order14">NNN</div>
        <div class="div1 order15">OOO</div>
        <div class="div1 order16">VVV</div>
        <div class="div1 order17">QQQ</div>
        <div class="div1 order19">RRR</div>
    </div>    


   
</body>
</html>
````

* grid3.css
```CSS
/*
j   ustify-content: center;
    align-content: center;
    justify-items: left;
    place-items: left;
    grid-row-gap
*/


body
{
    background-color: rgb(197, 231, 240);
}

.div
{
   height: 800px;
    width: 800px;
    border: 2px dashed red;
    display: grid;
    /*grid-template-columns: 100px 100px 100px 100px 100px;*/
    /*grid-template-columns:repeat(3,1fr);*/
    grid-template-columns:repeat(5,minmax(min-content,max-content));
    grid-template-rows: 100px 100px 100px 100px;
    grid-auto-flow: row;

    justify-content: center;
    align-content: center;
    justify-items: left;
    place-items: left;
    grid-row-gap:50px;
    grid-gap:15px 5px;
}


.div1
{
    background-color: rgb(238, 99, 238);
    border: 1px solid rgb(88, 21, 175);
    color: seashell;
    font-weight: bolder;
    padding: 10px;
}

.order7{align-self: center;
        place-items: center;}


````
### Output
![alt text](images/10.PNG?raw=true "sortie de code")
















## 11. IntroductionDisign 
* IntroductionDisign.html
```HTML
<!-- 1er cours Html & css     -->

<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Introduction design Css</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div id="block">
        cette phrase est dans un case
    </div>
    <div> bla;;;;;;;;;;bal,,,,,,,,,,,,,,</div>

    <p>blablablablablablabla <span class="text-red">cette phrase est en rose</span> blablablablablablablablablabla
        blablablablablablablablablablablablablablablablab
        lablablablablablablablablablablablablablabla</p>

    <span class="text-red"> cette phrase est en rose </span>

</body>
</html>
````

* IntroductionDisign.css
```CSS
/*
    1) All tout les appareil
    2) screen les écran(PC, tablette, smartphone ...)
    3) speech outil sentise vocale
    4) print l'impression


    >568px smartphone, 768px, 992px, 1024px, 1280px

*/


body
{
    background-color: rgb(197, 231, 240);
}

img
{
    max-width: 100%;
    height: auto;
}

.container
{
    display: grid;
    grid-template-columns: auto minmax(150px,300px);
    grid-template-areas: "entete entete"
                         "principale laterale"
                         "pied pied";
    
}
header
{
    grid-area: entete;
}
section
{
    grid-area: principale;
    background-color:rgb(173, 213, 224);
    padding: 5px;
}
aside
{
    grid-area: laterale;
    background-color: rgb(112, 155, 212);
    padding: 5px;
}
footer
{
    grid-area: pied;
}

@media(max-width:600px)
{
   /* body 
    {
        color: blue;
        background-color: blanchedalmond
    };*/
    .container
    {
    grid-template-columns: 1fr;
    grid-template-areas: "entete"
                         "principale"
                         "laterale"
                         "pied";
    }  
}

/*@media screen and (max-width:600px){}
@media screen and (max-width:1200px){}*/

@media screen and (min-width:600px){}
@media screen and (min-width:768px){}
@media screen and (min-width:992px){}
@media screen and (min-width:1024px){}
````
### Output
![alt text](images/11.PNG?raw=true "sortie de code")


















## 12. mediaQueries
* mediaQueries.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>media Queries</title>
    <link rel="stylesheet" href="mediaQueries.css">

    <meta name="viewport" content="width:device-width, initial-scale=1">
    <!--<link rel="stylesheet" media="" href="small.css"--->

</head>

<body class="container">
    <header class="item">
        <h1>Mon site</h1>
    </header>

    <section class="item">
        <h2>Ceci est un titre d'article</h2>
        <p> Ingénieur diplômé d’un master II Électronique, Électrotechnique et Automatique (E.E.A.) spécialisé en Signal Imagerie et Application embarqué. proposé par l'université Toulouse III Paul Sabatier obtenu en 2019 et d’un premier Master 2 spécialisé dans l’électronique obtenu en 2017. Formé en électronique système embarqué et en informatique industrielle. Passionné par la programmation en ( C/C++,C#, Python, Java, SQL, HTML/CSS et Matlab) 
            Contact  </p>
        <ul>
            <li>Ingénieur système embarqué (vision par ordinateur et deep learning)  </li>
            <li>Développeur Python chez Michelin </li>
            <li>Stage -Traitement d’images IRM et Deep learning </li>
        </ul>
        <p>Ce projet réalisé au sein de l’équipe R&D - Modis Toulouse sur le projet d’innovation • Coder en Python un algorithme qui fait la reconnaissance des objets pour éviter les obstacles de véhicule autonome • Rédiger un cahier de charge pour : Le Choix des cartes (Arduino, Raspberry, Nvidia, Ordoid …) </p>
        <p><img src="giff.gif" alt="image gif"> </p>
        <p>Développer une application permettant de définir et enregistrer les paramètres de production des produits MICHELIN : - Caractéristiques techniques du produit : pression, force, température, épaisseurs… Informations de production : Date, série … - Suivi les étapes de production : poste Conducteur, Régleur, Alimenteur … • Création la version exécutable : - Accompagner les agents pour recenser leurs besoins et leurs retours sur ce logiciel Réaliser des tests fonctionnels et corrigé les bugs </p>
    </section>



    <aside class="item"> 
        <h2>Recherche</h2>
        <form method="post" action="">
            <p><input type="search" placeholder="Recherche...">
               <input type="submit" value="Ok"> </p>
        </form>
        <h2>Liens</h2>
        <p><a href="#"> A propos</a>  <br>
             <a href="#"> Montion légals</a> </p>
    </aside>

    <footer class="item"> <p>Copyright  copy 2020 - toutes sources réservées</p></footer>



   
</body>
</html>
````

* mediaQueries.css
```CSS
/*
    1) All tout les appareil
    2) screen les écran(PC, tablette, smartphone ...)
    3) speech outil sentise vocale
    4) print l'impression


    >568px smartphone, 768px, 992px, 1024px, 1280px

*/


body
{
    background-color: rgb(197, 231, 240);
}

img
{
    max-width: 100%;
    height: auto;
}

.container
{
    display: grid;
    grid-template-columns: auto minmax(150px,300px);
    grid-template-areas: "entete entete"
                         "principale laterale"
                         "pied pied";
    
}
header
{
    grid-area: entete;
}
section
{
    grid-area: principale;
    background-color:rgb(173, 213, 224);
    padding: 5px;
}
aside
{
    grid-area: laterale;
    background-color: rgb(112, 155, 212);
    padding: 5px;
}
footer
{
    grid-area: pied;
}

@media(max-width:600px)
{
   /* body 
    {
        color: blue;
        background-color: blanchedalmond
    };*/
    .container
    {
    grid-template-columns: 1fr;
    grid-template-areas: "entete"
                         "principale"
                         "laterale"
                         "pied";
    }  
}

/*@media screen and (max-width:600px){}
@media screen and (max-width:1200px){}*/

@media screen and (min-width:600px){}
@media screen and (min-width:768px){}
@media screen and (min-width:992px){}
@media screen and (min-width:1024px){}
````
### Output
![alt text](images/12.PNG?raw=true "sortie de code")














## 13. StiliserListe
* StiliserListe.html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>style text2-Css</title>
    <link rel="stylesheet" href="StiliserListe.css">
</head>
    <p>Liste d'animeaux</p>
    <ul>
        <li>Un chat</li>
        <li>Un chien</li>
        <li>Un ours</li>
        <li>Un castor</li>
    </ul>
<body>
    

</body>
</html>
````

* StiliserListe.css
```CSS
/* Un commentaire*/
body
{   
    margin: auto;
    width: 500px;
    background-color: peru;
    
}

li
{   
    /*list-style-image: url(1.jpg  );*/
    /*list-style-position: outside;*/
    list-style-type: decimal;
}
````
### Output
![alt text](images/13.PNG?raw=true "sortie de code")















## 14. StyleText1
* StyleText1.html
```HTML
<!-- 1er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>style text1-Css</title>
    <link rel="stylesheet" href="StyleText1.css">
</head>

<body>
    <h1>Chat</h1>

    <p>blablablablablablablablablablablablablablablablabla
        blablablablablablablablablablablablablablablablab
        lablablablablablablablablablablablablablabla</p>

    <p class="modifB">blablablablablablablablablablablablablablablablabla
        blablablablablablablablablablablablablablablablab
        lablablablablablablablablablablablablablabla</p>

    <p>Source : <a href="hattps://fr.wikipedia">Chat Wékipidia</a></p>

</body>
</html>
````

* StyleText1.css
```CSS
/* Un commentaire*/
p.modifB
{   
    font-style: italic;
    font-variant: small-caps;
    font-weight: bold;
    font-size: 12px;
    line-height: 27px;
    font-family: Arial, Helvetica, sans-serif;
}
````
### Output
![alt text](images/14.PNG?raw=true "sortie de code")








## 15. StyleText2 
* StyleText2 .html
```HTML
<!-- 3er cours Html & css     -->

<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="utf-8">
    <title>style text2-Css</title>
    <link rel="stylesheet" href="StyleText2.css">
</head>

<body>
    <h1>Chat</h1>

    <p class="modifB">blablablablablablablablablablablablablablabla blabla
        blablablabla<a href="#">hettps//:google.com/halabak</a> blablablablablablablablablablablablab
        lablablablablablablablablablablablablablabla</p>

    <p>blablablablablablablablablablablablablablablablablablablablablabla</p>

    <p>Source : <a href="hattps://fr.wikipedia">Chat Wékipidia</a></p>

</body>
</html>
````

* StyleText2 .css
```CSS
/* Un commentaire*/
body
{
    margin: auto;
    width: 500px;
}
span.modifB
{   
    /*text-decoration: line-through red;*/
    /*text-shadow: 4px 4px blue;*/
    /*text-transform:lowercase; */
    /*text-align: justify;*/
    /*vertical-align: sub;*/
    /*text-indent: 3em;*/
    /*text-overflow: ellipsis;*/
    /*letter-spacing: 4px;*/
    /*white-space: pre-line;*/
    /*word-break: break-all;*/
    /*direction: ltr;*/
    /*text-justify: distribute;*/
  


}
````
### Output
![alt text](images/15.PNG?raw=true "sortie de code")









## 16. TableauxCSS
* TableauxCSS.html
```HTML

<!-- les  Tableux 
        <thead></thead>
        <tbody></tbody>
        <tfoot></tfoot>        ---->
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Ma page web pour les Tableux CSS</title>
    <link rel="stylesheet" href="TableauxCSS.css">
</head>

<!------------------------------------------------->

<body>
    <table>

        <tr>
           <th id="Id"> Id</th>
            <th id="nom"> Name</th>
            <th id="age"> Age</th>
            <th id="mail"> Email</th>
        </tr>
       

        <tr>
            <td headers="Id"> Friste</td>
            <td headers="nom">  Qannaf</td>
            <td headers="age"> 27 ans</td>
            <td headers="mail">q.alsahmi@gmail.com</td>
        </tr>
        <tr>
            <td headers="Id"> Friste</td>
            <td headers="nom">  Qannaf</td>
            <td headers="age"> 27 ans</td>
            <td headers="mail">q.alsahmi@gmail.com</td>
        </tr>
        <tr>
            <td headers="Id"> Friste</td>
            <td headers="nom">  Qannaf</td>
            <td headers="age"> 27 ans</td>
            <td headers="mail">q.alsahmi@gmail.com</td>
        </tr>
        <tr>
            <td headers="Id"> Friste</td>
            <td headers="nom">  Qannaf</td>
            <td headers="age"> 27 ans</td>
            <td headers="mail">q.alsahmi@gmail.com</td>
        </tr>
        <tr>
            <td headers="Id"> Friste</td>
            <td headers="nom">  Qannaf</td>
            <td headers="age"> 27 ans</td>
            <td headers="mail">q.alsahmi@gmail.com</td>
        </tr>
            
          
        
    </table>
    
</body>

````

* TableauxCSS.css
```CSS
/* Un commentaire*/
/*          1) border      :  <width> <style> <color>
                              border-width:
                              border-style:dotted, dashed, solid, double, groove, ridge, inset, outset
                              border-color:
                border-top,left ....
            2) border-image : border-image.com
            3) border-radius: border-top-left-radius
            4) outline      :



*/


html
{
    background-color: #EEE;
}


body
{
    margin: auto;
    /*width: 1200px;*/
    
}


table,td,th
{
    border: 1px dashed #000;
    /*border-collapse: collapse;*/
    border-spacing: 10px;
}


td,th
{
    padding: 10px;
}

th
{
    font-size: 10px;
}
````
### Output
![alt text](images/16.PNG?raw=true "sortie de code")









