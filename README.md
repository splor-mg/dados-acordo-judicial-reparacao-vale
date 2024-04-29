# dados-acordo-judicial-reparacao-vale

[![Updated](https://github.com/splor-mg/dados-acordo-judicial-reparacao-vale/actions/workflows/all.yaml/badge.svg)](https://github.com/splor-mg/dados-acordo-judicial-reparacao-vale/actions/)

## Pré-requisitos

Esse projeto utiliza Docker para gerenciamento das dependências. Para fazer _build_  da imagem execute:

```bash
docker build --tag dados-acordo-judicial-reparacao-vale .
```

## Uso

Para executar o container

```bash
docker run -it --rm --mount type=bind,source=$(PWD),target=/project dados-acordo-judicial-reparacao-vale bash
```

Uma vez dentro do container execute os comandos do make

```bash
make all
```

_Gerado a partir de [cookiecutter-datapackage@746d48e](https://github.com/splor-mg/cookiecutter-datapackage/commit/746d48e1f92182f3d9a40a66d8250586334ec78b)_
