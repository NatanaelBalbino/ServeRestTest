# ServeRestTest
[![Badge ServeRest](https://img.shields.io/badge/API-ServeRest-green)](https://github.com/ServeRest/ServeRest/)

### 🎯 O Desafio
Esse desafio tem por intúito se tornar como um portifólio e instrumento de estudo de testes de API.

### O SUT (Software  Under Test)
Chegou ao meu conhecimento esse belíssimo trabalho open source chamado ServeRest que contém uma bélissima documentação visivel pelo Swagger e Endpoints Publicos de APIs. _Estou compreendendo a melhor forma de dar crédito ao dono do projeto._
- Repositório do projeto: [ServeRest](https://github.com/ServeRest/ServeRest) 

## 🛠 Ferramentas usadas no Desafio
### O Postman
Plataforma API: Além de ser extremamente completa para a realização dos testes tenho limitações de hardware, pois meu computador é um iMac com MAcOS 10.13 High Sierra e não tem como realizar os testes com ferramentas como k6 ou Jmeter.
- Caso queira executar os Testes via Desktop: [Postman Dowload](https://www.postman.com/downloads/)
- Caso queira executar os Testes via Web: [Postman Web](https://www.postman.com/)

### O Notion
Ferramenta para Gestão do Projeto que será utilizada para:
- Gestão do Projeto [ServeRestTest](https://qa-natanaelbalbino-xp.notion.site/ServeRestTest-1cbaf558677880788b63db1c6f0ad4a4)
	- Descrição do Projeto;
	- Análise e Decupagem da Documentação;
	- Decisões Técnicas quanto aos Testes;
	- Escrita dos Cenários de Teste Funcionais e não Funcionais;
	- Acompanhamento das Tarefas de Cenário de Teste, Erros e Melhorias;

## 🗄️ Compreendendo o Projeto
### Desafio do Versionamento do Código
Por conta da integração do Postman com o GitHub e demais ferramentas de versionamento ser pago me utilizarei da ideia do Manish Verma do Canal Software Testing Mentor:
- Link do Vídeo: [Postman Tutorial #79 - How to Push Postman API Tests in Github](https://www.youtube.com/watch?v=ZWIprDf55CY)

### Como usar o Projeto
Conforme o Vídeo acima:
1. Clonar o Repositório
2. Importar o arquivo ```Serverest API.postman_collection.json``` no Postman
3. Realizar os Testes ou Alterações

Sempre que for subir as alterações para o GitHub: Salvar e Exportar o Projeto do Postman no diretório do versionamento.

### Cobertura dos Testes
Os tipos de testes que pretendo estudar e demonstrar nesse portifólio são:
- Teste de Funcionalidade
- Teste de Contrato
- Teste de Performance

Todos esses testes terão suas asserções automatizadas no Postman para facilitar a validação.

## 📊 Status do Projeto
| Descrição                                   | Status            |
| :------------------------------------------ | :---------------- | 
| 1. Analisando o projeto                     | ✅ DONE           |
| 2. Gerar YAML do Projeto                    | ✅ DONE           |
| 3. Análise de Requisitos                    | ✅ DONE           |
| 4. Teste Funcional                          | ▶️ IN PROGRESS   🔵|
| 5. Teste de Performance                     | 🔴 TO DO          |
| 3. Análise de Requisitos                    | 🔴 TO DO          |

## 💡 O Futuro do Projeto
Utilizarei esse reposítório para usar mais de um tipo de ferramenta e método para fazer os testes do ServeRest.
Algumas das ideias que tenho em mente para implementar e estudar seria:
- Adicionar o uso de uma API que gere dados para fazer os testes;
- Utilizar uma IA para fazer ou refazer as coisas que já fiz e análisar a eficiência e aprender mais;
- Quando superar meu limite de Hardware:
	- Utilizar o docker para testes de Performance - assim como indicado na documentação do ServeRest;
  - Utilizar ferramentas mais robustas para os diversos tipos de teste de performance como: k6, Jmeter e Gatling.
