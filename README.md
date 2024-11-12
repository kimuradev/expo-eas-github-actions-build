### Arquivo de configuração para deploy automático utilizando Github Actions and Expo EAS

Baseado no video do [Rodrigo](https://github.com/orodrigogo/), ensinando em como fazer deploy automatico de uma aplicação mobile, utilizando `Github Actions` and `Expo EAS`, deixei disponivel o arquivo de `deploy.yml` apenas para copiar e colar.

O restante das configurações, basta seguir os detalhes no vídeo.

Video: https://www.youtube.com/watch?v=x5oJ7Egnm8g

----

### Dificuldades durante o processo.

1. Baixar o arquivo `JSON` com as credenciais (https://www.youtube.com/watch?v=rWcLDax-VmM) esse video me ajudou.
2. No momento de submissão do app na EAS, ocorreram dois problemas:
   - Google Play Android Developer API -> Precisei habilitar no Google Cloud
   - Após habilitar a API, tive um erro de permissão. Precisei adicionar o mesmo e-mail que cadastrei nas credenciais, dentro do Google Play Console na aba de `Users and permissions` com permissão de admin.
  
Depois disso, foi só correr pro abraço.
