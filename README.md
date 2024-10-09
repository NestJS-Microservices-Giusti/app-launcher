## Dev

1. Clone the repository
2. Execute `sudo chown -R $(whoami):$(whoami) ./orders-ms/postgres/` to give permissions to the postgres user
3. Create an .env file based on .env.tempate
4. Ejecutar el comando `git submodule update --init --recursive` para reconstruir los submodulos
5. Run `docker-compose up --build`
