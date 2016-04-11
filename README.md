# RStudio compmetagen release

Extends the docker image [rocker/rstudio](https://hub.docker.com/r/rocker/hadleyverse/),
providing libraries for computational metagenomics.

## Available Tags/Versions

- latest: GitHub snapshot

## Quickstart

1. Download the latest version:

   `docker pull compmetagen/rstudio`

2. Run an instance of the image, mounting the host directory:

   `docker run -v /Users/davide/rstudio:/home/rstudio -d -p 8787:8787 compmetagen/rstudio`

3. Determine the ip address of your machine:

   `docker-machine ip`

4. Using a web browser visit that address appended with the port (8787), e.g.:

  `192.168.99.100:8787`

5. You can now login using default username (rstudio) and password (rstudio).
