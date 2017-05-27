# instagram_batch_downloader
A python script which allows you to download all the photos and video under an instagram user's page.


## Dependencies
+ [python]
+ [requests]

## usage:
+ -u username  
    The username. eg: NASA, adidas

+ -t download_type  
    An integer which indicates the download_type.  
    1 for video  
    2 for photo  
    3 for both  
    The default value is 3.

+ -m max_page:  
    The maximum number of pages that you want to download.  
    The default value is 9999.  
    Normally each page contains 12 files

+ -C  
    Continue the last download


## examples:
```python
python3 go_spider.py -u nasa -m 5 -t 3
```

```python
python3 go_spider.py -C
```

## LICENSE

       Copyright 2017 Kangel Zenn

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

[requests]:https://github.com/kennethreitz/requests
[python]:https://www.python.org/