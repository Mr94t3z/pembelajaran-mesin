# Deep Belief Networks

### Requirement:

- [ ] git
- [ ] docker

### Execute

#### 1. clone and cd directory

```
git clone https://github.com/albertbup/deep-belief-network
```

```
cd deep-belief-network
```

#### 2. create image

```
docker build --tag muhamadtaopik/deep-belief-network .
```

#### 3. run the container and exec

```
docker run --rm -it -v ${PWD}:/code muhamadtaopik/deep-belief-network bash
```

#### 4. evaluate model

```
python example_classification.py
```

```
python example_regression.py
```

```
python example_unsupervised.py 
```
