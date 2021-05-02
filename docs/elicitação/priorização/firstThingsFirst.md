# First Things First

## Definição

<div style="text-indent: 40px; text-align: justify">
 O First Things First é uma técnica de priorização baseada na estimativa de  valor, custo e risco. Dessa forma, determina-se quais requisitos são os mais importantes, devendo ser implementados primeiro. 
</div>

### Utilização
<div style="text-indent: 40px; text-align: justify">
Em projetos de grande escala a definição da priorização dos requisitos precisa ser mais estruturada, visto que chegar a um denominador comum entre muitos stakeholders é uma tarefa difícil.

A equipe se reuniu para construir a tabela de priorização, atribuindo os valores, custos e riscos dos requisitos elicitados anteriormente. No entanto, era necessário a participação de outros interessados no sistema. Por isso, houve a participação de personas.

A equipe foi orientada pelos seguintes passos:

</div>

- Passo 1: Liste todos os requisitos que deseja priorizar  

- Passo 2: Estime o benefício relativo que cada funcionalidade fornece ao cliente ou ao negócio em uma escala de 1 a 9  

- Passo 3: Estime a penalidade que o negócio sofreria se a funcionalidade não for incluída  

- Passo 4: Preencha a coluna "Valor total". Ela é a soma do benefício relativo e a penalidade relativa  

- Passo 5: Estime o custo relativo de implementação de cada funcionalidade, em uma escala de 1(baixo) para 9(alto)  

- Passo 6: Estime o grau relativo de risco para cada requisito em uma escala de 1 a 9  

- Passo 7: Calcule a prioridade para cada funcionalidade.  Prioridade = valor% / ( custo% + risco% )  

- Passo 8: Ordene a lista de funcionalidades em ordem decrescente pela  ordem de prioridade  


## Priorização dos Requisitos
<div style="text-indent: 40px; text-align: justify">
Os requisitos presentes nesse documento podem ser encontrados na <a href="https://requisitos-de-software.github.io/2020.2-Coronavirus-SUS/elicitação/requisitos/">lista de requisitos</a>.

</div>


| Requisito  | Benefício Relativo | Penalidade Relativa | Valor Total | Valor(%) | Custo Relativo | Custo(%) | Risco Relativo | Risco(%) | Prioridade | 
| -------- | -------- | -------- | ------ | --------| -------- | -------|----- | ------| ------ |
| RF02 | 8 | 8 | 16 | 6,93% | 2 | 3,63% | 1 | 1,82%  |1,271|
| RF12 | 9 | 9 | 18 | 7,79% | 2 | 3,63% | 2 | 3,64%  |1,071|
| RF07 | 8 | 7 | 15 | 6,49% | 2 | 3,63% | 2 | 3,64%  |0,892|
| RF14 | 6 | 5 | 11 | 4,76% | 2 | 3,63% | 1 | 1,82%  |0,873|
| RF17 | 7 | 4 | 11 | 4,76% | 2 | 3,63% | 1 | 1,82%  |0,873|
| RF08 | 5 | 2 | 7  | 3,03% | 1 | 1,82% | 1 | 1,82%  |0,832|
| RF03 | 8 | 7 | 15 | 6,49% | 3 | 5,45% | 3 | 5,45%  |0,595|
| RF10 | 6 | 6 | 12 | 5,19% | 3 | 5,45% | 2 | 3,64%  |0,570|
| RF05 | 9 | 9 | 18 | 7,79% | 3 | 5,45% | 5 | 9,09%  |0,535|
| RF01 | 7 | 6 | 13 | 5,63% | 3 | 5,45% | 3 | 5,45%  |0,516|
| RF16 | 9 | 8 | 17 | 7,36% | 6 | 10,90%| 4 | 7,27%  |0,405|
| RF06 | 6 | 4 | 10 | 4,33% | 3 | 5,45% | 3 | 5,45%  |0,397|
| RF13 | 5 | 5 | 10 | 4,33% | 3 | 5,45% | 3 | 5,45%  |0,397|
| RF04 | 7 | 6 | 13 | 5,63% | 3 | 5,45% | 5 | 9,09%  |0,387|
| RF15 | 6 | 5 | 11 | 4,76% | 3 | 5,45% | 4 | 7,27%  |0,374|
| RF11 | 9 | 9 | 18 | 7,79% | 6 | 10,90%| 7 | 12,73% |0,329|
| RF09 | 6 | 7 | 13 | 5,63% | 4 | 7,27% | 6 | 10,91% |0,309|
| RF18 | 2 | 1 | 3  | 1,30% | 4 | 7,27% | 2 | 3,63%  |0,119|
| Total|123|108|231 | 100%  | 55| 100%  |55 | 100%   |  -  |


## Referências Bibliográficas

> WIEGERS, Karl. First Things First: Prioritizing Requirements. Pode ser acessado em: [https://www.processimpact.com/articles/prioritizing.pdf](https://www.processimpact.com/articles/prioritizing.pdf). Data de acesso: 27/04/2021

## Versionamento

| Autor(es)     | Data       | Título     | Versão     |
| :--------:| :--------: | :--------: | :--------: |
| Todos os integrantes | 29/04/2021     | Criação do Documento | 1.0 |