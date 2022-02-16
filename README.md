# poc-sheets-nodejs
Poc para trabalhar com planilhas no node utilizando 2 libs para teste: *xlsx* e *xlstream*.   
  
## Comandos para criação do projeto  
1) mkdir poc-sheets-nodejs (nome do diretório do projeto)  
2) cd poc-sheets-nodejs  
3) npm init -y (comando para criação do projeto)  
4) ls  
  
## Comando para executar o projeto  
- Executando o teste da lib xlsx: **node xlsx/script.js**  
- Executando o teste da lib xlstream: **node xlstream/script.js**   

## Sobre as libs utilizadas  

### XLSX
**npm i xlsx**  
Lib utilizada para trabalhar com planilhas no Node JS. A leitura é feita de uma só vez, ou seja, carrega todo o conteúdo da planilha para conseguir manipular.  
- Link para referência: https://www.npmjs.com/package/xlsx  
  
### Xlstream
**npm i xlstream**  
Lib utilizada para trabalhar com planilhas no Node JS. A leitura é feita via stream, não precisa esperar carregar todo o conteúdo do arquivo para conseguir manipular os dados.  
- Link para referência: https://www.npmjs.com/package/xlstream  

