In case you are not able (or you do not want to install `cookiecutter` dependency), you can also use the Dockerfile included in this repo. What it takes to use it is to fill in the `cookiecutter.json` according to your needs. Then execute:

`docker build -t cookie .`
`docker run -v $PWD/:/cookiecutter cookie`

NOTE: add `sudo` before each command if you are in linux