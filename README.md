# Datastructure
by Thikamporn Simud 5910401033
This resipotory contain program

```
rasa data split nlu --training-fraction 0.8
```

```
rasa train nlu
```

```
rasa test nlu -u test_set.md --model models/nlu-20200123-091659.tar.gz
```

```
rasa test nlu --config config.yml --cross-validation -f 10 --model models/nlu-20200122-214156.tar.gz
```
