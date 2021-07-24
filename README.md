# alpine-android-tools
![Docker Pulls](https://img.shields.io/docker/pulls/forumi0721/alpine-android-tools)
![Docker Stars](https://img.shields.io/docker/stars/forumi0721/alpine-android-tools)



----------------------------------------
#### [alpine-android-tools](https://hub.docker.com/r/forumi0721/alpine-android-tools/)
![Docker Image Version](https://img.shields.io/docker/v/forumi0721/alpine-android-tools/latest)
![Docker Image Size](https://img.shields.io/docker/image-size/forumi0721/alpine-android-tools/latest)



----------------------------------------
#### Description

* Distribution : [Alpine Linux](https://alpinelinux.org/)
* Architecture : x64
* Appplication : [android-tools](https://sites.google.com/a/android.com/tools/)
    - Android Debug Bridge (adb) is a versatile command-line tool that lets you communicate with a device. 



----------------------------------------
#### Run

```sh
docker run -i -t --rm \
           -e RUN_USER_NAME=<user_name> \
           -e RUN_USER_UID=<user_uid> \
           -e RUN_USER_GID=<user_gid> \
           forumi0721/alpine-android-tools:[ARCH_TAG]
```



----------------------------------------
#### Usage

* Run docker container and login.
    - Default user name : forumi0721



----------------------------------------
#### Docker Options

| Option             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Ports

| Port               | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Volumes

| Volume             | Description                                      |
|--------------------|--------------------------------------------------|
| -                  | -                                                |


#### Environment Variables

| ENV                | Description                                      |
|--------------------|--------------------------------------------------|
| RUN_USER_NAME      | login user name (default:forumi0721)             |
| RUN_USER_UID       | login user uid (default:1000)                    |
| RUN_USER_GID       | login user gid (default:100)                     |

