Tools you need installed for local development:
 - docker
 - docker-compose
 - That's about it??
Suggested tools and extensions:
 - `rust` via [rustup](https://rustup.rs/)
 - `yarn`
 - [Rust extension pack](https://marketplace.visualstudio.com/items?itemName=swellaby.rust-pack)
 - [Conventional Commits](https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits)
 - [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
How to develop:
1. Clone this repository
2. Run `git submodule update --init --recursive`
3. Run `docker compose up` to bring up the development environment
    - [http://localhost:8000](http://localhost:8000) for the backend
    - [http://localhost:3000](http://localhost:3000) for the frontend
    - `mongodb://root:root@localhost:27017` as the mongodb connection string
4. Changes made in the `frontend` or `backend` folders are immediately applied