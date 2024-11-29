# ExemploARQUIVO15_XLS

Este projeto é um exemplo de como integrar várias bibliotecas Java para criar uma aplicação de interface gráfica com **Swing**, manipulação de arquivos Excel, gráficos interativos, criptografia, e desenhos gráficos utilizando `stddraw`.

## Funcionalidades

- **Interface Gráfica com Swing**: Utilização de menus e `JInternalFrame` para criar uma aplicação modular e com janelas internas.
- **Manipulação de Arquivos Excel**: Leitura e escrita de planilhas `.xlsx` com Apache POI.
- **Geração de Gráficos**: Criação de gráficos interativos com a biblioteca JFreeChart.
- **Criptografia**: Funções de criptografia para proteger dados sensíveis.
- **Desenhos Gráficos**: Utilização da biblioteca `stddraw` para desenhar formas gráficas e realizar manipulação visual.

## Dependências

Este projeto utiliza as seguintes dependências Maven:

- **Apache POI**: Biblioteca para manipulação de arquivos Excel.
  - `poi` (versão 5.2.3)
  - `poi-ooxml` (versão 5.2.3)
- **Apache Commons Collections**: Para manipulação de coleções avançadas.
  - `commons-collections4` (versão 4.4)
- **Log4j**: Biblioteca para logging detalhado de eventos.
  - `log4j-core` (versão 2.20.0)
  - `log4j-api` (versão 2.20.0)
- **JFreeChart**: Biblioteca para a criação de gráficos interativos.
  - `jfreechart` (versão 1.0.13)

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
```
