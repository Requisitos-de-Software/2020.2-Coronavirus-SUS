# Especificação Suplementar

## Definição
<div style="text-indent: 40px; text-align: justify"/>
A Especificação Suplementar trata-se de um documento em linguagem natural, que visa explicitar os detalhes dos requisitos não funcionais, de modo que possam seguir para as demais fases do desenvolvimento.(REINEHR, Sheila 2020. Engenharia de Requisitos)  
</div>

### Utilização
<div style="text-indent: 40px; text-align: justify"/>

A partir dos requisitos não funcionais levantados, a equipe definiu, de maneira consensual, quais as classificações FURPS+ cada um se identificava, dessa forma foram geradas as tabelas com descrições plausíveis a cada requisito não funcional.

A especificação Suplementar foi vista pela equipe como a melhor forma de modelar, de maneira tradicional, os requisitos não funcionais, visto as descrições feitas dentro do levantamento dos requisitos e a proximidade com a classificação FURPS+ utilizada na Especificação Suplementar.
    
</div>

## Resultados

### Usabilidade

<div style="text-indent: 20px; text-align: justify"> 
Reúne os requisitos que envolvem a interação do usuário com o sistema. Indicando o tempo necessário para que o usuário consiga ser produtivo na utilização do sistema.
</div>
<br>

| Requisito | Descrição |
| :---------: | :----: |
|RNF17| O usuário deve poder compartilhar teste positivo com no máximo 3 cliques|
|RNF18|O usuário deve ter fácil acesso às dicas e notícias|
|RNF19|O sistema deve conter outros idiomas guardados|



### Confiabilidade 

<div style="text-indent: 20px; text-align: justify">
Reúne os requisitos de confiabilidade do sistema, em relação a segurança dos dados do usuário.
</div>
<br>

|  Requisito  | Descrição |
|:-----------:|:---------:|
|RNF02|O sistema deve buscar atualizações de informações a partir do site do Ministério da Saúde|
|RNF05|As notícias devem ser obtidas através do twitter dos órgãos competentes, Ministério da Saúde e Secretarias de Saúde|
|RNF07|Não coleta dados de geolocalização|
|RNF08|O sistema não deve guardar nenhum dado identificador do usuário|
|RNF09|O sistema deve excluir os dados no dia 31 de dezembro|
|RNF10|O sistema não pode determinar a identidade do usuário ou das pessoas com quem o usuário entrou em contato|
|RNF16|Os dados gravados no celular e as conexões com o servidor que os receberá são protegidos por criptografia|




### Desempenho

<div style="text-indent: 20px; text-align: justify"> 
Reúne os requisitos que envolvem o tempo de resposta na execução das funcionalidade do sistema. Também envolve o uso de recursos, tais como memória, espaço em disco e comunicação.
</div>
<br>

| Requisito | Descrição |
| :---------: | :----: |
|RNF01|O sistema deve atualizar as notícias a cada dia|
|RNF03|O sistema deve atualizar as estatísticas diariamente|
|RNF04|O sistema deve atualizar os informativos a cada trimestre|
|RNF12|O sistema deve emitir uma notificação ao usuário que foi exposto no período de um dia|


### Suportabilidade
<div style="text-indent: 20px; text-align: justify"> 
Reúne os requisitos que envolvem aspectos limitantes aos quais o sistema deve suportar, como versão.
</div>
<br>

| Requisito | Descrição |
| :---------: | :----: |
|RNF06|O sistema deve acessar a posição atual do usuário|
|RNF11|Para concretizar um contato, o usuário deve ter ficado a menos de 2 metros de um usuário contaminado durante um período mínimo de 5 minutos|
|RNF14|O sistema será compatível apenas em Iphone versão 13.5 ou superior|
|RNF15|O sistema será compatível apenas em Android 5.0 ou superior|
|RNF13|O sistema deverá trocar chaves anônimas por Bluetooth com outros usuários|


## Referências Bibliográficas
> REINEHR, Sheila. 2020. ENGENHARIA DE REQUISITOS. 

> [Introdução a Requisitos de Software](https://www.devmedia.com.br/introducao-a-requisitos-de-software/29580). Data de acesso: 19/03/2021 

## Versionamento

| Autor(es)     | Data       | Título     | Versão     |
| :--------:| :--------: | :--------: | :--------: |
| Lucas Gabriel, Kleidson Alves,<br>Lucas Rodrigues, Gabriel Batalha | 19/03/2021     | Criação do Documento | 1.0 
| Hugo Bezerra | 19/03/2021     | Revisão | 1.1 
| Gabriel Batalha, Hugo Bezerra  | 27/04/2021  |  Refatoração |1.2 
