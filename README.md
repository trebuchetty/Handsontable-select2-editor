Handsontable-select2-editor
===========================

Handsontable Select2 Editor



Using this custom editor

```JAVASCRIPT
var optionsList = [{id: 1, text: 'jsmith'}, {id: 2, text: 'wjones'}, ...];
var columnsList = [{
                    data: "UserName", // from datasource
                    editor: 'select2',
                    select2Options: { // these options are the select2 initialization options 
                        data: optionsList,
                        dropdownAutoWidth: true,
                        allowClear: true,
                        width: 'resolve'
                    }
                },
                ...
                ];


this.$container = $("#container");
this.$container.handsontable({
    data: [...],
    columns: columnsList
    });
```

I've left out a lot here for brevity, so let me know if any clarification is required.




License

(The MIT License)

Copyright (c) 2013 Sean Riordon <trebuchetty@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
