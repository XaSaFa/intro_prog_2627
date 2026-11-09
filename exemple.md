**index.html:**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botiga</title>
    <style>
        body{
            background-color:rgb(176, 107, 43);
            color: whitesmoke;  
            text-align: center;                  
        }

        .targeta{
            margin: auto;
            width: 800px;
            border: 2px solid peru;
            border-radius: 10px;
            box-shadow: 6px 6px rgb(102, 59, 15);
            margin-top:10px;
            padding: 10px;
        }        
        p{        
            padding: 20px; 

        }
        img{            
            margin: 20px auto;
            
            max-width: 600px;
            border-radius: 12px;             
        }
        .boto{
            margin: 10px 8px 10px 0px;
            width: 100px;
            border: 2px solid peru;
            border-radius: 10px;
            box-shadow: 6px 6px rgb(102, 59, 15);
            margin-top:10px;
            padding: 10px;
        }
        .boto:hover{
            border: 2px solid black;
            box-shadow: 6px 6px rgb(150, 43, 43);
            color: rgb(150, 43, 43);

        }
        .contenidor{
            width: 800px;
            margin: 0px auto;
            display: flex;
        }


    </style>
</head>
<body>
    <!-- Nom del negoci -->
    <div class="targeta">
        <h1>Fleca Sancho</h1>
    </div>
    
    <!-- Menú-->
     <div class="contenidor">
        <div class="boto"> Inici </div>
        <div class="boto"> Productes </div>
        <div class="boto"> Contacte</div>

     </div>



    <!-- Presentació del negoci -->
    <div class="targeta">
        <p >
            ¡Benvinguts a la fleca de referència de Mont-roig del Camp!<br><br>
            La fleca Sancho disposa del major assortiment de pa i pastes de Mont-roig del Camp des de 1978.
            <img src="imatges/croissant1.webp" alt="">
        </p>

    </div>
</body>
</html>
```

**contacte.html**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botiga</title>
    <style>
        a, body{
            background-color:rgb(176, 107, 43);
            color: whitesmoke;  
            text-align: center;  
            text-decoration: none;                
        }

        .targeta{
            margin: auto;
            width: 800px;
            border: 2px solid peru;
            border-radius: 10px;
            box-shadow: 6px 6px rgb(102, 59, 15);
            margin-top:10px;
            padding: 10px;
        }        
        p{        
            padding: 20px; 

        }
        img{            
            margin: 20px auto;
            
            max-width: 600px;
            border-radius: 12px;             
        }
        .boto{
            margin: 10px 8px 10px 0px;
            width: 100px;
            border: 2px solid peru;
            border-radius: 10px;
            box-shadow: 6px 6px rgb(102, 59, 15);
            margin-top:10px;
            padding: 10px;
        }
        .boto:hover{
            border: 2px solid black;
            box-shadow: 6px 6px rgb(150, 43, 43);
            color: rgb(150, 43, 43);

        }
        .contenidor{
            
            width: 800px;
            margin: 0px auto;
            display: flex;
        }
        .active{
            color:rgb(42, 22, 2)
        }
        .contacte{
            text-align: left;
            padding-left: 10px;
        }
        .color_fosc{
            color:rgb(88, 57, 22)
        }
        iframe{
            margin: auto;
        }



    </style>
</head>
<body>
    <!-- Nom del negoci -->
    <div class="targeta">
        <h1>Fleca Sancho</h1>
    </div>
    
    <!-- Menú-->
     <div class="contenidor">
        
        <a href="index.html"> <div class="boto"> Inici </div></a>
        <a href="productes.html"> <div class="boto"> Productes </div></a>
        <a href="contacte.html"> <div class="boto active"> Contacte</div></a>

     </div>



    <!-- contacte -->
    <div class="targeta">
        <div class="contacte">
            <span class="color_fosc">Adreça:</span> C/ Paris, 79. 08029 Barcelona<br>
            <span class="color_fosc">Telèfon:</span> <a href="tel:+34934948800">+ 34 934 94 88 00</a><br>
            <span class="color_fosc">Mail:</span> <a href="mailto:info@flecasancho.com">info@flecasancho.com</a><br>
            <span class="color_fosc">On som:</span><br>
            <!-- Mapa de google-->
            <div style="padding: 20px 100px;">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1058.3098245811573!2d2.1466356227143897!3d41.38816213091057!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12a4a28266531dfb%3A0x70550e1bb8b78882!2sPecomark%20S.A.U!5e0!3m2!1sca!2ses!4v1794215720939!5m2!1sca!2ses" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
            </div>

        </div>

    </div>
</body>
</html>
```
