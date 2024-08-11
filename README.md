## Explorando os Recursos de IA Generativa com Copilot e OpenAI
Desafio de projeto


## 🚀 Introdução
Projeto em atendimento ao Desafio de Recurso: Explorando os Recursos de IA Generativa com Copilot e OpenAI


## 🎯 Desafio!💪🤓

Utilização de ferramentas de reconhecimento de texto em imagens

## 📒 Descrição
Criação das pastas inputs (com as imagens utilizadas) e outputs (com os resultados de reconhecimento de texto em imagens)

## 🤖 Tecnologias Utilizadas
Copilot e busca de imagens

## 🧐 Processo de Criação
Busca por imagens através de prompts com IA Generativa do Copilot e busca por imagens.


A busca ocorreu em 5 diferentes cenários:


 **A) texto de 300 caracteres, gerados pelo Copilot, exportado para PDF**
 
![prompt 300 caracteres](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/prompt%20300%20caracteres.png)


Resultado em PDF:

![PDF 300 caracteres](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/texto%20300%20caracteres%20em%20PDF.png)


**O resultado foi bem sucedido!**

![leitura do texto 300 caracteres](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/output/texto%20300%20caracteres%20convertido%20PDF%20x%20%20texto.png)


 
 **B) imagem de cartaz, exportada para JPG**
 
![cartaz JPG](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/inca-outubrorosa_cartaz.jpg)

**O resultado foi satisfatório.**


Com ressalva de que faltou detalhe do número de telefone informado no canto do cartaz (DISQUE SAÚDE 136) que não foi identificado. Por isso o alerta de sempre revisarmos o resultado do reconhecimento de texto em imagens, não se limitando à prática de CTRL+C / CTRL+V.

![leitura do cartaz](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/output/inca%20convertido%20em%20texto.png)



  **C) imagem com escrita vertical nos 2 sentidos, exportada para PNG**

![PNG lombada](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/lombada-americana-europeia50.png)


**O resultado foi bem sucedido!**

![leitura da lombada](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/output/lombada%20convertida%20em%20texto.png)



  **D) imagem de placa de veículo, exportada para PNG**

![placa de veículo PNG](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/placa%20veiculo.png)


**O resultado foi bem sucedido!**

![leitura da placa](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/output/placa%20convertida%20em%20texto.png)


 
  **E) planilha simulada de vendas, gerado pelo Copilot, exportada para XLSX**

![prompt de planilha de vendas](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/prompt%20planilha%20vendas.png)


![planilha gerada](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/copilot%20planilha%20vendas.png)


![planilha em XLSX](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/planilha%20vendas%20no%20Excel.png)



**O resultado foi bem sucedido!**

![leitura da planilha](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/output/planilha%20vendas%20planilha%20x%20texto.png)



## ⚡👁 Insights

No caso C, resultado do reconhecimento do texto foi bem sucedido, da imagem com escrita vertical nos 2 sentidos, sendo escolha premeditada, para verificar se o Copilot faria a leitura nos 2 sentidos corretamente. O mesmo não ocorreu com outras ferramentas de OCR, em que leu corretamente somente 1 dos sentidos e ficou "perdido" no outro sentido, com caracteres desconexos.


No caso E, da planilha simulada, acrescentou-se solicitação adicional, fazendo o reconhecimento de texto não pela planilha, mas por imagem da planilha em PGN e solicitando a totalização de vendas, que não constava na imagem enviada. E também retornou a informação corretamente.


![prompt da imagem da planilha e totalizacao](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/inputs/prompt%20imagem%20planilha%20vendas%20e%20totalizacao.png)


![leitura da imagem da planilha e totalizacao](https://github.com/bids-work/explorando-os-recursos-de-ia-generativa/blob/main/output/imagem%20planilha%20vendas%20e%20totalizacao.png)

 
 
## 🚀 Resultados

Conclui-se que o reconhecimento de texto em imagens é uma ferramenta muito interessante e útil, podendo propiciar aumento na eficiência e produtividade em nosso dia-a-dia, tendo em visto os resultados positivos retornados. Ressalte-se a importância da devida revisão dos resultados e necessários cuidados em sua utilização.


```
