# Julia Notebook for Investigating Jinteki.net Game Logs

Best run out of a docker container.
```
% docker run -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes --rm -v $PWD:/home/jovyan/work jupyter/datascience-notebook
```

Data can be dumped from a JNet install via:
```
% lein get-game-stats /tmp/data.csv "2021-07-20"
```

