# Odoo-Setup
This is an out-of the box Odoo setup using Docker

# Requirementss:
1. Linux env (ubuntu or Debian)
2. Docker
3. Dockercompose
4. Odoo (handled by the docker file)
5. Postgres(Handled by the docker file)

# Run
- create a `.env` file that will contain all your secrets and passwords i.e Odoo and Postgress
NB: use a `.gitignore` file and add your `env` file to avoid pushing your secrets
- Just run
`docker-compose up -d`
- incase of any error
  `docker container-name logs`
- To stop the container
  `docker-compose down`
