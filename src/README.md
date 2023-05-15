Function: hash
Description: The hash function takes a key of type K and generates a hash value for the key. It uses the hashCode() method of the key object and applies the modulo operation with M (the size of the hash table) to determine the index where the key-value pair will be stored.

Function: put
Description: The put function is used to insert a key-value pair into the hash table. It calculates the index using the hash function, and if the chain at that index is empty, it creates a new linked list to store multiple key-value pairs. It then checks the chain to see if the key already exists. If found, it updates the value; otherwise, it adds a new HashNode with the given key and value.

Function: get
Description: The get function retrieves the value associated with a given key from the hash table. It calculates the index using the hash function and then searches the chain at that index to find the matching key. If found, it returns the corresponding value; otherwise, it returns null.

Function: remove
Description: The remove function is used to remove a key-value pair from the hash table. It calculates the index using the hash function and then searches the chain at that index to find the matching key. If found, it removes the corresponding HashNode from the chain, decreases the size, and returns the value; otherwise, it returns null.

Function: contains
Description: The contains function checks if the hash table contains a specific value. It iterates over all the chains in the hash table and checks if any HashNode's value matches the given value. If found, it returns true; otherwise, it returns false.

Function: getKey
Description: The getKey function retrieves the key associated with a specific value in the hash table. It iterates over all the chains in the hash table and checks if any HashNode's value matches the given value. If a match is found, it retrieves and returns the corresponding key; otherwise, it returns null.





