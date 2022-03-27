# laxmi-Business-Card
<html>
    <head>
        <style>
            #card{
                border:3px solid blue;
                width: 350px;
                height: 500px;
                margin:30px auto;
                background-color: black;
                padding-bottom: 20px;
            }
            img{
                border-radius: 50%;
                background-color: black;
                padding: 5px;
                margin-top: 20px;
            }
            #section1{
                text-align: center;
                background-color: rosybrown;
            }
            h2{
                margin-bottom: 0px;
            }
            p{
                margin-bottom: 0px;
            }
            #section{
                padding: 30px;
            }
           table{
               width: 100%;
               color: cornsilk;
           }
           button{
               background-color: cornsilk;
               padding: 10px;
               width: 40%;
               color: rgb(81, 129, 81);
               margin-right: 10px;
            }
            #b1{
                margin-left: 10px;
            }
            #section3{

                text-align: center;
                border:5px solid black
                margin 30px
            }
            #section2{
                margin-bottom: 40px;
                margin-top: 20px;
            }
            body{
               /* background-color: blanchedalmond;*/
               background: url("data:image/jpeg;base64,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");
               }

            

        </style>
    </head>
    <body> 
        <div id="card">
            <div id="Section1"> 
                <img src=" data:image/jpeg;base64,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 " 
                 width="200px"
                 height="200px"
                />
               <h2>K Laxmi</h2>
               <p>Software Engineer</p>
            </div>
             



            <div id="Section2"> 
                <table>
                    <tr>
                        <th>
                            <p>112</p>
                            <p>Posts</p></th>
                        <th>
                            <p>420</p>
                            <p>followers</p>
                        </th>
                        <th>
                            <p>250</p>
                            <p>following</p>
                
                        </th>
                    </tr>
        
                </table>
            </div>




            <div id="section3">
               <button id="b1">Follow </button>
                <button id="b2">Message</button>
                    
                </td>
            </tr>
        </div>



    </body>
</html>
