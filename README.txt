** README **
** cannot upload company code, but wanted to document my work anyway

- used HTML/CSS/js/jquery to create a simple front end client to test company server.
	- handles GET, POST, PATCH, DELETE requests.
	- handles sessions cookies
	- because the main purpose was to test and familiarize myself with the server,
		I simply opted to print response code, headers, and body.
	- relevant technologies: axios, bootstrap
	
- tested and implemented js api libraries:
	adminApi.min.js
	userApi.min.js
- extensively tested admin functions
- tested a couple of user functions
- tested server response

ADMIN_TEST:
	login page:
		login
		logout (did not delete session - 8/21/18)
	user page:
		get users
		create user
		activate user
		delete user
		get user's library permissions
		modify user's library permissions
		get user's project permission
		modify user's project permission
	project page:
		get projects
		create project
		rename project
		activate project
		delete project
	project permissions page:
		get user's project permissions
		modify user's project permissions
	library permissions
		get user's library permissions
		modify user's project permission

USER_TEST
	login
	logout (did not delete session - 8/21/18)
	create model in library
	add files to model
	create instance on a project
	download files of an instance


Ryan Chan
8/23/2018
