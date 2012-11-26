bullet_example
==============

Bullet gem is designed to help developers by suggesting them over the eager loading(N+1 queries) and counter cache. Bullet gem shall be used in development or custom environment(staging,profile etc..)

Follow the below steps to use the gem:

*	gem "bullet", :group => "development". add this in gem file.

*	in config/initializers/bullet.rb add the below.	

	if defined? Bullet
	  Bullet.enable = true
	  # Bullet.alert = true
	  Bullet.bullet_logger = true
	end

Bullet suggests through different ways such as alert , bullet logger, rails logger, console etc..

The link https://github.com/flyerhzm/bullet can be referred for more information.

