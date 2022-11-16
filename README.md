# HOW TO USE IT

You just need to have docker installed and being able to copy a file in order to do a backup copy of bashrc file.

Please, proceed as follows:

```bash
cp ${HOME}/.bashrc ${HOME}/.bashrc.bak # First step is doing a backup copy in case of emergency
docker run --rm curlimages/curl https://raw.githubusercontent.com/gerardVM/living-containerized/main/aliases.txt >> ${HOME}/.bashrc
```

Once these two commands are executed, open a new terminal and then you are free to go.

Be aware that you may have limitations if you are trying to perform complex operations with these tools.

## Contributing

Pull requests are welcome

## License

[MIT](LICENSE)
