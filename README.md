<!DOCTYPE html>
<html>
<head>
	<meta content="width=device-width, initial-scale=1" name="viewport" />
	<title>Forgot password</title>
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1" crossorigin="anonymous">
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css" integrity="sha512-HK5fgLBL+xu6dm/Ii3z4xhlSUyZgTT9tuc/hSrtw6uzJOvgRr2a9jyxxT1ely+B+xFAmJKVSTbpM/CuL7qxO8w==" crossorigin="anonymous"/>

	<link rel="stylesheet" href="./assets1/css1/forget.css">
</head>
<body>
<main>
	<div class="backg" style="background-image: url(./assets1/imags/blur.png);">
		<div class="heading">
			 
			    <h1>Forget your Password???</h1> <br> 
			          <center><h4>Don't Worry!</h4></center>
			 
		</div>
		<div class="text">
			
				<p>Enter your email address and we'll</p>
	            <p>send your a link to rest your password.</p>
			
		</div>
		
			<form action="" method="get" class="form-example">
				  <div class="form-example">
					    <input type="email" class="have" name="email" id="email" placeholder="EmailAddress"  required><span class="fas fa-envelope-square level" ></span>
				  </div>&nbsp;
				  <div class="form-example">
				    <input type="submit" class="btn btn-info buttonc" value="send link">
				  </div>
			</form>

	   <div>
			<center>
				<p class="over">Did you remember? <a href="" style="color: #28b5c2">Sign in!</a></p>
				<p class="over">you don't have a accout? &nbsp; <a href="" style="color: #28b5c2">Sign up</a></p>
			</center>
	   </div>
	</div>
</main>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-ygbV9kiqUc6oa4msXn9868pTtWMgiQaeYH7/t7LECLbyPA2x65Kgf80OJFdroafW" crossorigin="anonymous"></script>
<script src="https://code.jquery.com/jquery-3.5.1.js" integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc=" crossorigin="anonymous"></script>

<style type="text/css">
	body{
    background:none!important;
}
.body-main{
    background-color: none; 
}
.heading
{
	color: white;
}
.backg {
    background: #808080a6;
    width: 100%;
    height: 100vh;
    background-size: cover;
    display:flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.text
{
	margin-top: 20px;
	color: white;
    float:left;
    width:100%;
    font-family:Calibri (Body);
    letter-spacing:2px;
    font-size:14px;
    text-align:center;
    margin:20px 0px;
    margin-bottom: 29px;
}  

 .btn.btn-info
 {
 	color: white;
 	width: 100%;
 }
.over
{
	color: white;
}
.have
{
    background: transparent;
    color: #f8f9fa;
}
/*::placeholder{
	color: white;
}
*/
.level{
    font-size: 16px;
    font-weight: 900;
    position: relative;
    right: 12px;
    top: 7px;
    color:white;
    display:-webkit-box;
}
button, input, optgroup, select, textarea {
    margin: 0;
    font-family:auto;
    font-size: inherit;
    line-height: inherit;
}
input#email {
    border: 1px solid;
    border-radius: 3px;
    padding: 2px 7px;
    outline: none;
    cursor: pointer;
    width: 100%;
}

form.form-example {
    display: table;
}

div.form-example {
    display: table-row;
}

label, input {
    display: table-cell;
    margin-bottom: 10px;
}

label {
    padding-right: 10px;
}
input:-internal-autofill-selected span.fas.fa-envelope-square{
   color: black!important;
}
div.form-example {
    width: 100%;
    display: -webkit-box;
}
@media screen and (max-width: 660px){
    .text{
        margin-top: 100px;
    }
}
	@media all (max-width: 667px){
 .text {
    margin-top: 10px!important;
    letter-spacing:1px;
    margin: 15px 0px;
    font-size: 10px;
}
}
</style>

</body>
</html>
