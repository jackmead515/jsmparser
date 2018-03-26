# jsmparser

### JSMParser is a wrapper class to organize a specific key-value pair syntax.

The syntax is as follows:

`key: value`<br/>
`key_1: value`<br/>
`key_2: value`<br/>

where each key-value pair is on a new line.

To use properly...
* Call constructor with a valid path to a file that has already been created. 
* Then, call the load method to load any key-value pair that is present in the file.
* After this, use the set and get methods to use the data that was loaded.
* Finally, call the save method with no parameters to save the data back to the file.

This cycle can be used repeatedely

