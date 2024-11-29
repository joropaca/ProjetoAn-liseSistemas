# ExemploARQUIVO15_XLS

Este projeto é um exemplo de como utilizar as bibliotecas Apache POI para manipulação de arquivos Excel (XLS/XLSX), Log4j para log e JFreeChart para a criação de gráficos em Java.

## Descrição

Este projeto demonstra a leitura e manipulação de arquivos Excel, geração de gráficos e exibição de logs para acompanhamento da execução do programa.

### Funcionalidades:
- Leitura e escrita de arquivos Excel (XLS, XLSX)
- Geração de gráficos utilizando JFreeChart
- Logs detalhados utilizando Apache Log4j
- Interface gráfica para visualização de gráficos e dados

## Tecnologias Utilizadas

- **Apache POI**: Biblioteca Java para manipulação de arquivos do Microsoft Office (Excel, Word, etc.)
- **Log4j**: Sistema de log para registrar eventos e facilitar o diagnóstico e monitoramento.
- **JFreeChart**: Biblioteca para criação de gráficos dinâmicos e interativos.
- **Maven**: Ferramenta de automação de construção para Java.

## Dependências

O projeto utiliza as seguintes dependências do Maven:

```xml
<dependency>
    <groupId>org.apache.poi</groupId>
    <artifactId>poi</artifactId>
    <version>5.2.3</version>
</dependency>

<dependency>
    <groupId>org.apache.poi</groupId>
    <artifactId>poi-ooxml</artifactId>
    <version>5.2.3</version>
</dependency>

<dependency>
    <groupId>org.apache.commons</groupId>
    <artifactId>commons-collections4</artifactId>
    <version>4.4</version>
</dependency>

<dependency>
    <groupId>org.apache.logging.log4j</groupId>
    <artifactId>log4j-core</artifactId>
    <version>2.20.0</version>
</dependency>
<dependency>
    <groupId>org.apache.logging.log4j</groupId>
    <artifactId>log4j-api</artifactId>
    <version>2.20.0</version>
</dependency>

<dependency>
    <groupId>jfree</groupId>
    <artifactId>jfreechart</artifactId>
    <version>1.0.13</version>
</dependency>
