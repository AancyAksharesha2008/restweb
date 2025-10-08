# Ex.07 Restaurant Website
## Date:7/10/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:

```

virgil.html

<html>
    <head>
        <title>
            You Can See The Sea Here
        </title>
        <link rel="stylesheet" href="style1.css">
    </head>
    <body>
        <div class="title">
            <p>YOU CAN SEE THE SEA HERE</p>
        </div>
        <div class="quote">
            <p>"Fresh from the sea,straight to your plate!! ,
                Reel on freashness-taste the ocean today!!"
            </p>
        </div>
        <div class="links">
            <a href="virgil.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administer</a>
            <a href="contact.html">Contact</a>
        </div>
        <div class="footer">&copy; Aancy Aksharesha A (25015773)</div>
    </body>
</html>

home.css

body{
    background-image:url('bg.png');
    background-repeat:no-repeat ;
    back-ground-size:cover;
    justify-content:space-between ;
    display:flex ;
}
.title{
    position:fixed;
    top:0;
    font-family:'Arial','Helvetica','sans-serif';
    margin-left:70px;
    font-size:40px;
    font-weight: bold;
    color:white;
}
.quote{
    position:fixed;
    bottom: 250px;
    margin-left:7px;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-weight:bolder;
    font-size:25px;
    color:beige;
}
.links{
    position:fixed;
    top:0;
    @media(any-hover:hover){
        a:hover{
            background-color:purple;
        }
    }
    margin-top:42px;
    margin-left:1000px;
    margin-right:50px;
    font-family:'Times New Roman', Times, serif;
    font-size:24px;
}
.footer{
    position:fixed;
    bottom:0;
    width:100%;
    back-ground:beige;
    color:white;
    text-align:center;
    padding:10px;
}

menu.html

<html>
    <head>
        <title>
            Menu: Ceremony
        </title>
        <link rel="stylesheet" href="menu.css">
    <body>
        <div class="links">
            <a href="virgil.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administer</a>
            <a href="contact.html">Contact-us</a>
        </div>
        <div class="title">
            <p>You can see the sea here - MENU</p>
        </div>
        <div class="menu-grid">
            <div class="menu-item">
                <img src= "prawns.png">
                <h3>Prawns-$14</h3>
            </div>
            <div class="menu-item">
                <img src= "thandoori.png">
                <h3>Fish Thandoori-$16</h3>
            </div>
            <div class="menu-item">
                <img src= "lobster.png">
                <h3>Lobster-$18</h3>
            </div>
            <div class="menu-item">
                <img src= "soup.png">
                <h3>Crab soup-$7</h3>
            </div>
            <div class="menu-item">
                <img src= "nethili.png">
                <h3>Neethili 65-$10</h3>
            </div>
            <div class="menu-item">
                <img src= "biryani.png">
                <h3>Fish Mandi Biryani-$13</h3>
            </div>
            <div class="menu-item">
                <img src= "squid.png">
                <h3>Squid gravy-$11</h3>
            </div>
            <div class="menu-item">
                <img src= "fingers.png">
                <h3>Fish fingers-$9</h3>
            </div>
            <div class="menu-item">
                <img src= "tawa.png">
                <h3>Tawa Fish Fry-$4</h3>
            </div>
            <div class="menu-item">
                <img src= "meals.png">
                <h3>fish meals-$10</h3>
            </div>
            <div class="menu-item">
                <img src= "lollipop.png">
                <h3>Crab lollipop-$12</h3>
            </div>
            <div class="menu-item">
                <img src= "puttu.png">
                <h3>Sura puttu-$9</h3>
            </div>
        </div>
<div class="footer">&copy; Aancy Aksharesha A (25015773)</div>
    </body>
</html>

menu.css

body{
    background-color:pink;
    background-repeat:no-repeat
    background-size:cover;
    justify-content:space-between;
    display:flex;
}
.title{
    position:fixed
    top=0;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin-left:5px;
    font-size:70px;
    font-weight:bold;
    color:light purple;
}
.links{
    position:fixed;
    top:0;
    @media(any hover:hover){
        a:hover{
            background-color: beige;
        }
    }
    margin-top: 10px;
    margin-left: 1000px;
    margin-right: 60px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 22px;
}
.menu-grid{
    align-items: center;
    display: grid;
    grid-template-columns: repeat(6,1fr);
    gap: 10px;
    padding: 20px;
    background-size: 90%;
    background-color: beige;
}
.menu-item{
    background-color: beige;
    background-size: 700px;
    padding: 2px;
    border-radius: 5px;
    text-align: center;
    border:beige;
}
.menu-item img{
    width: 100%;
    height: auto;
    border-radius: 5px;
    margin-bottom: 5px;
}
.menu-item h3{
    margin: 0;
    font-size: 20 px;
    color: black;
}
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: beige;
    color:black;
    text-align: center;
    padding:10px;
}

admin.html

<html>
    <head>
        <title>
            Administer: Ceremony
        </title>
        <link rel="stylesheet" href="admin.css">
    </head>
    <body>
        <div class="links">
            <a href="virgil.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administer</a>
            <a href="contact.html">Contact-us</a>
        </div>
        <div class="title">
            <p>You can see the sea here -Meet our superb team</p>
        </div>
        <div class="team-grid">
            <div class="team-item">
                <img src="ceo.png">
                <h2>AancyAnand</h2>
                <p>CEO</p>
            </div>
            <div class="team-item">
                <img src= "dhoni.png">
                <h2>Dhoni</h2>
                <p>Manager</p>
            </div>
            <div class="team-item">
                <img src="virat.png">
                <h2>Virat Kohli</h2>
                <p>Restaurent Technician</p>
            </div>
            <div class="team-item">
                    <img src="rashmika.png">
                    <h2>Rashmika</h2>
                    <p>Hr</p>
            </div>
            <div class="team-item">
                    <img src="samantha.png">
                    <h2>Samantha</h2>
                    <p>Sales Head</p>
            </div>
            <div class="team-item">
                        <img src="nazriya.png">
                        <h2>Nazriya</h2>
                        <p>Receptinist</p>
            </div>
        </div>
    <div class="footer">&copy; Aancy Aksharesha A (25015773)</div>
    </body>
</html>

admin.css

body{
    background-image :url('bga.png');
    background-repeat: no-repeat;
    background-size: cover;
    justify-content: space-between;
    display: flex;
}
.title{
    position: absolute;
    top: 10px;
    font-family: Georgia, 'Times New Roman', Times, serif;
    margin-left: 50px;
    font-size: 50px;
    font-weight: bold;
    color:beige;
}
.links{
    position: fixed;
    top: 0;
    @media(any-hover: hover){
        a:hover{
            background-color: pink;
        }
    }
    margin-top: 40px;
    margin-left: 1000px;
    margin-right: 50px;
    font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-size: 22px;
}
.team-grid {
    /* align-items: center; */
    bottom:0;
    display: grid;
    grid-template-columns: repeat(6,1fr);
    gap: 30px;
    padding: 40px;
    max-width: 1200px;
    margin: 0 auto;
}
.team-item {
    background-color: pink;
    background-size: 200px;
    border-radius: 5px;
    text-align: center;
    border: 2px beige;
    margin-top: 200px;
    height: 250px;
}
.team-item img {
    width: 120px;
    height: auto;
    border-radius: 50%;
    border: 3px purple;
    margin-bottom: 20px;
    margin-left: auto;
    margin-right: auto;

}
.team-item h2{
    margin:0;
    font-size:20px;
    color:black;
}
.team-item p{
    margin:0;
    font-size: 20px;
    color: black;
}
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color:white;
    color: black;
    text-align: center;
    padding:10px;
}

contact.html

<html>
    <head>
        <title>
            Contact-us: You can see the sea here
        </title>
        <link rel="stylesheet" href="contact.css">
    </head>
    <body>
        <div class="links">
            <a href="virgil.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administer</a>
            <a href="contact.html">Contact-us</a>
        </div>
        <div class="title">
            <p>You can see the sea here</p>
        </div>
        <div class="box">
            <h2>Contact-us</h2>
            <p>Visit Us at:</p>
            <p>1628/Alhail gate,Dubai</p>
            <p>Phone: +41 56745 56745</p>
            <p>Email: seeseaalhail@gmail.com</p>
        </div>
        <div class="footer">&copy; Aancy Aksharesha A (25015773)</div>
    </body>
</html>

contact.css

body{
    background-image:url('bgaaaa.png');
    background-repeat: no-repeat;
    background-size: cover;
    justify-content: space-between;
    display:flex;
    align-items: center;
    }
.title{
    position:absolute;
    top: 10px;
    font-family: 'Times New Roman', Times, serif;
    margin-left: 60px;
    font-size: 60px;
    font-weight: bold;
    color: beige;
}
.links{
    position: fixed;
    top: 0;
    @media(any-hover :hover){
        a:hover{
            background-color: pink;

        }
    }
    margin-top: 40px;
    margin-left: 1000px;
    margin-right: 50px;
    font-family: 'Times New Roman', Times, serif;
    font-size: 22px;
}
.box{
    margin-left: 600px;
    border: 8px;
    background-color:purple;
    width: 250px;
    height: 250px;
    text-align: center;
    padding: 20px;
}
.box h2{
    font-size: larger;
    color: pink;
}
.box p{
    font-size: larger;
    color: pink;
}
.footer{
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color:purple;
    color: white;
    text-align: center;
    padding:10px;
}

```


## OUTPUT:

![alt text](<Screenshot (23).png>)

![alt text](<Screenshot (24).png>)

![alt text](<Screenshot 2025-10-07 212336.png>)

![alt text](<Screenshot (25).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
