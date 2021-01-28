# DSI Notes

## Relevant Links
* [Visualizing scipy.stats] (https://stackoverflow.com/questions/37559470/what-do-all-the-distributions-available-in-scipy-stats-look-like)

* [Math Equations] (https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

----------------------------------

# Bash Scripting
* bash profile location on OSX: '~./bash_profile'


### make a bash function

```bash
function gitadder(){
    git pull
    git add .
    dt=$(date '+%d/%m/%Y %H:%M:%S');
    git commit -m "Auto Updated: $(date '+%a
    %M:%H %h %d %Y')"
}
```
--------------------------------
```python
[num for num in range(100)]
```

## functions to remember

```python
def factorial(n):
    prod = 1
    for num in range(n+1):
        prod *=num
    return prod
```

-----------------------------

## Machine Learning Workflow

### Cross Validation
```python
# train/test split
```

### k-fold Cross Validation

### Bootstrap

-------------------------------
# Sorting Algorithms

## Bubble Sort

```python
# hand coded algorithm
```

