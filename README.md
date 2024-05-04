Benchmark de Desempenho: WorldClim Data com Pandas vs. PySpark
Este é um projeto de benchmarking desenvolvido em Python para medir o desempenho do processamento de dados da WorldClim utilizando as bibliotecas Pandas e PySpark. O objetivo é comparar o tempo de execução de operações comuns de análise de dados em ambas as abordagens.

Introdução
A WorldClim é uma base de dados de clima global que fornece informações climáticas em uma grade de resolução de cerca de 1 km². Este projeto foca em medir o tempo necessário para processar e analisar dados da WorldClim usando duas abordagens diferentes: Pandas e PySpark.

Métodos de Medição de Tempo
Dois métodos de medição de tempo foram utilizados:

%time Magic Command: Este comando é utilizado no Jupyter Notebook para medir o tempo de execução de uma única linha de código ou de um bloco de código.
timeit(): Este é um módulo em Python que permite medir o tempo de execução de pequenos trechos de código.
Arquivos JSON
Para uma análise posterior dos resultados, este projeto gera arquivos JSON contendo os tempos de execução das operações para ambas as abordagens. Os arquivos JSON estarão disponíveis no diretório de saída especificado no momento da execução do benchmark.

Configuração
Antes de executar os benchmarks, é necessário configurar o ambiente de desenvolvimento:

Instale as dependências listadas no arquivo requirements.txt.
Certifique-se de ter acesso aos dados da WorldClim ou substitua-os por conjuntos de dados similares.
Executando o Benchmark
Para executar o benchmark, siga estas etapas:

Pandas Benchmark:Execute o script pandas_benchmark.py. Ele contém operações comuns de análise de dados usando Pandas sobre os dados da WorldClim.
PySpark Benchmark:Execute o script pyspark_benchmark.py. Ele contém operações equivalentes às do benchmark do Pandas, mas usando o Spark DataFrame.
Os resultados serão salvos em arquivos JSON no diretório especificado.

Resultados
Os resultados dos benchmarks serão exibidos no console ou em um arquivo de saída, dependendo da configuração do script. Os tempos de execução serão comparados entre as abordagens Pandas e PySpark.

Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues relatando problemas, sugerir melhorias ou enviar pull requests.

Licença
Este projeto é distribuído sob a licença MIT.
