docker build . --tag dasrecht/yamllint
docker run -it --rm -v "$(pwd):/data"  --name yamllint dasrecht/yamllint
