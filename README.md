# dotfiles

## Test homer config
`docker run -d --rm --name homer -p 8080:8080 --mount type=bind,source=".",target=/www/assets b4bz/homer:latest`
