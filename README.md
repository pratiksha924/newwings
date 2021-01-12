#Generic Backend framework MCS


## Commands to configure the package
	.git init (initialize git repo)
	.git remote add origin {REPO URL} (to add the remote repository)
	.composer install - (Download all depencies)
	.php artisan key:generate (Generate Application Key)
	.php artisan storage:link (Generate Symlink)
	.php artisan migrate --seed


## Extra Commands to generate new models & controllers

	.php artisan make:model {model} --controller   (Generates Model + Controller)
	.php artisan make:model {model}   (Generates Model)
	.php artisan make:controller {controller}   (Generates Controller)


### Configure Panel Name

`resources\lang\en\panel.php`