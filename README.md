# plantilla web standard
```
<!DOCTYPE html>
<html>
<meta charset="utf-8">
<head>
	<title></title>
	<style type="text/css">
		.container{
			height: 800px;
			width: 800px;
			background-color: #ccc;
			margin: 0px auto;
			position: relative;
		}
		#foto{
			width: 24%;
			background-color: red;
			display: inline-block;
			height: 100%
		}
		#titulo{
			width: 48%;
			background-color: grey;
			display: inline-block;
			height: 100%;
			border:1px solid;
		}
		#topic{
			width: 26.5%;
			background-color: red;
			display: inline-block;
			height:70%;
			border:1px solid;
			position: absolute;
			margin-left: 2px;
			
        }
        #busqueda{
        	background-color: green;
        	display: inline-block;
        	width: 26.5%;
        	height: 25%;
        	border:1px solid;
        	margin-left: 2px;
        	bottom: 20px;
        	position: absolute;
        	top:75%;
        	

        }

		header{
           height: 10%;
           position: relative;

		}
		nav{
			margin-top: 5px;
			height: 5%;
			border:1px solid;
			background-color: yellow;

		}
		
		section{
			width: 100%;
			height: 82%;
			margin-top: 5px;
			position: relative;
		}
		footer{
          display: inline-block;
          width: 46%;
          height: 20%;
          margin-left: 215px;
          margin-top: 2px;
		  bottom: 10px;
		  position: absolute;
		  border:1px solid;

		}
		#izquierda{
			display: inline-block;
			width:26%;
			height: 100%;
			border:1px solid;
			background-color: green;
			
		}
		#seccion{
			margin-left: 25%;	
			display: inline-block;
			width: 46%;
			height: 75%;
			margin: 0px auto;
			border:1px solid;
			background-color: blue;
		}
		#derecha{
			display: inline-block;
			width:26%;
			height: 75%;
			border:1px solid;
			margin: 0px auto;
			background-color: green;
		}
		#links{
			background-color: pink;
			margin-left: 590px;
			width:26%;
			height: 24.4%;
			border:1px solid;
			position: absolute;
			bottom: -2px;
		}
		#footer{
			display: inline-block;
			width: 100%;
			height: 100%;
			background-color: magenta;
			
			
			
		}
		
	</style>
</head>
<body>
   <div class="container">
   	<header>
   		<div id=foto>
   			Foto 
   		</div>
   		<div id=titulo>
   			titulo
   		</div>
   		<div id=topic>
   			topic
   		</div>
   		<div id=busqueda>
        byscador
   		</div>

   	</header>
   	<nav>
   		<div id=navegacion>
   			nav
   	</nav>
   	<section>
   		 <div id=izquierda>
    		    aside izquierda
    	</div>
    	<div id=seccion>
    	section.
    	     
        </div>
        
        <div id=derecha>
        	aside derecha.
        </div>
        <div id=links>
        	links
        </div>
       </section>
    <footer>
    	 <div id=footer>
        	footer.
        </div>
    </footer>
   </div>
</body>
</html>

´´´
