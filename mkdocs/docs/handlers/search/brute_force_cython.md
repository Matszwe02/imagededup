## class BruteForceCython
Class to perform search using a Brute force.


### \_\_init\_\_
```python
def __init__(hash_dict, distance_function)
```
Initialize a dictionary for mapping file names and corresponding hashes and a distance function to be used for getting distance between two hash strings.


##### Args
* **hash_dict**:  Dictionary mapping file names to corresponding hash strings {filename: hash}

* **distance_function**: A function for calculating distance between the hashes.


### search
```python
def search(query, tol)
```
Function for searching using brute force.


##### Args
* **query**: hash string for which brute force needs to work.

* **tol**: distance upto which duplicate is valid.

##### Returns
* **List of tuples of the form [(valid_retrieval_filename1**:  distance), (valid_retrieval_filename2: distance)]

