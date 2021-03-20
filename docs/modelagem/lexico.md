# Léxico

## Definição
<div style="text-indent: 20px; text-align: justify"> 
Léxico ampliado a linguagem (Language extended Lexicon) é uma técnica para descrever os símbolos de uma linguagem com noção e impacto, classificados em objetos, verbos e estados.
</div>

### Utilização
<div style="text-indent: 20px; text-align: justify">

Baseado nos requisitos levantados, a equipe utilizou seus nomes e definições para buscar por termos e palavras que se encaixariam dentro da proposta de descrição do léxico.

A equipe gerou os léxicos por meio de uma reunião, onde foram debatidos os requisitos e quais itens precisariam de uma descrição dentro do léxico.

A nossa equipe utilizou o léxico para descrever de maneira mais clara termos importantes para os requisitos, sendo importante tanto para a equipe durante o processo de desenvolvimento do projeto quanto para possíveis análises no futuro.

Os resultados da reunião estão explicitados neste documento em formato de Léxico.

</div>

## Resultados

### Verbos

|||
| :--------: | :-------- | 
|**Nome**|*Compartilhar*|
|**Sinônimo**| Distribuir|
|**Noção**|O usuário, ao selecionar "compartilhar teste positivo", informa o código do teste positivo, que servirá de alerta para outras pessoas.|
|**Impacto**|O usuário pode compartilhar com outros o seu teste positivo|
|**Classificação**|Verbo|

|||
| :--------: | :-------- | 
|**Nome**|*Habilitar*|
|**Sinônimo**|Ativar|
|**Noção**|Tarefa realizada pelo usuário<br>Ocorre quando o usuário deseja ser notificado de possíveis exposições ao vírus|
|**Impacto**|O usuário recebe um código aleatório e anônimo|
|**Classificação**|Verbo|

|||
| :--------: | :-------- | 
|**Nome**|*Desabilitar*|
|**Sinônimo**|Desativar|
|**Noção**|Tarefa realizada pelo usuário<br>Ocorre quando o usuário não deseja ser notificado de possíveis exposições ao vírus|
|**Impacto**|O sistema para de notificar o usuário|
|**Classificação**|Verbo|

|||
| :--------: | :-------- | 
|**Nome**|*Analisar*|
|**Sinônimo**|Examinar|
|**Noção**|O sistema analisa dados de saúde enviados pelo usuário<br>O sistema analisa dados demográficos enviados pelo usuário|
|**Impacto**|O usuário recebe uma análise, feita pelo sistema, indicando uma possível infecção<br>O usuário recebe informações sobre vacinação para sua região baseada nos dados demográficos|
|**Classificação**|Verbo|

|||
| :--------: | :-------- | 
|**Nome**|*Traduzir*|
|**Sinônimo**|Alterar idioma|
|**Noção**|O usuário escolhe alterar o idioma dos textos do sistema<br>Ocorre quando o usuário altera o idioma de exibição|
|**Impacto**|As telas serão exibidas no idioma escolhido para o usuário|
|**Classificação**|Verbo|
<br>

### Objetos

|||
| :--------: | :-------- | 
|**Nome**|*Dica*|
|**Sinônimo**|Sugestão|
|**Noção**|Textos que podem ser lidos pelo usuário, cuja finalidade é transmitir conhecimento e fazer sugestões|
|**Impacto**|Usuário visualiza diversas informações|
|**Classificação**|Objeto|


|||
| :--------: | :-------- | 
|**Nome**|*Notícia*|
|**Sinônimo**|Informação|
|**Noção**|Informações divulgadas com a intenção de transmitir conhecimento ao leitor acerca de acontecimentos específicos|
|**Impacto**|Usuário visualiza notícias|
|**Classificação**|Objeto|


|||
| :--------: | :-------- | 
|**Nome**|*Alerta*|
|**Sinônimo**|Notificação|
|**Noção**|Informações para usuários, a fim de deixá-los cientes de potenciais perigos|
|**Impacto**|O usuário recebe uma notificação que o alerta de uma exposição|
|**Classificação**|Objeto|

|||
| :--------: | :-------- | 
|**Nome**|*Estatística*|
|**Sinônimo**|Recenseamento|
|**Noção**|Amostra de dados organizada geograficamente sobre o vírus visualmente representadas por meio de gráficos|
|**Impacto**|O usuário visualiza e se informa dos dados sobre o vírus|
|**Classificação**|Objeto|

|||
| :--------: | :-------- | 
|**Nome**|*Criptografia*|
|**Sinônimo**|Codificação|
|**Noção**|Codificação dos dados enviados ao sistema|
|**Impacto**|Os dados enviados ao sistema são criptografados|
|**Classificação**|Objeto|

|||
| :--------: | :-------- | 
|**Nome**|*Geolocalização*|
|**Sinônimo**|Localização na terra|
|**Noção**|Localização de uma pessoa/objeto no globo terrestre|
|**Impacto**|O usuário envia para o sistema sua localização a fim de receber notícias localizadas <br>O usuário envia para o sistema sua localização a fim de receber informações regionalizadas de unidades de saúde e de estatísticas de exposição|
|**Classificação**|Objeto|

|||
| :--------: | :-------- | 
|**Nome**|*Bluetooth*|
|**Sinônimo**|Comunicação sem fio|
|**Noção**|Meio de comunicação entre dispositivos sem fio |
|**Impacto**|O sistema compartilha a chave criptografada do usuário com outros usuários para detectar uma exposição ao vírus|
|**Classificação**|Objeto|

|||
| :--------: | :-------- | 
|**Nome**|*Fake News*|
|**Sinônimo**|Notícia Falsa|
|**Noção**|Uma notícia sobre a doença COVID-19 que não seja verdadeira|
|**Impacto**|O sistema avisará ao usuário sobre o tema para não disseminar informações erradas|
|**Classificação**|Objeto|
<br>

### Estados


|||
| :--------: | :-------- | 
|**Nome**|*Online*|
|**Sinônimo**|Conectado|
|**Noção**|Conectado com um serviço de Internet|
|**Impacto**|Permite as atualizações de notícias e dicas.<br>Permite o compartilhamento do teste positivo|
|**Classificação**|Estado|

|||
| :--------:| :-------- | 
|**Nome**|*Exposição*|
|**Sinônimo**|Exibição|
|**Noção**|Usuário entrou em contato com outro usuário que compartilhou teste positivo.<br>Usuário foi exposto ao vírus.|
|**Impacto**|O usuário é notificado sobre a exposição.<br>O usuário deve tomar medidas para uma possível infecção.|
|**Classificação**|Estado|

|||
| :--------: | :-------- | 
|**Nome**|*Contaminado*|
|**Sinônimo**|Infectado|
|**Noção**|Usuário que foi infectado pelo vírus e compartilhou a contaminação com o sistema|
|**Impacto**|O código do usuário é vinculado ao diagnóstico positivo e gera notificações para outros usuários, em caso de contato|
|**Classificação**|Estado|

|||
| :--------: | :-------- | 
|**Nome**|*Anônimo*|
|**Sinônimo**|Não identificável|
|**Noção**|Os usuários do sistema não podem ser identificados|
|**Impacto**|O sistema não guarda dados pessoais ou de geolocalização do usuário|
|**Classificação**|Estado|

## Referências Bibliográficas

> SAMPAIO, Julio César. FRANCO, Ana Paula.  [A Strategy for Conceptual Model Acquisition](http://www-di.inf.puc-rio.br/~julio/Slct-pub/lel.pdf). Departamento de Informática. Universidade Católica do Rio de Janeiro. p. 243-246. Data de acesso: 19/03/2021  


## Versionamento

| Autor(es)     | Data       | Titulo     | Versão     |
| :--------:| :--------: | :--------: | :--------: |
| Lucas Gabriel, Kleidson Alves,<br>Lucas Rodrigues, Gabriel Batalha | 19/03/2021     | Criação do Documento | 1.0 
| Hugo Bezerra | 19/03/2021     | Revisão | 1.1 
