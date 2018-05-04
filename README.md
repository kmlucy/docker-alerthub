# docker-alerthub

To run:
```
docker run --name alerthub -v /PATH/TO/CONFIG/config.js:/app/etc/config.js:ro kmlucy/docker-alerthub
```

You must create the config file before running. You can get an example file from [here](https://github.com/Ardakilic/alerthub/blob/master/etc/config.example.js).

Based on: [Ardakilic/alerthub](https://github.com/Ardakilic/alerthub)
