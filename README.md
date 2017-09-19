# Galaxy mothur Toolset

All information pertaining to the Galaxy mothur Toolset (GmT) project

## Publication

This work has been published here (submission in progress)

## Docker

To run the docker image

```
docker run -d -p 80:8080 quay.io/shiltemann/galaxy-mothur-toolset
```

open a browser (firefox/chrome/safari, not IE) and navigate to `localhost:8080`. Log into Galaxy using the following credentials: `admin@galaxyproject.org:admin`. The workflow has been imported into this account, and all test data has been uploaded to a shared data library.


To build the docker image from scratch, clone this repository, and run the following command from its root directory:

```
docker build -f docker/Dockerfile .
```


## Training
There is a training module on how to perform the Mothur MiSeq SOP in Galaxy available from the Galaxy Training Network (GTN) site [here](http://galaxyproject.github.io/training-material/topics/metagenomics/)
