### Docker image on Alpine Linux

This Docker image [(0xnu20/alpine)](https://hub.docker.com/r/0xnu20/alpine/) uses [Alpine Linux](https://alpinelinux.org/) as its base image. For more information on versions and support see [Releases](https://wiki.alpinelinux.org/wiki/Alpine_Linux:Releases).

#### Why Alpine?
Alpine is 3x faster than Ubuntu with a 4.62 real life seconds wait time compared to Ubuntu’s 14.66 seconds. It is time too valuable to be wasted just for a programming test. Read more [here](https://finbarrs.eu/dev/2018/03/17/docker-react/).

#### Architectures

* ```:amd64```, ```:x86_64``` - 64 bit Intel/AMD (x86_64/amd64)

#### Tags Examples

* ```:latest``` latest branch based (Automatic Architecture Selection)

#### Usage

You can pull the image by declaring it in your **Dockerfile** like this: 

```
FROM 0xnu20/alpine:latest
```

#### License

This project is licensed under the [WTFPL License](LICENSE) - see the file for details.

#### Copyright

(c) 2020 [Finbarrs Oketunji](https://finbarrs.eu).
