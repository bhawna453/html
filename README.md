
<html>

<head>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	
	<style>
		body{
			background-color:#85F4FF ;
		}
		img.image1 {
			height: 300px;
			width: 300px;
			margin: auto;
		}
		img.image2 {
			height: 300px;
			width: 300px;
			margin: auto;
			padding-left:50px ;
			
		}		
.button-34 {
  background: #5E5DF0;
  border-radius: 999px;
  box-shadow: #5E5DF0 0 10px 20px -10px;
  box-sizing: border-box;
  color: #FFFFFF;
  cursor: pointer;
  font-family: Inter,Helvetica,"Apple Color Emoji","Segoe UI Emoji",NotoColorEmoji,"Noto Color Emoji","Segoe UI Symbol","Android Emoji",EmojiSymbols,-apple-system,system-ui,"Segoe UI",Roboto,"Helvetica Neue","Noto Sans",sans-serif;
  font-size: 16px;
  font-weight: 700;
  line-height: 24px;
  opacity: 1;
  outline: 0 solid transparent;
  padding: 8px 18px;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  width: fit-content;
  word-break: break-word;
  border: 0;
 text-align: center;
 margin: auto;
 display:flex;
  display:grid;
  
 

}


		@media only screen and (max-width: 665px) {
			body{
				background-color: #FF8AAE;
			}
			img.image1 {
				height: 100px;
				width: 100px;
				margin-left:40px ;
			}
				img.image2 {
				height: 100px;
				width: 100px;
				margin-left:40px ;
			}

		}
		
		
	
	</style>
</head>

<body align="center">

	<h1 style="text-align:center;">roll the dice</h1>


	<div>
		<img src="dice6.png" alt="dice image" class="image1">
		<img src="dice6.png" alt="dice image 2" class="image2">
		</div>
		<button class="button-34" type="button" role="button" onclick="refresh()" style="margin-top:50px ;" >Click Me</button>
		
<script src="fs2.js">

</script>
</body>

</html>
