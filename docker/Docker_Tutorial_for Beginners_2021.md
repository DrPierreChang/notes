- [link to course](https://youtu.be/pTFZFxd4hOI)

Docker is a platform for consistent building, running
and shipping applications

Container is an isolated environment for running an application

Containers:
 - Allow running multiple apps in isolation
 - Are lightweight
 - Share OS of the host
 - Start quickly
 - Need less hardware resources

Check version

```shell
docker version
```

Dockerfile includes instructions
to package up an application
into an image

Image contains everything application needs to run

Image
- A cut-down OS
- A runtime environment (ex. Python)
- Application files
- Third-party libraries
- Environment variables

Container is process with own file system provide by
the image
___


Build image with tag -t and use Dockerfile in current directory .
```shell
docker build -t hello-docker .
```

List of docker images
```shell
docker image ls
```
or
```shell
docker images
```
Run image
```shell
docker run image_name
```

Pull image from hub (alternative: docker run image_name)
```shell
docker pull image_name
```

Stopped containers
```shell
docker ps -a
```

Run container in interactive mode -it
```shell
docker run -it image_name
```

Check Linux user
```shell
whoami
```

Commands executed lately
```shell
history 
```

Clean History
```shell
history -c
```

Execute command from history
```shell
!number_in_history
```

List of ubuntu packages database
```shell
apt list
```
Update ubuntu packages database

```shell
apt udate
```

Install package

```shell
apt install package_name
```

Clear terminal
```shell
ctrl + L
```

Remove package
```shell
apt remove package_name
```
Vertical ls
```shell
ls -1
```

Detailed ls
```shell
ls -l
```

Go to root directory
```shell
cd ~
```

Rename directory with move command
```shell
mv old_name new_name
```
Create multiple files
```shell
touch file1 file2 file3
```
Remove multiple files
```shell
rm file1 file2 file3
```

Remove files using pattern *
```shell
rm file*
```
Open file and scroll
```shell
more
less (q to exit)
```

Read first and last lines
```shell
head -n 5
tail -n 5
```

View content of small files
```shell
cat
```

Redirect output
```shell
cat file1 > file2
echo hello > file_name
```

Concatenate content of several files
```shell
cat file1 file2
```
Concatenate content of several files
and write to another file
```shell
cat file1 file2 > combined.txt
```
