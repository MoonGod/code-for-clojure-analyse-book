# read-csv

A Clojure library designed to ... well, that part is up to you.

## Usage
In REPL:
1) (use 'incanter.core
	   'incanter.io)
2) (read-dataset "resources/small-sample.csv") will read dataset from csv file.

3) (read-dataset "resources/small-sample-header.csv" :header true) will remove header.

Note:

 In Incanter, a dataset is a table, similar to a sheet in a spreadsheet or a database 
table. Each column has one field of data, and each row has an observation of data. Some 
columns will contain string data (all of the columns in this example did), some will contain 
dates, some numeric data. Incanter tries to detect automatically when a column contains 
numeric data and coverts it to a Java int or double. Incanter takes away a lot of the pain  
of importing data.


## License

Copyright © 2014 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
