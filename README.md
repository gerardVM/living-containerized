# LIVING CONTAINERIZED

Use all your favourite tools even though you have not performed any installation (Except for Docker)

## INSTALLATION

You just need to have docker installed. Please, proceed as follows:

1- Execute following command to use the last version of this tool.

```bash
docker run --rm curlimages/curl https://raw.githubusercontent.com/gerardVM/living-containerized/main/aliases > ~/.living_containerized
```

2- Include an extra line to your ~/.bashrc file to source your new configuration.
```bash
echo "[ $(echo $(which docker)) ] && . ~/.living_containerized" >> ~/.bashrc
```

3- Clean up the curl docker image (Optional).
```bash
docker image rm curlimages/curl:latest
```
Once these commands are executed, open a new terminal and then you are good to go.

Be aware that you may have limitations if you are trying to perform complex operations with these tools.

## HOW TO USE IT

Use your tools like you would normally do. You just need to set the version you want by setting variables like TF_VERSION or GO_VERSION.

You can check what your setup is by executing the command "read-versions"

In order to track versions, a .tool-versions file will be created in each directory you use your tools.

## Contributing

Pull requests are welcome

## License

[MIT](LICENSE)
