# Bloom-Filter-App
-- Implementaion of `Bloom Filter` datastructure.  
-- Showcase use of implemented bloomfilter to do lookup on a list of elements loaded from file on application startup.

## About Bloomfilter
Bloom filter is a probabilistic datastructure which gives only one piece of information, True or False based on whether the key is member of set or not. It’s an incredibly space efficient datastrucuture that is often used as a first line of defense in high performance caches. 

Bloom filter takes up very small piece of memory compared to other datastructure as instead of storing each value, a bloom filter is simply an array of bits, using which it identifies the presence of the key in the filter.

There is also possibility of collision when two keys may map to same index in the bit array, this makes `Bloom Filter` a `probabilistic` datastructure where `False Positives` are possible.
