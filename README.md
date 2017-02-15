# Basic Object Obtainment Maître d'

Simple Django application to retrieve remote content (file and git repos) and stream back from BOOM server.  Content may be optionally Base64 encoded by BOOM. Support is also provided for chunking retrieved data to arbitrary max MiBs.

## Usage

Use docker to have a server up in 1 minute flat:

```
docker run -d -P gisjedi/boom
```
