# nlp-12-14-2016
Docker image for O'Reilly NLP class

https://www.safaribooksonline.com/live-training/courses/get-started-with-natural-language-processing-in-python/0636920065517/

cd into this directory and build with docker

- `docker build -t nlp-12-14-2016 .`

And then to run it on port 8888:

- `docker run -p 8888:8888 -i -t nlp-12-14-2016`

Then you can go to [http://localhost:8888/](http://localhost:8888/) to see your jupyter notebook.
