# template

Template project

## Prerequisites

- `secrets.DOCKER_TARGET`: Docker username or organization
- `secrets.DOCKER_USERNAME`: Docker login username
- `secrets.DOCKER_PASSWORD`: Docker login password

## Steps

1. Create repo with repository template
2. Put the upstrem project to `.repo`, format: `username/repository-name`
3. Push

## Version

If you need to build a specific version, you can add `secretes.UPSTREAM_VERSION`,
and building the image with the `--build-arg` parameter with `Dockerfile`.

## License

MIT

