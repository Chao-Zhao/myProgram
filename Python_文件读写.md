
## 指定UTF-8编码格式读入 ##


```python
import codecs
	with codecs.open(fileName, encoding = "utf-8") as fin:
	for line in fin:
		...

```
	

## 指定UTF-8编码格式写入 ##

```python
import codecs
    fout = codecs.open(fileName, "w+", "utf-8")
    fout.write("<node id=\"%d\" label=\"%s\">\n" % (i, str))
    ...
	fout.close()
```




