rpi-docker-wordpress
======================

Out-of-the-box Wordpress docker image for Raspberry Pi (based ubuntu)


Usage
-----

To create the image `joaquindlz/rpi-docker-wordpress`, execute the following command on the rpi-docker-wordpress folder:

	docker build -t joaquindlz/rpi-docker-wordpress .

You can now push your new image to the registry:

	docker push joaquindlz/rpi-docker-wordpress


Running your Wordpress docker image
-----------------------------------

Start your image:

	docker run -d -p 80:80 joaquindlz/rpi-docker-wordpress

Test your deployment:

	curl http://localhost/

You can now start configuring your Wordpress container!


More information
----------------

For details on how to access the bundled MySQL Server, set specific passwords or disable .htaccess,
please visit the [joaquindlz/rpi-docker-lamp repository on github](https://github.com/joaquindlz/rpi-docker-lamp)

**based http://www.tutum.co**
