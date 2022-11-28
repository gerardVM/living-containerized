# HOW TO USE IT

You just need to have docker installed. Please, proceed as follows:

1- Execute this command every time you want to use the last version of this repository

```bash
docker run --rm curlimages/curl https://raw.githubusercontent.com/gerardVM/living-containerized/main/aliases > ~/.living_containerized
```

2- Include an extra line to source your new configuration file into your ~/.bashrc file
```bash
echo "[[ -f ~/.living_containerized ]] && source ~/.living_containerized" >> ~/.bashrc
```

3- Clean up the curl docker image (Optional)
```bash
docker image rm curlimages/curl:latest
```
Once these commands are executed, open a new terminal and then you are free to go.

Be aware that you may have limitations if you are trying to perform complex operations with these tools.

## Contributing

Pull requests are welcome

## License

[MIT](LICENSE)
