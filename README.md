# dotfiles

## Test homer config
`podman run -d --rm --name homer -p 8080:8080 --mount type=bind,source=".",target=/www/assets docker.io/b4bz/homer:latest && firefox http://localhost:8080/`
