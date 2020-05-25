## 📚  Descrição 

O software tem o objetivo de enviar uma mensagem padrão para uma lista de contatos via whatsapp web automaticamente usando Delphi + Python

## 📢 Como executar

Requisitos:

Google Chrome v83 <br> (Caso queria usar as verões 80 ou 81, deve renomear o arquivo chromedriver para chromedriver83 e retirar o codigo da versão do chromedriver desejado para ficar com o nome de chromedriver)
Microsoft Excel ou Similar<br>

Baixar o arquivo <a href ="https://github.com/paulowiz/envioMensagensWhatsAppProject/blob/master/Software%20Compilado.rar"><b>Software Compilado.rar</b></a> e executar o <b>SistemaDeEnvio.exe</b>, preencher a <b>planilha_padrão.xls</b> com os nomes e números desejados , usar o <b>SistemaDeEnvio</b> aberto para importar o xls, digite a mensagem 

![gif](https://user-images.githubusercontent.com/18649504/82680684-059a2d00-9c23-11ea-980f-055d88dc8bc2.gif)

## 🚀 Tecnologias Usadas 

<img src="https://user-images.githubusercontent.com/18649504/66262823-725cd600-e7be-11e9-9cea-ea14305079db.png" width = "100">

<img src="https://user-images.githubusercontent.com/18649504/82679757-bbfd1280-9c21-11ea-9502-fc5cad416018.png" width = "200">

## 📌 Estrutura do Projeto 
    |-- dprInterfaceWhatsap.dproj ( Projeto de Interface do software e lógicas)
    |-- Service/main.py ( Serviço feito em python que chama whatsapp web)
    
   <br>
   <p>O sistema feito em delphi recebe a planilha padrão, valida os números e gera os txts contato.txt e mensage.txt,acionando o serviço em python para ler os txts,encaminhando as mensagens.</p>



## 🔓 Licença 
MIT © [Paulo Mota](https://www.linkedin.com/in/paulo-mota-955218a2/)
