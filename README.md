<!DOCTYPE html>
<html>
<head>
	<link rel="stylesheet" type="text/css" href="login2.css">
	<title>ROYAL CUSIN LOGIN PAGE</title>
</head>
<body>
	<div class="login-page">
		<div class="login-box">
			<h1>Login...</h1>
			<form action="/submit_login" method="post">
				<p>Username</p>
				<input type="text" name="username" placeholder="Enter Username" id="username">
				<p>Password</p>
				<input type="password" name="password" placeholder="Enter Password" id="password">
				<label for="remember-me">
					<input type="checkbox" id="Get-Notification" name="Get-Notification">
					Get Notification
				</label>
				 <input type="submit" name="submit" value="Login">
				<button id="login">Login</button>
				<p> <a href="royalres.html">Login</a></p>
				<a href="#">Forgot Password?</a>
				<p>Don't have an account? <a href="royalres.html">Free sigup</a></p>
			</form>
		</div>
	</div>
	<script src="login.js"></script>
</body>
</html>
