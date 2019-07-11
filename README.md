# canvas_rect
stroke a Rect use canvas
'''
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>canvasRect</title>
	<style type="text/css">
	   #canvas{
	   	background: #eee;
	   }
	</style>
</head>
<body>
  <canvas id="canvas" width="1000" height="500"> 
  	 你的浏览器展示不支持vanvas,请更新！
  </canvas>
   <script type="text/javascript">
   	 var canvas=document.getElementById('canvas');
   	 var c=canvas.getContext('2d');

   	      c.lineWidth=5;
   	      c.strokeStyle="red";
   	      

   	      c.rect(50,50,150,200);
   	      c.stroke();

   	      c.beginPath();
   	      c.lineWidth=5;
   	      c.strokeStyle="red";
   	      c.fillStyle="green";

   	      c.rect(300,50,150,200);
   	      c.fill();
   	      c.stroke();
   </script>
</body>
</html>
'''
