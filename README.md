<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title> animation text </title>
        <link rel="stylesheet" href="style.css ">
        <style>
           
           *{
                padding: 0;
                margin: 0;
                font-family: sans-serif;
                
              
            }
            
            body{
                background: #000;
                
      
            
            }
            
            container{
                text-align: center;
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%, -50%);
                widht: 100%;
            
            
            }
            
            .container span{
                text-transform: uppercase;
                display: block;
                
            
            }
            .text1{
                color: white;
                font-size: 60px;
                font-weight: 700;
                letter-spacing: 8px;
                margin-bottom: 20px;
                background: black;
                position: relative;
                animation: text 3s 1;
            
            }
            
            .text2{
                font-size: 30px;
                color: #6ab04c;
                
 
            
            }
            
            @keyframes text {
                0%{
                    color: black;
                    margin-bottom: -40px;
                }
                30%{
                    letter-spacing: 25px;
                    margin-bottom: -40px;
                }
                85%{
                    letter-spacing: 8px;
                    margin-bottom: -40px;
                
                }
                    
                    
            
            }
            
        
        
        </style>
    </head>
    <body>
        <div class="container">
           
            <span class"text1"> RED EYES </span>
            <span class="text2"> 11 </span>
            
           
            
            </dive>
        
        
  
    </body>
</html>
