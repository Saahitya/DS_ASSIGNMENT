# DS LRU\(Least Recently Used\) Cache Assignment
:+1

## DESCRIPTION
1. LRU Cache is basically a cache implemented with the cache replacement technique of replacing the least recently accessed item.
2. This LRU Cache is implemented using a doubly linked list style queue and standard python dictionary.
3. Cache is defined with two methods\-get\(\) and put\(\)
	* get\(key\)\- searches the cache for the item.
	> if item is found in dictionary using the key\-retrieve it and move to back of the queue.
	> else not found in cache and must check datadump array.
	* put\(item\)\-puts the item in the cache
	>if cache is full it removes the front of the queue and puts in the back.
	>else just puts it in the back of the queue.
4. the results are timed against a array retrieval technique to compare effiency .

##RUN INSTRUCTIONS
JUPYTER:
1. type "jupyter notebook" in terminal .
2. Choose DS_Cache.ipynb to run .
