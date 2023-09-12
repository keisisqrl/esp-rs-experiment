FROM "mcr.microsoft.com/devcontainers/rust"
RUN cargo install cargo-quickinstall
RUN cargo quickinstall cargo-binstall
RUN cargo binstall -y espup
RUN espup install