# rusty-py-postgres
[![Open in Codespaces](https://img.shields.io/static/v1?label=Codespaces&message=Open&color=blue&logo=github)](https://codespaces.new/max-callaghan/rusty-py-postgres?quickstart=1)

[![Language: Rust](https://img.shields.io/badge/Language-Rust-darkorange)](https://www.rust-lang.org/)
[![Language: Python](https://img.shields.io/badge/Language-Python-yellow)](https://www.python.org/)
[![Database: PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-blue)](https://www.postgresql.org/)

Codespace, Dev-container, Docker setup for an environment including Rust, Python and Postgres.

Created as an interation of the Rust-Postgres dev-container template (https://github.com/devcontainers/templates/tree/main/src/rust-postgres)

Acts as a starting point for developing solutions which include the three languages. This is my first public repositiory, so if there are any improvements to be made I am all ears.


## Using Python
The repository includes a folder "py_post_test" which contains python files for testing the connection to Postgres.
Before running the python files, ensure psycopg2-binary is installed by running "pip install psycopg2-binary" in terminal

## Using Rust
The repositiory folder includes a folder "rust_test" which contains tests which will confirm Rusts connection to Postgres.
To do these checks, first cd into the rust_test folder.
cargo run - Should return "Hello World"
cargo test - Should return the the test results.
As this is testing the connection to Postgres the relevant crate has been included in the Cargo.toml file, this will increase the build time.
