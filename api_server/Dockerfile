FROM rustlang/rust:nightly

RUN cargo install diesel_cli --features postgres

RUN cargo install cargo-watch

WORKDIR /usr/src/app

EXPOSE 3001

VOLUME ["/usr/local/cargo"]
