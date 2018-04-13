# cmatrix-docker
The project was created entirely by [abishekvashok](https://github.com/abishekvashok) over on [their github repo](https://github.com/abishekvashok/cmatrix).
This is just a docker container of their script.

This is the repo for my dockerhub automated build.

Start with: `docker run --rm --log-driver none -it beezu/cmatrix`

ctrl+c to close it.

I personally set up a bash alias to make launching cmatrix easier.

**NOTE**: It's important to set log driver to none, because this container will quickly fill your hard drive/partition with logs. With regular use, you could fill a 250GB hard drive with cmatrix docker logs in a matter of weeks.
