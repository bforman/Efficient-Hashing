# Efficient-Hashing
This is an inquiry resource pertaining to creating efficient hash functions. This repository will provide resources as well as insight into the essentials of hashing, and how to lower the chance of hashing to the same key.

#Problem
We want to learn not only a few different ways to create a hash function, but we also are looking to find ways to minimize the chance of collisions. A collision in the sense of hashing, is the incident in which your hash function maps items in the set to the same key. In the event of a collision the hash function will have to rehash, which will slow down the process of the program being executed.

#Questions
1. What methods of hashing are known in Python?
2. What conventions are known and identified when attempting to create a hash function?
3. Does the design of a hash function vary when dealing with small data sets as opposed to large data sets?
4. Does the EchoNest provide any information to developers that assist in constructing hash functions?

#Resources
1. [Python Hashing Algorithms](http://effbot.org/zone/python-hash.htm)
2. [Different Hashing Methods](http://www.partow.net/programming/hashfunctions/)
3. [Using hashlib](http://www.pythoncentral.io/hashing-strings-with-python/)

#Relevance of Python Hashing Algorithms:
This resource provides insight on how to hash in Python using a couple different data types. It also provides some examples of the structure that python hash functions follow. This reference can be a good starting point to forming an efficient hash function. This answers question: 1. What methods of hashing are known in Python?

#Relevance of Different Hashing Methods:
This link analyzes multiple methods used in attempting to create a hash function. It highlights approaches such as bit biases, cryptographic hashing, generic hashing, use of prime numbers, and others. Incorporation of these tactics in the formation of our hash functions will provide as useful tools in crafting collision resistant hash functions. The addition of some of these hashing techniques to existing algorithms can transform a good hash function into a solid one. This answers question: 2. What conventions are known and identified when attempting to create a hash function?

#3. Does the design of a hash function vary when dealing with small data sets as opposed to large data sets?
At a practical level the size of the data set does not effect the relative efficiency of a hash function too much. Although it should be pointed out that as more items get added to the database the chance of a collision occuring will increase. As a result, it is more difficult to maintain a satisfactory hash function when dealing with big data.

#Relevance of Using hashlib:
hashlib is the module that EchoNest uses in its script that performs the hashing of the tracks in its million song database. This reference provides information on how to effectively use hashlib to your advantage. Echonest works with MD5 files and this link goes into detail on using hashlib with MD5 files, so it will be useful when working with the EchoNest database. This is answering question: 4. Does the EchoNest provide any information to developers that assist in constructing hash functions?
