tensorflow notebook (for further extensions)

### After updating rebuild and push:

Run:

`docker build -t commandlinegirl/tensorflow .`

and

`docker push commandlinegirl/tensorflow`

### Running

`docker run -it -p 8888:8888 -v ~:/home/data commandlinegirl/tensorflow`

or the original:

`docker run -it -p 8888:8888 -v ~:/home/data gcr.io/tensorflow/tensorflow`
