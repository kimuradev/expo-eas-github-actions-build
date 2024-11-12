> pt-BR

### Arquivo de configuração para deploy automático utilizando Github Actions and Expo EAS

Baseado no video do [Rodrigo](https://github.com/orodrigogo/), ensinando em como fazer deploy automatico de uma aplicação mobile, utilizando `Github Actions` and `Expo EAS`, deixei disponivel o arquivo de `deploy.yml` apenas para copiar e colar.

O restante das configurações, basta seguir os detalhes no vídeo.

Video: https://www.youtube.com/watch?v=x5oJ7Egnm8g

### Dificuldades durante o processo.

1. Baixar o arquivo `JSON` com as credenciais (https://www.youtube.com/watch?v=rWcLDax-VmM) esse video me ajudou.
2. No momento de submissão do app na EAS, ocorreram dois problemas:
   - Google Play Android Developer API -> Precisei habilitar no Google Cloud
   - Após habilitar a API, tive um erro de permissão. Precisei adicionar o mesmo e-mail que cadastrei nas credenciais, dentro do Google Play Console na aba de `Users and permissions` com permissão de admin.
  
Depois disso, foi só correr pro abraço.

----

> en-US

### Configuration file for automatic deployment using GitHub Actions and Expo EAS

Based on [Rodrigo’s video](https://github.com/orodrigogo/) on setting up automatic deployment for a mobile app using `GitHub Actions` and `Expo EAS`, I’ve made the `deploy.yml` file available for easy copy-paste.

For the rest of the setup, just follow the details in the video.

Video: https://www.youtube.com/watch?v=x5oJ7Egnm8g

### Challenges during the process

1. Downloading the JSON file with credentials (https://www.youtube.com/watch?v=rWcLDax-VmM) – this video helped me.
2. During the app submission on EAS, I encountered two issues:
   - Google Play Android Developer API -> I had to enable it in Google Cloud.
   - After enabling the API, I got a permission error. I needed to add the same email registered in the credentials to the Google Play Console in the `Users and permissions` tab with admin permissions.

After that, everything went smoothly!
