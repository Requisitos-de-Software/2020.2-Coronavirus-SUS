# Caso de Uso

## Definição
<div style="text-indent: 20px; text-align: justify"> 

Diagrama de caso de uso é uma ferramenta, que faz parte do conjunto de diagramas de comportamento propostos pela UML (Unified Modeling Language), para representar graficamente os requisitos funcionais. Ele oferece uma forma simples de comunicação com os stakeholders em torno das funcionalidades e dos serviços que serão oferecidos aos usuários.
(REINEHR, 2020, p.99)

Em suma, o diagrama de casos de uso representa o usuário e suas interações com o sistema por meio de símbolos (atores, casos de uso, relacionamento).

Especificação dos casos de uso é um documento que tem por objeto descrever o comportamento do casos de uso.(PIMENTEL, 2007, p.17)
</div>

### Utilização
<div style="text-indent: 20px; text-align: justify">
A partir dos requisitos levantados e das características do sistema de ser de interação com o usuário, a equipe decidiu que um diagrama de caso de uso seria útil como uma forma de documentação gráfica do escopo funcional.

Além disso, a equipe decidiu que utilizar a especificação do caso de uso seria interessante para melhor entendimento do caso de uso e para fins de rastreabilidade.

</div>

## Resultados

### **UC01** - Compartilhar teste positivo
<br>

<img width="800" src="https://raw.githubusercontent.com/Requisitos-de-Software/2020.2-Coronavirus-SUS/devel/docs/assets/useCase/compartilharTestePositivo.png">

<br>

|   UC01    | Informações |
|:---------:|---------- |
|Descrição|O ato do usuário de compartilhar o resultado positivo de um teste para o vírus COVID-19|
|Atores|Cidadão brasileiro<br>gov.br|
|Pré-condições|O cidadão brasileiro deve estar conectado a internet <br> O cidadão brasileiro deve estar na página principal do sistema<br> O cidadão brasileiro gerou um código através do ator gov.br<br>O cidadão está com a funcionalidade de notificação de exposição ativada|
|Fluxo principal|1. O cidadão brasileiro clica no botão "Compartilhar teste positivo"<br>2. O cidadão brasileiro insere o token no espaço indicado<br>3. O sistema valida o token pelo ator gov.br<br>4. O sistema notifica o cidadão brasileiro do sucesso de seu compartilhamento |
|Fluxo alternativo|1. O cidadão brasileiro clica no botão "Compartilhar teste positivo"<br>2. O cidadão insere um token errado ou inexistente<br>3. O sistema retorna uma mensagem de erro|
|Fluxo de exceções|1. O cidadão brasileiro clica no botão "Compartilhar teste positivo"<br>2. O cidadão brasileiro não tem o código gerado pelo ator gov.br <br>3. O cidadão brasileiro acessa o ator gov.br e gera o código <br>4. O cidadão brasileiro insere o token no espaço indicado<br>5. O sistema valida o token pelo ator gov.br<br>6. O sistema notifica o cidadão brasileiro do sucesso de seu compartilhamento |
|Pós-condições|O teste positivo do cidadão brasileiro é compartilhado com a aplicação|
|Rastreabilidade|RF09 - Compartilhar teste positivo|

<br>

### **UC02** - Alterar idioma

<br>

<img width="800" src="https://raw.githubusercontent.com/Requisitos-de-Software/2020.2-Coronavirus-SUS/devel/docs/assets/useCase/alterarIdioma.png">

<br>
    
|   UC02    | Informações |
|:---------:|---------- |
| Descrição|O ato do usuário de alterar o idioma do aplicativo|
|Atores|Cidadão brasileiro|
|Pré-condições|O cidadão deve estar na página principal do sistema|
|Fluxo principal|1. O cidadão brasileiro pressiona o botão de alterar idioma<br>2. O cidadão brasileiro escolhe o idioma de sua preferência|
|Fluxo alternativo|Nenhum|
|Fluxo de exceções|Nenhum|
|Pós-condições|O idioma da aplicação é alterado para aquele escolhido pelo cidadão brasileiro|
|Rastreabilidade|RF18 - Internacionalização|

<br>

### **UC03** - Notificar exposição

<br>

<img width="800" src="https://raw.githubusercontent.com/Requisitos-de-Software/2020.2-Coronavirus-SUS/devel/docs/assets/useCase/notificarExposicao.png">

<br>

|   UC03    | Informações |
|:---------:|---------- |
| Descrição|O ato de o sistema notificar o usuário após uma exposição detectada|
|Atores|Cidadão brasileiro, API Exposure Notification, Cidadão brasileiro infectado|
|Pré-condições|O cidadão brasileiro deve estar com as notificações ativadas<br>O cidadão brasileiro deve estar com o Bluetooth ativado<br>O cidadão deve ter sido exposto|
|Fluxo principal|1. O cidadão brasileiro compartilha sua chave via Bluetooth com um cidadão brasileiro infectado<br> 2. O sistema identifica que o cidadão brasileiro sofreu uma exposição<br>3. O sistema envia uma notificação ao cidadão brasileiro informando a sua exposição<br>4. O cidadão brasileiro visualiza as suas notificações|
|Fluxo alternativo|1. O cidadão brasileiro ativa as notificações <br> 2. O cidadão brasileiro compartilha sua chave via Bluetooth com um cidadão brasileiro infectado<br> 3. O sistema identifica que o cidadão brasileiro sofreu uma exposição<br>4. O sistema envia uma notificação ao cidadão brasileiro informando a sua exposição<br>5. O cidadão brasileiro visualiza as suas notificações|
|Fluxo de exceções|1. O cidadão brasileiro compartilha sua chave via Bluetooth com outro cidadão brasileiro<br>2. O sistema não identifica exposição|
|Pós-condições|O cidadão brasileiro é informado com respeito à exposição que sofreu|
|Rastreabilidade|RF05 - Notificar contato com infectado|

<br>

### **UC04** - Apresentar alerta

<br>

<img width="800" src="https://raw.githubusercontent.com/Requisitos-de-Software/2020.2-Coronavirus-SUS/devel/docs/assets/useCase/alertas.png">

<br>

|   UC04    | Informações |
|:---------:|---------- |
| Descrição|O ato do usuário visualizar os alertas|
|Atores|Cidadão brasileiro|
|Pré-condições|O cidadão brasileiro deve estar com o sistema aberto|
|Fluxo principal|1. O cidadão brasileiro navega para a aba de alertas<br>2. O sistema carrega lista de alertas<br>3. O cidadão brasileiro visualiza seus alertas|
|Fluxo alternativo|1. O cidadão brasileiro navega para aba de alertas<br>2. O sistema carrega lista de alertas<br>3. O cidadão brasileiro ativa/desativa os alertas|
|Fluxo de exceções|Nenhum|
|Pós-condições|O cidadão brasileiro é informado a respeito de todos alertas que já recebeu|
|Rastreabilidade|RF17 - Apresentar alerta|

<br>

### **UC05** - Notícias

<br>

<img width="800" src="https://raw.githubusercontent.com/Requisitos-de-Software/2020.2-Coronavirus-SUS/devel/docs/assets/useCase/noticias.png">

<br>

|   UC05    | Informações |
|:---------:|---------- |
| Descrição|O ato do usuário ver as notícias sobre a COVID-19|
|Atores|Cidadão brasileiro, Twitter Ministério da Saúde|
|Pré-condições|O cidadão brasileiro deve estar com o sistema aberto<br>O cidadão brasileiro deve estar conectado a um serviço de Internet|
|Fluxo principal|1. O cidadão brasileiro navega para a aba de notícias<br>2. O sistema carrega as notícias a partir do twitter do Ministério da Saúde<br>3. O cidadão brasileiro consegue ver as últimas notícias|
|Fluxo alternativo|1. O cidadão brasileiro navega para a aba de notícias<br>2. O sistema carrega as notícias a partir do twitter do Ministério da Saúde<br>3. O cidadão brasileiro seleciona uma das notícias<br>4. O sistema redireciona o cidadão brasileiro para o endereço do link da notícia selecionada|
|Fluxo de exceções|1. O cidadão brasileiro navega para a aba de notícias sem estar conectado a algum serviço de Internet<br>2. O sistema apresenta uma mensagem de erro em relação ao carregamento das notícias|
|Pós-condições|O cidadão brasileiro consegue ver as notícias atualizadas com respeito à COVID-19|
|Rastreabilidade|RF03 - Notícias sobre a COVID-19|

<br>

### **UC06** - Informativos

<br>

<img width="800" src="https://raw.githubusercontent.com/Requisitos-de-Software/2020.2-Coronavirus-SUS/devel/docs/assets/useCase/informativos.png">

<br>

|   UC06    | Informações |
|:---------:|---------- |
| Descrição|O ato do usuário ver informativos relacionados à COVID-19|
|Atores|Cidadão brasileiro|
|Pré-condições|O cidadão brasileiro deve estar o sistema aberto|
|Fluxo principal|1. O cidadão brasileiro navega para a aba de dicas<br>2. O sistema mostra todos os tópicos de informativos<br>3. O cidadão brasileiro seleciona um tópico de seu interesse<br>4. O sistema carrega as informações do tópico selecionado<br>5. O cidadão brasileiro pode ler as informações|
|Fluxo alternativo|1. O cidadão brasileiro navega para a aba de dicas<br>2. O sistema mostra todos os tópicos de informativos<br>3. o cidadão brasileiro pesquisa o tópico de informação que é de seu interesse<br>4. O sistema mostra o tópico pesquisado<br>5. O cidadão brasileiro seleciona o tópico mostrado<br>6. O cidadão brasileiro pode ler as informações|
|Fluxo de exceções|1. O cidadão brasileiro navega para a aba de dicas<br>2. O sistema mostra todos os tópicos de informativos<br>3. o cidadão brasileiro pesquisa o tópico de informação que é de seu interesse<br>4. O sistema não encontra o tópico pesquisado|
|Pós-condições|O cidadão brasileiro consegue ver informativos com respeito à COVID-19|
|Rastreabilidade|RF02 - Informativos sobre a COVID-19|

## Referências Bibliográficas
> REINEHR, Sheila. 2020. ENGENHARIA DE REQUISITOS.


> PIMENTEL, Andrey Ricardo, [Projeto de Software Usando a UML](https://www.inf.ufpr.br/andrey/ci162/apostilaUml.pdf). p.17. Data de acesso: 19/03/2021.


> [Diagrama de caso de uso UML: O que é, como fazer e exemplos](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml). Data de Acesso 19/03/2021

## Versionamento

| Autor(es)     | Data       | Titulo     | Versão     |
| :--------:| :--------: | :--------: | :--------: |
| Hugo Bezerra, Kleidson Alves, <br>Lucas Gabriel | 19/03/2021     | Criação do Documento | 1.0 
| Gabriel Batalha, Kleidson Alves, <br>Lucas Rodrigues | 20/03/2021     | Adicionado Casos de Uso| 1.1 |
| Hugo Bezerra, Lucas Gabriel | 20/03/2021     | Revisão| 1.2 |
| Hugo Bezerra, Lucas Gabriel | 20/03/2021     | Adicionando imagens| 1.3 |
