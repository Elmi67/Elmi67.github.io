-	!DOCTYPE html>
+	<!DOCTYPE html>
 	<html>
 	<head>
-	    <title>Canvas tutorial</title>
+		<link rel="stylesheet" type="text/css" href="css/CSS.css" />
 	    <script type="text/javascript">
-	        function draw(){
-	            // Find the canvas element.
-	            var canvas = document.getElementById('tutorial');
-	
-	            // Determine size and find center of canvas.
-	            var w = canvas.getAttribute("width");
-	            var h = canvas.getAttribute("height");
-	            var x = w / 2;
-	            var y = h / 2;
-	
-	            // Determine how large the circle can be.
-	            var r = (x > y ? y : x) - 10;
-	
-	            if (canvas.getContext){
-	                var ctx = canvas.getContext('2d');
-	
-	                ctx.beginPath();
-	
-	                // Outer circle.
-	                ctx.arc(x, y, r, 0, Math.PI*2, true);
-	
-	                ctx.stroke();
-	            }
-	        }
+		function draw(){
+			
+			var canvas = document.getElementById('canvasOne');
+			var ctx = canvas.getContext('2d');
+			
+			var width = canvas.getAttribute("width");
+			var height = canvas.getAttribute("height");
+			var centerX = width/2;
+			var centerY = height/2;
+			var gapScale = 0.95; //Mind the gap
+			var wedgesCount = prompt("Number of Parts");
+			var allAround = 2 * Math.PI;
+			var rad = (centerX < centerY ? centerX : centerY) - 10;
+			var colourSet = ["#A55D00", "#15C0FF", "#FF961B", "#FFF14F", "#FF67B2", "#27D83C", "#FFFFFF", "#000000"];
+			var playerNumber = 5;
+			try{
+			ctx.beginPath();
+			ctx.fillStyle = colourSet[playerNumber - 1];
+			ctx.arc(centerX, centerY, rad, 0, allAround, false);
+			ctx.fill();
+			ctx.stroke();
+			
+			drawWedges(ctx, centerX, centerY, rad * gapScale, wedgesCount);
+			}
+	catch(err)
+	  {
+	  txt="There was an error on this page.\n\n";
+	  txt+="Error description: " + err.message + "\n\n";
+	  txt+="Click OK to continue.\n\n";
+	  alert(txt);
+	  }
+		}
+		
+		function drawWedges(ctx, x, y, r, n){
+			var n = Math.abs(n);
+			var n = Math.ceil(n);
+			var n = n%257;
+			var angle = 2 * Math.PI / n;
+			var allAround = 2 * Math.PI;
+			var xOffset = 0;
+			var yOffset = 0;
+			var colourSet = ["#A55D00", "#15C0FF", "#FF961B", "#FFF14F", "#FF67B2", "#27D83C", "#FFFFFF", "#000000"];
+			var getsColours = [true, true, true, true, true, true, true, true]
+			
+			
+			
+			
+			if(n!=1){
+				for(i=0; i<n; i++){
+					var conPointX = x + r * Math.cos(i * angle);
+					var conPointY = y + r * Math.sin(i * angle);
+					
+					ctx.beginPath();
+					ctx.moveTo(x + xOffset, y + yOffset);
+					ctx.lineTo(conPointX, conPointY);
+					ctx.arc(x, y, r, i * angle, (i+1) * angle, false);
+					ctx.lineTo(x + xOffset, y + yOffset);
+					ctx.closePath();
+					if(getsColours[i]){
+						ctx.fillStyle = colourSet[i];
+						ctx.fill();
+					}
+					ctx.stroke();
+				}
+				
+			}else{
+				ctx.beginPath();
+				ctx.moveTo(x+r, y)
+				ctx.arc(x, y, r, 0, allAround, true);
+				ctx.fillStyle = colourSet[0];
+				ctx.fill();
+				ctx.stroke();
+			}
+			
+		}
 	    </script>
-	    <style type="text/css">
-	        body { font-family: "Helvetica Neue", helvetica, sans-serif; }
-	        canvas { border: 1px solid black; }
-	    </style>
+		<title>--Elmi Awad--</title>
+		<meta charset="utf-8" />
+		
 	</head>
-	<body onload="draw();"> <!-- Draw function is called in response to onload event. -->
-	    <p>Drawing using the &lt;canvas&gt; is a great way to learn some JavaScript.
-	        Here are somethings to try:</p>
-	        <ol>
-	            <li>Draw an inner circle.</li>
-	            <li>Draw a line that divides the inner circle in half.</li>
-	            <li>Divide the inner circle into wedges.</li>
-	            <li>Fill a wedge with color.</li>
-	            <li>Write a function to divide the inner circle into an arbitrary
-	                number of wedges.</li>
-	            <li>Write a function to fill in an arbitrary wedge with color.</li>
-	        </ol>
-	    <p>You may find this tutorial useful: <a href="https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Canvas_tutorial">Mozilla Canvas Tutorial.</a>
-	    </p>
-	    <canvas id="tutorial" width="600" height="400"></canvas>
+	<body onLoad="draw();">
+		<h1 align="center">Elmi </h1>
+	    <hr>
+	    <div style="width:100%;text-align:center;">
+	    <canvas id="canvasOne" width="700" height="600" style="display:inline;">I ain't about that life</canvas>
+	    </div>
 	</body>
 	</html>
 	
