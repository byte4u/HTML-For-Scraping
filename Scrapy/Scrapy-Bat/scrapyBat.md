# 'scrapy' is not recognized as an internal or external command, 
operable program or batch file. #831

###### BYTE4U - IT Solutions

To solve this problem, you can go to the location where python was installed. 
Look for a folder called Scripts. In that folder, you must create a file called 
"scrapy.bat". This file must contain the command below:

``` batch
@echo off
python -mscrapy.cmdline %*
```
## Reference
@pablohoffman( https://github.com/scrapy/scrapy/blob/a8f45dc6dd4fbc371ff6fd4e90d7e086319ad0c8/extras/scrapy.bat)
