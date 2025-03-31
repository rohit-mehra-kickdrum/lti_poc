## Build Command
```
docker build . -t ltipoc
```

## Run Command
```
docker run -p 5003:5003 -p 8888:8888 -t ltipoc
```


Once the container is running, you can access the jupyter notebook at http://localhost:8888.

The notebook with the code is available at http://localhost:8888/tree/jupyter/notebooks/LTI.ipynb.


Once the container is running, the platform will be running at http://localhost:5003.
