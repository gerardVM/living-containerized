# HOW TO USE IT

You just need to have docker installed. Please, proceed as follows:

```bash
docker run --rm curlimages/curl https://raw.githubusercontent.com/gerardVM/living-containerized/main/aliases > ~/.living_containerized # Execute this command every time you want to use the last version of this repository
echo "[[ -f ~/.living_containerized ]] && source ~/.living_containerized" >> ~/.bashrc # This includes an extra line into your ~/.bashrc file
docker image rm curlimages/curl:latest # Clean recently used Docker image
```
Once these commands are executed, open a new terminal and then you are free to go.

Be aware that you may have limitations if you are trying to perform complex operations with these tools.

## Contributing

Pull requests are welcome

## License

[MIT](LICENSE)
