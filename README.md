# django-react-poll

A simple dockerized poll app built with Django and React


### Run with docker

**Docker compose needs to be installed.**

Duplicate `.env-example` as `.env` and set the database password inside `.env`:

`$ cp .env-example .env`

Run with:

`$ docker-compose up`

Then, open `http://localhost/` in the browser.


### Used tech stack

- Backend: Django with Django Rest Framework
- Frontend: React.js with Material-UI
- Database: PostgreSQL




### TODO

- [ ] Optimize docker images
- [ ] Dev / Production docker & settings files
- [ ] Hot reloading while React development
- [ ] UI Improvements
- [ ] Serve with nginx container
