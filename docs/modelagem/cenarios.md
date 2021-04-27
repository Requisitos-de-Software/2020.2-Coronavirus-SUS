# Cenários 

## Definição

<div style="text-indent: 40px; text-align: justify "/>
É uma estratégia entendida como a criação de situações específicas para determinar como o produto de software deve reagir em cada uma delas. A partir disso é possível elicitar a parte comportamental do software, sua dinâmica ou seu fluxo.
</div>

### Utilização

<div style="text-indent: 40px; text-align: justify "/>
A equipe decidiu utilizar essa técnica, pois permite um fácil entendimento do requisito, o que pode ser utilizado na etapa de desenvolvimento e na etapa de pós-rastreabilidade.
    
</div>

<br>

### Resultados

### Cenário 01
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** | *Compartilhar teste positivo*|
|**Objetivo**| *O usuário deve ser capaz de compartilhar um teste positivo*|
|**Contexto**|*O usuário fez o teste para COVID-19 e recebeu resultado positivo* |
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Um Dispositivo com acesso à Internet<br>Dispositivo com Coronavírus SUS instalado*<br>*Token gerado pelo site Valida Coronavírus-SUS*|
|**Exceção**|*Sem acesso à Internet*<br>O usuário não possui o token|
|**Episódios**|*1- Usuário entra no aplicativo do Coronavírus SUS <br>2- O usuário clica no botão "compartilhar teste positivo"<br>3- O usuário digita o código gerado pelo site Valida Coronavírus-SUS<br>4- O usuário seleciona a opção "continuar"*|


### Cenário 02
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** | *Ler notícia*|
|**Objetivo**| *O usuário deve poder acessar as notícias e lê-las*|
|**Contexto**| *Não precisa de um contexto específico, o usuário só precisa querer se informar* |
|**Atores**|*Cidadão brasileiro, Ministério da saúde*|
|**Recursos**|*Dispositivo com acesso à Internet<br>Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*Sem acesso à Internet*|
|**Episódios**|*1- Usuário entra no aplicativo do Coronavírus SUS <br/>2- Usuário navega até a aba de notícias <br/>3- Usuário clica na notícia que deseja ler <br/>4- Usuário é encaminhado para a fonte da notícia, o twitter do Ministério da saúde*|

### Cenário 03
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** | *Habilitar notificação de possível exposição*|
|**Objetivo**| *O usuário deve poder habilitar notificações de possíveis exposições ao vírus*|
|**Contexto**| *O usuário deseja ser notificado caso entre em contato com o vírus*|
|**Atores**| *Cidadão brasileiro*|
|**Recursos**|*Dispositivo com Bluetooth<br>Dispositivo com Coronavírus SUS instalado<br> Aplicativo com permissão para notificar*|
|**Exceção**|*O usuário não está com o Bluetooth do dispositivo ativado <br> As notificações do dispositivo estão desativadas*|
|**Episódios**|*1- O usuário acessa o sistema <br /> 2- O usuário clica no botão "habilitar" para habilitar a notificação de exposição* <br /> |

### Cenário 04
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Mudar idioma*|
|**Objetivo**|*O usuário deve poder alterar o idioma de apresentação do aplicativo*|
|**Contexto**|*Não há contexto específico*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*Sem exceções*|
|**Episódios**|*1- O usuário acessa o aplicativo do Coronavírus SUS<br/>2- O usuário seleciona a lista de idiomas<br/>3- O usuário seleciona a opção de idioma desejado*|

### Cenário 05
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Ler informativos sobre a COVID-19*|
|**Objetivo**|*O usuário deve poder acessar informações sobre o vírus da COVID-19*|
|**Contexto**|*O usuário quer entender mais sobre a COVID-19*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*Sem exceções*|
|**Episódios**|*1- O usuário acessa o aplicativo do Coronavírus SUS<br/>2- O usuário seleciona a aba de dicas<br/> 3- O usuário seleciona um tópico*|


### Cenário 06
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Visualizar lista de alertas*|
|**Objetivo**|*O usuário deve poder acessar os alertas*|
|**Contexto**|*O usuário recebeu algum alerta <br> O usuário deseja visualizar quais alertas ele recebeu*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*O usuário não recebeu nenhum alerta*|
|**Episódios**|*1- O usuário entra no aplicativo do Coronavírus SUS<br/>2- O usuário seleciona a aba de alertas*|

### Cenário 07
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Visualizar mapa de exposição*|
|**Objetivo**|*O usuário deve poder visualizar a concentração de casos da COVID-19 no território brasileiro*|
|**Contexto**|*O usuário deseja informar-se sobre a exposição de determinada área*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Acesso à Internet<br>Dispositivo com GPS<br>Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*Sem acesso à Internet*|
|**Episódios**|*1- O usuário entra no aplicativo do Coronavírus SUS<br>2- O usuário seleciona a aba mapa<br>3- O usuário clica na opção "Área de exposição"*|

### Cenário 08
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Visualizar estatísticas*|
|**Objetivo**|*O usuário deve poder visualizar estatísticas sobre a COVID-19*|
|**Contexto**|*O usuário deseja se informar sobre as estatísticas atualizadas sobre o vírus COVID-19*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Acesso à Internet<br>Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*Sem acesso à Internet*|
|**Episódios**|*1- O usuário entra no aplicativo do Coronavírus SUS<br>2- O usuário acessa a aba de notícias<br>3- O usuário acessa a opção "Estatísticas"*|

### Cenário 09
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Compartilhar notícias*|
|**Objetivo**|*O usuário deve poder compartilhar notícias publicadas pelo Ministério da Saúde diretamente do sistema*|
|**Contexto**|*O usuário deseja compartilhar notícias nas redes sociais*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Acesso à Internet<br>Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*Sem acesso à Internet*|
|**Episódios**|*1- O usuário entra no aplicativo do Coronavírus SUS<br>2- O usuário acessa a aba de notícias<br>3- O usuário visualiza as notícias<br>4- O usuário seleciona o ícone de compartilhamento da notícia<br>5- O usuário seleciona qual o meio pelo qual deseja compartilhar*|

### Cenário 10
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Verificar previsão de disponibilidade de vacina*|
|**Objetivo**|*O usuário deve poder descobrir quando é estimado que ele tenha direito a se vacinar*|
|**Contexto**|*O usuário deseja saber uma previsão de quando se vacinar*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Informações do usuário<br>Dispositivo com acesso à Internet<br>Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*Sem acesso à Internet*|
|**Episódios**|*1- O usuário entra no aplicativo do Coronavírus SUS<br/> 2- O usuário acessa a aba de informações<br>3- O usuário acessa o tópico sobre vacina<br>4- O usuário acessa a opção de disponibilidade de vacina<br>5- O usuário informa alguns dados e solicita a previsão*|

### Cenário 11
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Visualizar mapa de unidades de saúde*|
|**Objetivo**|*O usuário deve poder visualizar um mapa que indica a localização das unidades de saúde mais próximas*|
|**Contexto**|*O usuário deseja informar-se sobre a localidade das unidades de saúde em determinada área*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Dispositivo com GPS<br>Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*O GPS do dispositivo estar desativado*|
|**Episódios**|*1- O usuário entra no aplicativo do Coronavírus SUS<br>2- O usuário seleciona a aba mapa<br>3- O usuário seleciona a opção de "Unidades de Saúde"*|


### Cenário 12
| <div style = "font-size:25px"> Elemento </div> | <div style = "font-size:25px"> Resposta </div> |
| :--------: | :-------|
|**Título** |*Relatar estado de saúde*|
|**Objetivo**|*O usuário deve poder relatar o seu estado de saúde, verificando se os sintomas são compatíveis com os da COVID-19*|
|**Contexto**|*O usuário deseja analisar se seu estado de saúde se enquadra nos sintomas da COVID-19*|
|**Atores**|*Cidadão brasileiro*|
|**Recursos**|*Acesso à Internet<br>Dispositivo com Coronavírus SUS instalado*|
|**Exceção**|*Sem acesso à Internet*|
|**Episódios**|*1- O usuário acessa o aplicativo do Coronavírus SUS<br>2- O usuário relata seu estado de saúde como "mal"<br>3- O usuário responde a um questionário sobre seu estado de saúde <br>4- O sistema informa se o estado do usuário se enquadra nos sintomas da COVID-19*|

## Referências Bibliográficas

>[Uso de cenários para especificação de requisitos de qualidade e avaliação de arquitetura](https://www.devmedia.com.br/uso-de-cenarios-para-especificacao-de-requisitos-de-qualidade-e-avaliacao-de-arquitetura/22528). Data de acesso: 16/03/2021. 

## Versionamento

| Autor     | Data       | Título     | Versão     |
| :--------:| :--------: | :--------: | :--------: |
| Todos os integrantes   | 16/03/2021 | Criação do Documento | 1.0 |
| Hugo Bezerra   | 19/03/2021 | Revisão | 1.1 |
| Hugo Bezerra, Lucas Gabriel   | 19/03/2021 | Refatoração da definição e adicionando referências bibliográficas | 1.1 |
| Kleidson Alves, Lucas Gabriel, Lucas Rodrigues   | 27/04/2021 | Refatoração do documento | 1.2 |
