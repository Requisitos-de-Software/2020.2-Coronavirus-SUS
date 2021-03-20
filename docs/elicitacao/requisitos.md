# Requisitos

<div style="text-indent: 40px; text-align: justify"/>
A lista de requisitos abaixo é proveniente das técnicas de elicitação utilizadas pela equipe. Todos os números de requisitos presentes neste documento são os números utilizados para citação dos requisitos em outros documentos, exceto aqueles que fazem parte das diferentes técnicas de elicitação de requisitos.
</div>

## Não-funcionais
| Numéro | Nome | Descrição | Técnica |
| :--------: | :--------: | :--------: | :-------:
| RNF01 | Atualização de notícias | O sistema deve atualizar as notícias a cada dia| Brainstorming
|RFN02 |Obtenção das informações| O sistema deve buscar atualizações de informações a partir do site do Ministério da Saúde| Análise de documentos
|RNF03|Atualização de estatísticas | O sistema deve atualizar as estatísticas diariamente|Brainstorming
|RNF04|Atualização de informativos| O sistema não deve atualizar as notícias em tempo real |Brainstorming
|RNF05| Carregar notícias do twitter| As notícias devem ser obtidas através do twitter dos órgãos competentes, Ministério da Saúde e Secretarias de Saúde|Análise de documentos
|RNF06|Geolocalização|O sistema deve acessar a posição atual do usuário|Análise de documentos
RNF07 | Dados de geolocalização|Não coleta dado de geolocalização |Análise de documentos
RNF08 |Dados de usuário|O sistema não deve guardar nenhum dado identificador do usuário|Introspecção
RNF09 |Exclusão dos dados|O sistema deve excluir os dados no dia 31 de dezembro|Análise de documentos
RNF10 |Não determinar identidade|O sistema não pode determinar a identidade do usuário ou das pessoas com quem o usuário entrou em contato|Análise de documentos
RNF11 |Contato com a COVID-19|Para concretizar um contato, o usuário deve ter ficado a menos de 2 metros de um usuário contaminado durante um período mínimo de 5 minutos |Análise de documentos
RNF12 |Notificação de usuário contaminado|O sistema deve emitir uma notificação ao usuário que foi exposto no período de um dia|Brainstorming
RNF13 | Troca de chaves por Bluetooth| O sistema deverá trocar chaves anônimas por Bluetooth com outros usuários|Brainstorming
RNF14 |Contact-tracing Iphone| O sistema será compatível apenas em Iphone versão 13.5 ou superior|Análise de documentos
RNF15 |Contact-tracing Android|O sistema será compatível apenas em Android 5.0 ou superior|Análise de documentos
RNF16 |Criptografia|Os dados gravados no celular e as conexões com o servidor que os receberá são protegidos por criptografia|Análise de documentos
RNF17 |Compartilhamento simples|O usuário deve poder compartilhar teste positivo com no máximo 3 cliques
RNF18 |Fácil acesso|O usuário deve ter fácil acesso às dicas e notícias
RNF19 |Internacionalização|O sistema deve conter outros idiomas guardados

<br>

## Funcionais

| Numéro | Nome | Descrição | Técnica |
| :--------: | :--------: | :--------: | :-------:
RF01|Mapa de unidades de saúde |O sistema deverá mostrar unidades de saúde próximas a geolocalização do usuário| Introspecção
RF02 |Informativos sobre a COVID-19|O sistema deverá mostrar informações sobre o vírus da COVID-19| Análise de documentos
RF03 |Notícias sobre a COVID-19|O sistema deverá mostrar as notícias relacionadas ao vírus da COVID-19| Análise de documentos
RF04 |Análise de estado de saúde|O sistema deverá informar com base nas respostas do usuário sobre o estado de saúde qual a possibilidade dele estar infectado e orientá-lo sobre o que fazer| Análise de documentos
RF05 |Notificar contato com infectado|O usuário deve ser notificado se houver contato entre ele e um usuário infectado| Introspecção
RF06 |Validar código |O sistema deve ser capaz de validar o TOKEN disponibilizado pelo site Valida Coronavírus - SUS| Análise de documentos
RF07 |Relatar estado |O usuário deve poder responder objetivamente sobre o seu atual estado de saúde| Análise de documentos
RF08 |Habilitar/Desabilitar notificação de exposição|O usuário poderá habilitar e desabilitar as notificações de exposição ao coronavírus | Análise de documentos
RF09 |Compartilhar teste positivo|O usuário deve poder compartilhar o teste positivo de COVID-19| Brainstorming
RF10 |Avisos sobre Fake News|O sistema deverá ter uma área informativa sobre Fake News| Brainstorming
RF11 |Mapa de exposição|O usuário poderá acessar um mapa que mostra a mancha de exposição das regiões próximas| Introspecção
RF12 |Notificação de área de risco|O usuário deve receber uma notificação quando estiver em uma área em que o número de casos registrados é elevado| Introspecção
RF13 |Compartilhar notícias|O usuário deve poder compartilhar notícias diretamente do sistema| Introspecção
RF14 |Apresentar notícias locais|O usuário deve poder acessar uma página com as notícias referentes à sua região|Brainstorming
RF15 |Apresentar estatísticas |O usuário deve poder ver dados relacionados à COVID-19 - número de infectados registrados, de mortos, de recuperados e de vacinados|Brainstorming
RF16 |Previsão de disponibilidade de vacina|O usuário preenche um formulário, com alguns dados que não serão salvos, e o sistema retorna para ele qual a previsão de vacinação para sua classificação em sua região|Brainstorming
RF17|Apresentar alerta|O usuário deve poder acessar uma página com as lista de alertas que o sistema lhe notificou|Brainstorming
RF18|Alterar idioma|O usuário deve poder alterar o idioma do sistema


## Versionamento


| Autor | Data | Titulo | Versão |
| :--------: | :--------: | :--------: | :-----:
| Hugo Bezerra, Kleidson Alves    | 16/03/2021     | Criação do Documento| 1.0
| Hugo Bezerra, Lucas Gabriel    | 20/03/2021     | Revisão e adição de descrição| 1.1
