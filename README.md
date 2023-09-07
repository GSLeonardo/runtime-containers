# Runtine Container

This repo has the objective of providing container configurations for different runtimes, making it easier to create apps using frameworks like NodeJS, without actually having to install (almost) anything on your machine.

**You need to have Docker installed**

## npm

1. Add the path where npm should run (your project) to the `BIND` variable inside the `.env` file
2. Go to the `/npm` folder from this repo
3. Run `docker compose run --rm --build npm` followed with any npm command

**For Windows users**: Make sure to replace all the `\` from your path, with `/` <br>(_Ex_. Change `C:\Users\me` to `C:/Users/me`)

## npx

1. Add the path where npm should run (your project) to the `BIND` variable inside the `.env` file
2. Go to the `/npx` folder from this repo
3. Run `docker compose run --rm --build npx` followed with any npx command

**For Windows users**: Make sure to replace all the `\` from your path, with `/` <br>(_Ex_. Change `C:\Users\me` to `C:/Users/me`)
