# indexer_and_word_search
Exercício Programa Indexador e Buscador de Palavras

## Como Compilar e Executar o Programa:
O programa foi desenvolvido e testado com a execução pelo Prompt de Comando do Windows.

1. Basta abrir o CMD, inserir o comando:
```
cd <filePATH>
```
- Substituindo <filePATH> pelo local onde os arquivos foram salvos

2. Compilar o arquivos .c corretamente:
```
gcc main.c -o <saida.exe> 
```
- Substituindo <saida.exe> por um nome a ser escolhido para a sua conveniência

3. Para rodar o programa já compilado:
```
<saida> <texto.txt> <tipo_de_estrutura>
```
- Substituindo <saida> pelo executável gerado pelo comando anterior e <texto.txt> pelo arquivo de texto a ser analisado

- em <tipo_de_estrutura> pode ser escolhido "lista" ou "arvore", para serem utilizadas as diferentes estruturas mencionadas

4. Por fim, basta executar os comandos descritos:
```
> busca <palavra>
```
- Substituindo <palavra> pela palavra a ser buscada.
```
> fim
```
- Para finalizar o programa

- **IMPORTANTE**: Os limites para a leitura do texto são: Linhas de 1000 palavras com 50 caracteres, número máximo de linhas indeterminado.
- O programa foi feito para ser executado no Windows, com o Prompt de Comando, e não suporta a busca de palavras com caracteres acentuados, sendo recomendável apenas a busca em textos em inglês ou outra linguagem sem acentuação.
- O arquivo de texto a ser lido tem que estar codificado em UTF-8 para funcionar corretamente.
