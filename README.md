# create-react-app

## Build the Docker image.

```bash
docker build -t smathewthomas/create-react-app .
```

## Run a container.

~~mkdir src~~

~~docker run --rm -ti -v $HOME/.aws:/root/.aws -v $HOME/.ssh:/root/.ssh  -v "$(pwd)"/src:/usr/src/app/src smathewthomas/create-react-app~~

```bash
docker run --rm -ti -v $HOME/.aws:/root/.aws -v $HOME/.ssh:/root/.ssh -p "3000:3000" -v "$(pwd)":/usr/src/app/src smathewthomas/create-react-app

npx create-react-app src/<new-react-app>
```

