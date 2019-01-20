# tutorials

Repo containing the monthly walkthroughs and tutorials from the OPUG meetings.

All of the tutorials can be run using a Jupyter notebook, and support being run from either a docker cotainer, or running them
locally using an installed version of Anaconda or building a virtualenv.

To contribute to the repo, please see the "How to Contribute" section below.

# Quickstart

To get started, we'll want to run:

```python
docker run -p 8888:8888 -v $(pwd)/tutorials:/home/jovyan jupyter/minimal-notebook
```

If you haven't already run the `minimal-notebook` docker image before, docker will automatically download the image and
start a container based on the image.  Once it's downloaded, you'll use the URL provided in the terminal output to access
the Jupyter server.

Note, that some of the tutorials may use different docker-stack images; however, they'll call that out in their individual READMEs.

## How to Contribute

#TODO: Fill this section out.

 # References:

 [Docker for Data Science: Running a Dockerized Jupyter Server](https://www.dataquest.io/blog/docker-data-science/)