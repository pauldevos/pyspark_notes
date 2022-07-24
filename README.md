# spark_notes

### Command Line Arguments
`pyspark --master "local[*]"`  # runs local jobs with all cores








### Setting up Scala (build) with VSCode
- https://www.youtube.com/watch?v=iATmBDxlYAA&list=PLTx-VKTe8yLxYQfX_eGHCxaTuWvvG28Ml&index=10

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

