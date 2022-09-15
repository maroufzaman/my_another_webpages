<!DOCTYPE html>
<html>
	<head>
		<title>Fancify Shamcify</title>

		<!-- link to your script file here -->
		<script src="fancifymytext.js">

		</script>
		
	</head>
	<style>

		input[type = text]{

		   width: 100%;
		   padding: 12px 20px;
		   margin: 8px 0;
		   box-sizing: border-box;
		   border: 2px solid red;
		   border-radius: 4px;

	  }          


	   .button {

		  border: none;
		  color: white;
		  padding: 16px 32px;
		  text-align: center;
		  text-decoration: none;
		   display: inline-block;
		   font-size: 16px;
		  margin: 4px 2px;
		 transition-duration: 0.4s;
		 cursor: pointer;
	 }

		.button1 {
		  background-color: white; 
		  color: black; 
		  border: 2px solid #4c56af;
	   }

		.button1:hover {
		 background-color: #4c56af;
		 color: white;
		 }


		 .button2 {
		  background-color: white; 
		  color: black; 
		  border: 2px solid #4c56af;
	   }

		.button2:hover {
		 background-color: #4c56af;
		 color: white;
		 }

   </style>



	<body>
		<h1>Fancify my Text</h1>
        <!-- Your UI controls go here -->

		

		<form>
			<label for="text">text</label>
			<input type="text" id="text" name="text">	
		</form>

		


	


		<fieldset>
			<legend>Fancify </legend>

			<button id="button1"> Bigger</button>
			<button id="button2">Moo</button>
		
			<div>
			  <input type="radio" id="FancyShmancy" name="drone" value="FancyShmancy">
			  <label for="FancyShmancy">FancyShmancy</label>
			</div>
		
			<div>
			  <input type="radio" id="BoringBetty" name="drone" value="BoringBetty">
			  <label for="BoringBetty">BoringBetty</label>
			</div>
		
			
		</fieldset>


	</body>
</html>
