web_technologies_2018_2019
	-app => Hidden for the user
		-controllers
			-add.php
			-change.php
			-changeInfo.php
			-delete.php
			-home.php
			-login.php
			-logout.php
			-profile.php
			-register.php
		-core
			-app.php => main class, processing URL
			-Controller.php
		-include
			-vars.php => file with information for the DB
			-onemilionpixels.sql => Database
		-models
			-database.php
			-Pixel.php
			-User.php
		-views
			-add_view.php
			-change_view.php
			-home_view.php
			-login_view.php
			-profile_view.php
			-register_view.php
		-.htaccess => Limit user access
		-init.php => Include files, initializing DB
	-public => The user has access to this folder
		-css
			-profile_style.css
			-reg_style.css
			-style.css
		-images
		-.htaccess => access and rules to proccess URL
		-index.php => calls init.php, creates instance of the app
README.txt
wwwTech2018_19_11ed_SI_REQ_fn62001_fn61982.docs