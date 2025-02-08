# Workato-Connector-SDK-Docker
A quick guid for for setting up the Workato connector development environment with docker on Windwos.

1. Turn on the WSL 2 feature on Windows. For detailed instructions, refer to the [Microsoft documentation](https://learn.microsoft.com/en-us/windows/wsl/install)
2. Install Docker desktop for Windows. [https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)
3. Open the Terminal once your WSL 2 and Docker is ready.
4. Download the **docker-compose.yml** file and save it to your destination folder in WSL
6. Run the command to start the container.
`
docker compose up -d
`
7. Runs Bash shell inside the container
`
docker exec -it workato bash
`
8. You can now run Linux commands inside the container as if you were logged into a separate machine
9. Try workato command
    `
   workato help
   `
