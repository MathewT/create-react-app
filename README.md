# create-react-app

```bash
docker build -t smathewthomas/create-react-app .
```

```bash
mkdir src
docker run --rm -ti -v $HOME/.aws:/root/.aws -v $HOME/.ssh:/root/.ssh  -v "$(pwd)"/src:/usr/src/app/src smathewthomas/create-react-app
```

