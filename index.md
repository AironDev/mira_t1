<!DOCTYPE html>
<html>
<head>
	<title></title>
	<!-- Compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
    <!-- Compiled and minified JavaScript -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
    <style type="text/css">
    	html {
		  height: 100vh;
		}

		body {
		  font-family: Roboto, RobotoDraft, Helvetica, Arial, sans-serif !important;
		  font-size: 14px !important;
		  font-weight: 400;
		  letter-spacing: 0.2px;
		  line-height: 20px;
		  color: #202124 !important;
		  background-color: #ede7f6;
		}

		header nav .image-logo {
		  display: flex;
		  height: 100%;
		  align-items: center;
		  margin-left: 2%;
		}

		header nav .brand-logo {
		  font-size: 1.5rem;
		}

		.login-body {
		    height: calc(100% - 20px);
		    padding-top: 3%;
		}

    </style>
</head>
<body>
	<header>
	    <nav>
	      <div class="nav-wrapper indigo darken-4">
	        <a href="index.html" class="brand-logo left image-logo p-1"><img class="responsive-img" src="assets/images/miraicon.png" alt="Mira technologies logo" width="40px"> Mira Technologies</a>
	        <ul class="right">
	          <li><a href="index.html" class="right-pd-50">Register</a></li>
	        </ul>
	      </div>
	    </nav>
	</header>
	<main class="container login-body">
	    <div class="row">
	      <div class="col s0 m3"></div>
	      	<div class="col s12 m6">
	        	<div id="loader"></div>
		        <div>
		          <div class="center-align ">
		            <img class="responsive-img" src="assets/images/miraicon.png" alt="Mira technologies logo" width="60px">
		            <h4 class="indigo-text text-darken-4">Login</h4>
		            <p>Login to your account</p>
		          </div>
		        </div>
		        <form id="login-form" style="padding:30px;" class="card-panel">
		          <div class="row">
		            <div class="input-field col s12">
		              <input id="email" name="email" type="text" autocomplete="email">
		              <label for="email" class="">Email</label>
		            </div>
		          </div>
		          <div class="row">
		            <div class="input-field col s12">
		              <input id="password" name="password" type="password" autocomplete="current-password">
		              <label for="password" class="">Password</label>
		            </div>
		          </div>
		          <div class="row login-links">
		            <div class="col s12 center-align">
		              <button id="login-btn" class="btn waves-effect waves-light indigo darken-4" type="submit" name="action">Login
		              </button>
		            </div>
		            <br>
		          </div>
		        </form>
		        <div class="col s12 center-align">
		          <a class="center indigo-text text-darken-4" href="forgot.html">Forgot Password</a>
		        </div>
	      	</div>
	      <div class="col s0 m3"></div>
	    </div>
  	</main>
</body>
</html>