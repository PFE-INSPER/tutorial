# Ferramentas e estrutura do projeto

## Ferramentas
As principais ferramentas utilizadas neste tutorial estão listadas abaixo:

<center>

| Tools          | Function                   | Developer  |
| -------------- |:--------------------------|:-----------|
| [Watson Assistant](https://www.ibm.com/products/watson-assistant)  | Ferramenta para criação de chatbots     | IBM        |
| [Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding)  | Reconhecimento de linguagem natural     | IBM        |
| [IBM Cloudant](https://cloud.ibm.com/catalog/services/cloudant)  | Armazenamento de dados     | IBM        |
| [IBM Cloud Foundy](https://www.ibm.com/cloud/cloud-foundry)  | Implementação e gerencialmento de servidores     | IBM        |
| [Node.js](https://nodejs.org/en/)  | Backend do servidor     | Node.js Foundation  |
| [React](https://reactjs.org/)  | Backend do servidor     |Node.js Foundation  |
| [Express](https://expressjs.com/) | Backend do servidor     | Node.js Foundation  |



</center>

## Bibliotecas utilizadas: 
* [Watson Platform Component React Component Library](https://watson-developer-cloud.github.io/react-components ) 
* [IBM-Cloud-Sdk-Core](https://pypi.org/project/ibm-cloud-sdk-core/)
* [IBM Watson](https://pypi.org/project/ibm-watson/)
* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Selenium](https://selenium-python.readthedocs.io/)
* [Pandas](https://pandas.pydata.org/)
* [JSON](https://docs.python.org/3/library/json.html)
* [Tqdm](https://www.google.com/search?q=python+tqdm&oq=python+tqdm&aqs=chrome..69i57j0i512l3j0i22i30l6.3883j0j7&sourceid=chrome&ie=UTF-8)
* [Urlib](https://docs.python.org/3/library/urllib.request.html)


## Estrutura das pastas

``` 
├── README.md 
├── .gitignore 
├───client
│   ├───public
│   └───src
├───docs
├───node_modules
├───scripts
│   └───│Cloudant.ipynb
│   └───│Criacao Modelo.ipynb
│   └───│news.csv
│   └───│skill-Assitant.json
│   └───│TesteAcuracia.ipynb
│   └───│Treinamento.ipynb
└───server
    └───│IBM-cloud-URLS.txt
    └───│index.js
    └───│watson-assistant.js
    └───│watson-discovery.js
``` 


## Fluxo do Projeto
* [Criação instância NLU](nlu.md)
* [Treinamento do modelo e enriquecimento dos dados](enriquecimento.md)
* [Subir arquivos para o Cloudant ](cloudant.md)
* [Criação e configuração do Assistant](assistant.md)
* [Configurar o servidor](cloudfoundry.md)
* [Aplicação funcionando](aplicacao.md)


!!! Importante
    Para seguir os próximos passos é necessário que você tenha uma conta [IBM Cloud](https://cloud.ibm.com/registration). 