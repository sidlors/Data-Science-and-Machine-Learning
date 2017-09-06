# Python-Data-Science-and-Machine-Learning-Bootcamp
Repo for Python Data Science and Machine Learning Bootcamp

### Build your own image

docker build --force-rm=true --no-cache=true  . -t sidlors/machine-course


### start container

docker run -d --name curso -p 8888:8888 sidlors/machine-course

### Start with jupyter

see logs container

$docker logs curso

please, find something like this:


> http://localhost:8888/?token=4cd5d158c05ae625fe111d59671763dcc030d6959416b6c4


In this case you token is (and it will be untill you don't stop the container)

**f0bca478912b475173a4a4e58df539915f1f29cc93abc0fa**

if you logout and you want to login use must to use yout tokens

### Open notebook with Browser

![](https://i.imgur.com/mJX5jSj.png)


### start/stop  container

Use Stop command for stoping container

$ docker stop curso

So if you run other container (and start the same container, docker start curso) repet the process of see logs for looking the token.


### Finally enjoy the lectures


