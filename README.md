# pyspark_notes

### Environment Management Articles
- https://www.inovex.de/blog/isolated-virtual-environments-pyspark/
- https://databricks.com/blog/2020/12/22/how-to-manage-python-dependencies-in-pyspark.html

1. `zip` src file
    - uses Makefile

```bash
# MakeFile
build:
    mkdir ./dist
    cp main.py ./dist
    cd ./src && zip -r ../dist/src.zip .
```

