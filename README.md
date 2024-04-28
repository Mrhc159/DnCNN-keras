### Dependence
```
tensorflow
keras2
numpy
opencv
```

### Prepare train data
```
$ python data.py
```

Clean patches are extracted from 'data/Train400' and saved in 'data/results_data'.
### Train
```
$ python main.py
```

### Test
```
$ python main.py --only_test True --pretrain 'path of saved model'
```


### Results




