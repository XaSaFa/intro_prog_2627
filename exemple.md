Codi web:

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
