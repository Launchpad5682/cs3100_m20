# CS3100: Paradigms of Programming (IITM Monsoon 2020)

This is the Github repo for the course CS3100 Paradigms of Programming run at IITM in the Monsoon semester 2020. The course website is here: https://kcsrk.info/cs3100_m20/. 

## Running the Jupyter notebooks

Install [docker](https://docs.docker.com/install/#supported-platforms) for your platform.

```bash
$ git clone https://github.com/kayceesrk/cs3100_m20
$ cd cs3100_m20/lectures
$ docker run -it -p 8888:8888 -v "$(pwd)":/lectures kayceesrk/cs3100_iitm:latest
$ jupyter notebook --ip=0.0.0.0
```

Copy and paste the diplayed URL that starts with `http://127.0.0.1:8888` into
your browser. If you save the changes to the notebook, they are saved locally.
As you go through the course, you will have to do `git pull` in the
`cs3100_m20` directory to get the latest updates from upstream.

## Linux

On Linux, you need to run the docker command with `sudo`:

```bash
$ sudo docker run -it -p 8888:8888 -v "$(pwd)":/lectures kayceesrk/cs3100_iitm:latest
```

## Virtual Box Disk Image

While the docker set up is recommended, an Ubuntu virtual box disk image (VDI)
with the jupyter notebook is also available
[here](https://drive.google.com/drive/folders/1bak0M85dHd6Avvn1AANdFKBaYpomIuzT?usp=sharing).
The password is `cs3100_m20`. The course git repo has been cloned under
`cs3100_m20` in the home directory.  
