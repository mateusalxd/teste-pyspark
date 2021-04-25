# Testando PySpark

## Passos iniciais

- baixar a imagem do Jupyter com o PySpark

```bash
docker pull jupyter/pyspark-notebook
```

- iniciar o notebook

```bash
# o parâmetro utilizado na montagem do volume é o diretório do repositório
docker run -it --rm -p 8888:8888 -v $(pwd):/home/jovyan/work jupyter/pyspark-notebook
```

## Referências

- [Quickstart — PySpark 3.1.1 documentation](https://spark.apache.org/docs/latest/api/python/getting_started/quickstart.html)
