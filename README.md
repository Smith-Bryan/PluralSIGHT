# PluralSIGHT


It’s better to use a list
Because you cannot ad to an already set array
If you have 8 spaces and only 4 are filled with data the rest will be null
If you call the size with 3 values but 8 spaces
And you try to get the size you will always return 8 even though 5 of those three spaces are empty


Types are inferred
Maps use .put() to add keys and values
Uses containsKey returns true or false
.get() to

Put comparison operator first


.entrySet() returns a set of the key/value entries used for iterating

Hashmap - no particular order
Linked map order they were entered
Tree map alpha numerically lexiocligraphical


Sets don’t allow repeated values
.RetainAll() gets intersection


TO LOOP THROUGH A MAP YOU MUST:
 for (Map.Entry<String,String> entry : gfg.entrySet())  
            System.out.println("Key = " + entry.getKey() + 
                             ", Value = " + entry.getValue()); 
    } 
} 


TO LOOP THROUGH A COLLECTION:
  // Get the iterator
    Iterator<String> it = cars.iterator();

    // Print the first item
    System.out.println(it.next());
  }
}

To loop through a collection, use the hasNext() and next() methods of the Iterator:
while(it.hasNext()) {
  System.out.println(it.next());
}
