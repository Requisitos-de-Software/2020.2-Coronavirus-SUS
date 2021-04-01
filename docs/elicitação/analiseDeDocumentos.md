# Análise de documentos

## Definição
<div style="text-indent: 40px; text-align: justify">
Análise de documentos trata de analisar documentos já existentes para buscar por potenciais requisitos. Os documentos mais úteis são especificação de requisitos, processos do negócios, coleções lessons-learned e manual do usuário de aplicações similares ou existentes. 
</div>

### Utilização
<div style="text-indent: 40px; text-align: justify">
Por se tratar de um tema que está em alta, muitas matérias jornalisticas são feitas com dados e informações, sobre o vírus e temas relacionados a ele. Isso gera muitos documentos passíveis de extração de informação, o que a equipe julgou como muito útil para a elicitação de documentos.
</div>

## Resultados

### Documento Analisado: [App Store](https://apps.apple.com/br/app/coronavírus-sus/id1408008382)

|Número|Nome|Descrição|
|:--:|:--:|:--:|
RNF01|Recurso contact-tracing| O sistema será compatível apenas em Iphone versão 13.5 ou superior| 
RNF02| Obtenção de informações do twitter|O sistema deve buscar atualizações de notícias a partir do twitter do Ministério da Saúde
RF01|Mapa de unidades de saúde|O sistema deverá mostrar unidades de saúde próximas a geolocalização do usuário
RF02|Informativos sobre a COVID-19|O sistema deverá mostrar informações sobre o vírus da COVID-19
RF03|Notícias sobre a COVID-19|O sistema deverá mostrar as notícias relacionadas ao vírus da COVID-19
RF04| Testar possível infecção|O usuário deve poder verificar se os seus sintomas são compatíveis com os da COVID-19


### Documento Analisado: [Play Store](https://play.google.com/store/apps/details?id=br.gov.datasus.guardioes)
|Número|Nome|Descrição|
|:--:|:--:|:--:|
RNF02|Obtenção de informações do twitter|O sistema deve buscar atualizações de notícias a partir do twitter do Ministério da Saúde
RNF03|Recurso contact-tracing|O sistema será compatível apenas em android 5.0 ou superior|
RF01|Mapa de unidades de saúde |O sistema deverá mostrar unidades de saúde próximas à geolocalização do usuário
RF02|Informativos sobre a COVID-19|O sistema deverá mostrar informações sobre o vírus da COVID-19
RF03|Notícias sobre a COVID-19|O sistema deverá mostrar as notícias relacionadas ao vírus da COVID-19
RF04|Testar possível infecção|O usuário deve poder verificar se os seus sintomas são compatíveis com os da COVID-19

### Documento Analisado: [Youtube Ministério da saúde](https://www.youtube.com/watch?v=PjG_imUHTSI&ab_channel=MinistériodaSaúde)

|Número|Nome|Descrição|
|:--:|:--:|:--:|
|RNF04|Contato com a COVID-19|O usuário deve ter ficado a menos de 2 metros, durante no mínimo 5 minutos, de um usuário que testou positivo para concretizar o contato|
|RNF05|Enviar notificação|O sistema deve enviar uma notificação ao usuário no mesmo dia|
|RNF06|Dados do usuário|O sistema não deve armazenar nenhum dado que identifique o usuário|
|RF05|Notificar contato com infectado|O usuário deve ser notificado se houver contato entre ele e um usuário infectado|
|RF06|Validar código|O sistema deve ser capaz de validar o TOKEN disponibilizado pelo site Valida Coronavírus - SUS|


### Documento Analisado: [App Coronavírus SUS - uol](https://www.uol.com.br/tilt/noticias/redacao/2020/07/31/app-coronavirus---sus-adiciona-rastreamento-de-contatos-entenda.htm)

|Número|Nome|Descrição|
|:--:|:--:|:--:|
|RNF06|Dados do usuário|O sistema não deve armazenar nenhum dado que identifique o usuário
|RNF07|Não determinar identidade|O sistema não pode determinar sua identidade ou das pessoas com quem o usuário entrou em contato
|RNF08|Exclusão dos dados|O sistema deve excluir os dados no dia 31 de dezembro
|RNF09|Criptografia|Os dados gravados no celular e as conexões com o servidor que os receberá são protegidos por criptografia
|RNF10|Dados de geolocalização|Não coleta dado de geolocalização 
|RNF11|Troca de chaves por Bluetooth|O sistema deverá trocar chaves anônimas por Bluetooth com outros usuários

### Documento Analisado: [Canaltech](https://canaltech.com.br/apps/como-usar-app-coronavirus-sus/)

|Número|Nome|Descrição|
|:--:|:--:|:--:|
|RF01|Mapa de unidades de saúde |O sistema deverá mostrar um mapa com as unidades de saúde mais próximas em destaque|
|RF02|Informativos sobre a COVID-19|O sistema deverá mostrar informações sobre o vírus da COVID-19|
|RF03|Notícias sobre a COVID-19|O sistema deverá mostrar as notícias relacionadas ao vírus da COVID-19|
|RF05|Notificar contato com infectado|O usuário deve ser notificado se houver contato entre ele e um usuário infectado|
|RF07|Relatar estado|O usuário deve poder relatar o seu estado de saúde atual|
|RF08|Análise de estado de saúde|O sistema deverá informar com base nas respostas do usuário sobre o estado de saúde qual a possibilidade dele estar infectado e orientá-lo sobre o que fazer|
|RF09|Habilitar/Desabilitar notificação de exposição|O usuário poderá habilitar e desabilitar as notificação de exposição|
|RF10|Compartilhar teste|O usuário deve poder compartilhar o teste positivo de COVID-19|

### Documento Analisado: [Amplifica Digital](https://amplificadigital.com.br/blog/sus/)

|Número|Nome|Descrição|
|:--:|:--:|:--:|
|RNF02|Obtenção de informações do twitter|O sistema deve buscar atualizações de notícias a partir do twitter do Ministério da Saúde|
|RNF12|Geolocalização|O sistema deverá utilizar a geolocalização do usuário para encontrar os postos de saúde mais próximos|
|RNF13|Atualização de notícias|O sistema não deve atualizar as notícias em tempo real|
|RF01|Mapa de unidades de saúde|O sistema deverá mostrar um mapa com as unidades de saúde mais próximas em destaque.|
|RF02|Informativos sobre a COVID-19|O sistema deverá mostrar informações sobre o vírus da COVID-19|
|RF07|Relatar estado|O usuário deve poder relatar o seu estado de saúde atual|
|RF08|Análise de estado de saúde|O sistema deverá informar com base nas respostas do usuário sobre o estado de saúde qual a possibilidade dele estar infectado e orientá-lo sobre o que fazer|
|RF11|Avisos sobre Fake News|O sistema deverá ter uma área informativa sobre Fake News|


## Referências Bibliograficas 

> REINEHR,Sheila.2020. ENGENHARIA DE REQUISITOS. 

> [App Store Coronavírus - SU‪S‬](https://apps.apple.com/br/app/coronav%C3%ADrus-sus/id1408008382). Data de acesso: 04/03/2021

> [Play Store Coronavírus - SU‪S‬](https://play.google.com/store/apps/details?id=br.gov.datasus.guardioes). Data de acesso: 04/03/2021

> Aplicativo Coronavírus-SUS vai alertar contatos próximos de pacientes com Covid-19. Disponível em: [https://www.youtube.com/watch?](https://www.youtube.com/watch?v=PjG_imUHTSI&ab_channel=Minist%C3%A9riodaSa%C3%BAde). Data de acesso: 04/03/2021

> [Coronavírus - SUS](https://www.gov.br/pt-br/apps/coronavirus-sus). Data de acesso: 04/03/2021

> [App Coronavírus SUS agora vai avisar quando usuário foi exposto; entenda](https://www.uol.com.br/tilt/noticias/redacao/2020/07/31/app-coronavirus---sus-adiciona-rastreamento-de-contatos-entenda.htm). Data de acesso: 04/03/2021

> [Como usar o app do Coronavírus - SUS](https://canaltech.com.br/apps/como-usar-app-coronavirus-sus/). Data de acesso: 04/03/2021

## Versionamento

| Autor | Data | Título | Versão |
| :--------:| :--------: | :--------: | :--------: |
| Gabriel Batalha, Lucas Gabriel,<br>Kleidson Alves | 04/03/2021      | Criação do Documento | 1.0 |
| Todos os integrantes | 09/03/2021     | Edição e revisão    | 1.1 |
| Lucas Gabriel | 11/03/2021     | Formatação de texto    | 1.2 |
| Lucas Gabriel | 20/03/2021     | Correção de referências bibliográficas   | 1.3 |
|Kleidson Alves| 01/04/2021| Padronização do documento| 1.4
