
Room SQLite Difference Finder
==================================================

Room SQLite Difference Finder helps Android Developers migrating from SQLITE to ROOM DATABASE. The Error logged by the Android Studio is pretty difficult to understand and to trace out which column is causing the error is a big headache. 

After trying to find an easy way to check the difference between the expected and found output, it became evident there is none or that Search Engines haven't indexed it yet.

So came up with an easy solution for it.
Don't trouble yourself anymore with manual checking of each and every word, line by line.

 1. Just paste the output of the Android Logcat in the relevant areas and press GO.
 2. If you get no error, Press Compare.
 3. You are done.

It's really easy. Try it using the sample data.

Room SQlite Difference Finder is built upon amazing JSON Diff. All the hard work for it goes to **Zack Grossbart and JSONLint Team**.



Credits
==================================================


**JSON Diff**

JSON Diff expands on the amazing work by the guys at [jsonlint.com](http://www.jsonlint.com) and provides a semantic compare tool for JSON documents.

I often work with large documents and it's difficult to see the differences between them.  Normal text compare tools work well for finding the differences in JavaScript code, but JSON data can have many differences in the text that don't actually change the data.  

JSON Diff sorts, formats, and compares two JSON documents to find the actual semantic differences instead of just the text ones.

Try it out:  [http://www.jsondiff.com](http://www.jsondiff.com)

Run the built-in unit tests:  [http://www.jsondiff.com/index-test.html](http://www.jsondiff.com/index-test.html)



Copyright (c) 2018 HRankit.

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

```
