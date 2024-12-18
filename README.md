# Try Docker
A docker that serves a simple web page to test how far can i go with simple html, css and javascript. Also doubles as a practice of docker.

<!--  TODO: here is a list of possible ideas    -->
<!-- + make a portfolio page as homepage        -->
<!-- + make a contact me page (namecard style)  -->
<!-- + make a project showcase page             -->
<!-- + make a blog post page                    -->

## How to run the code

1. Clone this repo
```bash
git clone https://github.com/MingFei2001/try-docker.git
cd try-docker
```

2. Build the docker image
```bash
docker build -t simple-web .
```

3. Run the docker
```bash
# depending on your configuration you might need to use sudo
docker run --name {the docker name} -d -p 8080:80 simple-web
```

4. Access `http://localhost:8080` to see the webpage

## LICENSE
This project is licensed under the [MIT License](./LICENSE).

You are free to use, modify, and distribute this software as outlined in the license.
