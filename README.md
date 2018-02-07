How a beginer setup virtualenv example in python

# virtualenv

#### 1- install virtualenv
```
$ pip install virtualenv
```

#### 2- Init project
```
$ virtualenv virtualEnvExample
//virtualenv -p /usr/bin/python2.7 virtualEnvExample
```

#### 3- To begin using the virtual environment, it needs to be activated
```
$ source virtualEnvExample/bin/activate
```

#### 4- Install packages as usual
```
$ pip install requests
```


# Finished

#### 5- Run the script
```
$ python main.py
```

#### 6- Deactivate
```
$ deactivate
```

## Reference
 - [http://docs.python-guide.org/en/latest/dev/virtualenvs/](http://docs.python-guide.org/en/latest/dev/virtualenvs/)