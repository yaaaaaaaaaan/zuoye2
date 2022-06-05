
<html>
    <head>
        <style>
            input[type=text]{
                border: 2px solid black;
                width: 200px;
                padding: 10px 10px 10px 10px;
                padding-left: 30px;
                margin: 30%;
                background-image: url("校标（蓝）.png")
                ;background-size: 20px;
                background-repeat: no-repeat;
                background-position: left;
                }
                option{color: red;}
                select{color: red;}
            li{
            text-align:center;
            text-decoration:none;
        display: inline-block;
        margin: 10PX;
    }
   
.dropdown {
  position: relative;
  display: inline-block;
}
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  padding: 12px 16px;
}
.dropdown-content a{
    color: aquamarine;
    text-decoration: none;
    display: block;
    
  
}

.dropdown-content a:hover{background-color: aliceblue;}


.dropdown:hover .dropdown-content {
  display: block;background-color: rgb(239, 237, 234);
}
span{color: red;}




        
    li a:hover:not(.active)
    {background-color: antiquewhite;
    color: aquamarine;}

    
            li a {display: block;
                text-shadow: 11px;
                
                
                text-decoration: none;
            padding: 8PX;background-color:none;color: rgb(237, 11, 11);}
            ul{background-color:none;}
            body {background-repeat: no-repeat;
                background-size: 100%;
                background-attachment: fixed;
            background-position: right top;}
       
    select{display: inline-block;
      
    }
    button{
        border: 2px solid black;
                
                padding: 10px 10px 10px 10px;
                position:absolute;
               margin: 20%;
            font-size: 11px;

                
       

    }
    
       </style>

    </head>
    <body style="background-image: url(天空.jpg)">
        <ul>
            <img src="校标（蓝）.png" alt="tubiao" width="50px" height="50px">
        <li><a  href="#new">New</a></li>
        <li><a href="story">story</a></li>
        <li><a href="thing">thing</a></li>
        
        <div class="dropdown">
            <span>more</span>
            <div class="dropdown-content">
              <a href="#">class</a><br>
              <a href="#" target="_blank" rel="noopener noreferrer">some</a>
            </div>
          </div>
        </ul>
        <button type="submit" name="firt" value="search">search</button><br>
        <input type="text">
         
        
    </body>
</html>
