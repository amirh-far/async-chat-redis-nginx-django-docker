# async-chat-redis-docker-django

<p>
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=green"/>
<img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"/>
<img src="https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/daphne-092E20?style=for-the-badge&logo=django&logoColor=green"/> <br>
</p>

This repo is an asynchronous simple chat, built in with Django, Nginx, Redis, Daphne and Postgresql using Docker.<br>
I have used the same chat, mentioned in [channels tutorial official document](https://channels.readthedocs.io/en/latest/tutorial/index.html), but with additional configurations for Redis, Nginx and Postgresql composed together with Docker.


### Installation

```
# Clone the project
git clone https://github.com/amirh-far/async-chat-redis-nginx-django-docker

# Install Docker (macos)
brew install docker

cd to/your/cloned/project

# compose the containers
sudo docker compose up

```

## Contact

If you have any questions, checkout my github profile for contact information

GitHub: [amirh-far](https://github.com/amirh-far)

Feel free to customize this template based on the specifics of your project.
