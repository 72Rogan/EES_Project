# Importante referir:

- Hardware: i5/i7/RAM/
- OS: Linux
- Versão do benchmark
- Versão do compilador
- Quantas vezes executaram cada programa (outliers? Como trataram? Descartaram?)
- Gráficos / tabelas
- Conclusões: O que ganhamos/perdemos

## Anexos:
- Todos os csv, execel's, etc



# Benchmark do Java

## Requisitos
1. No benchmark do java é preciso mudar a versão para o java-8.

Como mudar:

- Listar todas as versões do java

```bash
update-java-alternatives --list
```

- Mudar a versão default do java

``` bash
sudo update-java-alternatives --set /path/para/versao/java
```

2. Ter o ant para correr os benchmark


## Como correr?
`ant -p`      [prints out description, including configuration and environment variable settings]

`ant`         [builds all benchmarks, creates a zip file]

`ant dist`    [builds all benchmarks, this is the default]

`ant source`  [builds a source distribution including benchmarks and tools]

`ant bm`      [builds a specific benchmark, bm]

⚠️ Para correr é preciso estar na diretoria ***benchmarks*** 

