### Running the project

In your terminal, type:

```bash
docker-compose up -d --build
```

This will build the images, and start the containers in detached mode (that's what the `-d` does).

If successful, you should be able to go to [localhost:80](http://localhost:80) and see the project running.

### Tearing down the project

When you're done and ready to remove the containers, you can use

```bash
docker-compose down
```

This will stop all the containers that are running as part of the `docker-compose.yml`.

## How to install Docker:

[Install Docker Desktop](https://docs.docker.com/engine/install/)

#### Linux

These systems do not have much issue.  Before you do anything, remember to start docker.

```bash
systemctl start docker
```

#### MacOs

Following the above link, you should be able to install the Docker Engine and Desktop.  Starting docker may require you to give it some permissions.


#### Windows

If you are on a Windows Machine, please *DO NOT* skip the part where you are asked to update the Linux Kernal.

Windows now has a linux subsystem which will allow you to do some UNIX operations.  It is vital that you update it.
