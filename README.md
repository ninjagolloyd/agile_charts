<snippet>
  <content>
# Agile.js
 
Agile.js is a jquery plugin that makes it easy to modify tables and create graphs from tables and csv's.

Currently under construction.
 
## Usage
 
To create a graph from a table: 

    Agile.createGraph({
        dataType:'table',
        identifier: '#myTable', //or .myTable 
    });

To create a graph from a csv:

    Agile.createGraph({
        dataType:'csv',
        identifier:'http://url.to/my.csv'
    })

To append a column in a table:

    Agile.tableOps.addColumn({
        name: 'My New Column',    //this will be displayed as the header text of the new column 
        col1: 'Benefit',          //header text of first column to base new column value off of
        col2: 'Cost',             //header text of second column to base new column value off of
        operation: 'subtract',    //operation to perform, in this case, col1 - col2
    })

## Contributing
 
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :P

## Credits
 
Creator: Mike Johnson Jr.

Graphs powered by: HighCharts
 
## License
 
Copyright (c) 2014 Mike Johnson Jr

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

</content>
</snippet>
