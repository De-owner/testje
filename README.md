<html>
<head>
    <title>Community Paneel</title> 
	
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
	<meta http-equiv="Content-Language" content="nl" />
	<meta name="description" content="Het paneel van FBOI in Habbo Hotel!" /> 
	<meta name="author" content="Wessel Verheij" /> 
	<meta name="copyright" content="Wessel Verheij" /> 
	<meta name="robots" content="nosnippet">
	<meta name="googlebot" content="noodp" /> 

	<link rel="stylesheet" href="/_paneel/assets/css/style.css" type="text/css" />
	<link rel="stylesheet" href="/_paneel/assets/css/style-dev.css" type="text/css" />
	<link rel="stylesheet" href="/_paneel/assets/plugins/spoilers/spoilers.css" type="text/css" />
	<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" type="text/css">
	<link rel="stylesheet" href="//fonts.googleapis.com/css?family=Open+Sans:300,400,400italic,600,700" type="text/css">
	<link rel="stylesheet" href="//fonts.googleapis.com/css?family=Montserrat:400,700" type="text/css" />
	
	<script type="text/javascript" src="/_paneel/assets/js/jquery.js"></script>
	<script type="text/javascript" src="/_paneel/assets/plugins/ckeditor/ckeditor.js"></script>
	<script type="text/javascript" src="/_paneel/assets/plugins/spoilers/spoilers.js"></script>
	<script type="text/javascript" src="/_paneel/assets/js/blockadblock.js"></script>
	<script type="text/javascript" src="/_paneel/assets/js/main.js"></script>
</head>


<body leftmargin="0px" topmargin="0px" rightmargin="0px" bottommargin="0px" marginwidth="0px" marginheight="0px">
	<nav class="content-left">
		<div class="menu-header">
			<div class="content">
				<img src="https://www.habbo.nl/habbo-imaging/badge/b07154s02135s01153s43154s380144cc56082d6a3e9802bc228bbca72ea5b.gif">
			</div>
		</div>
		<div class="menu-item extend-menu">
	<div class="content">
		<i class="fa fa-dashboard"></i>
	</div>
	
	<div class="menu-advanced">
		<div class="item"><a href="/">Dashboard</a></div>
		<div class="item"><a href="/conversaties">Mijn conversaties</a></div>
		<div class="item"><a href="/profiel/fboimedewerker">Mijn profiel</a></div>
		<div class="item"><a href="/wachtwoord_veranderen">Verander wachtwoord</a></div>
		<div class="item"><a href="/uitloggen">Uitloggen</a></div>
	</div>
</div>

<div class="menu-item extend-menu">
	<div class="content link-button" data-link="/forum">
		<i class="fa fa-comment"></i>
	</div>
</div>

<div class="menu-item extend-menu">
	<div class="content">
		<i class="fa fa-group"></i>
	</div>
	
	<div class="menu-advanced">
		<div class="item"><a href="/medewerkers">Overzicht medewerkers</a></div>
<div class="item"><a href="/notifyrechtenhouders">Roep rechtenhouders</a></div>
			</div>
</div>

<div class="menu-item extend-menu">
	<div class="content">
		<i class="fa fa-bar-chart"></i>
	</div>
	
	<div class="menu-advanced">
		<div class="item"><a href="/stats/rangenoverzicht">Rangenoverzicht</a></div>
		<div class="item"><a href="/stats/promos">Maandelijks: Promoties</a></div>
		<div class="item"><a href="/stats/trainingen">Maandelijks: Trainingen</a></div>
		<div class="item"><a href="/stats/laatstepromoties">Laatste promoties</a></div>
		<div class="item"><a href="/stats/laatstetrainingen">Laatste trainingen</a></div>
	</div>
</div>
				</nav>
	
	<div class="content-right">
		<div class="header">
			<div class="header-left">
				<div class="v-center">
					<a href="https://github.com/lessevv/communitypanel">Community Panel</a>
				</div>
			</div>
			
			<div class="header-right text-bait">
				<div class="header-button link-button" data-link="/conversaties">
					<div class="v-center">
						<span class="header-alert">0</span>
						<i class="fa fa-comments"></i>
					</div>
				</div>
				<div class="header-user">
					Welkom, <strong class="link-button" data-link="/profiel/fboimedewerker">fboimedewerker</strong>
				</div>
			</div>
		</div>
		<div class="wrapper">
			<div class="panel w-20">
	<div class="panel-heading">
		<h2>Advertentie</h2>
	</div>
	<div class="panel-body">
			</div>
</div>

<div class="panel w-50">
	<div class="panel-heading">
		<h2>Laatste nieuws</h2>
	</div>
	<div class="panel-body">
	</div>
</div>			
			<div class="panel">
							</div>
		</div>
	</div>
	
	<script type="text/javascript">
		$("#toggle-dropdown").click(function() {
			$("#user-dropdown").toggle();
		});

		$(".Editor, .message-textarea").each(function() {
			CKEDITOR.replace($(this).attr('id'));
		});
	</script>
</body>
</html>
