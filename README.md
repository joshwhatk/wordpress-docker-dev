# Quick Docker Wordpress Development

Simple docker setup to quickly get Wordpressing.

---

## Up and Running

> **Note**: You need to have [Docker](https://www.docker.com/) set up correctly to use this.

1. Simply download a zip or clone the repository.
2. `cd` into the project directory.
3. Run `docker-compose up`.
4. It will automatically create `public` and `database` folders to hold the Wordpress files and MySQL database, respectively.
5. Visit `localhost:8080` to get setup.
6. You can also connect to the MySQL database via port `33067`.

## Down and Forgotten

> **Note**: You will need to run `docker-compose stop` instead if you started it with the `-d` flag.

1. Hit `Ctrl + C` (on Mac) to quit the running docker-compose process.
2. Run the following commands:

    ```
    docker-compose rm wordpress
    docker-compose rm mysql
    ```

3. And `rm -r` the project directory and it's as if it never happened.
