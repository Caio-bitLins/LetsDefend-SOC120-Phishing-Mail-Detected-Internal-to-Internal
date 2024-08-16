![image](https://github.com/user-attachments/assets/e1af8764-a40b-417f-b4e9-b523d8d0898b)

## Let's Defend
>LetsDefend ajuda você a construir uma carreira na equipe azul com experiência prática, investigando ataques cibernéticos reais dentro de um SOC simulado.

## SOC120 - Phishing Mail Detected - Internal to Internal
![Captura de Tela 2024-08-16 às 11 42 10](https://github.com/user-attachments/assets/0c1a57ae-6fa6-47c3-8f37-564e04a4ffce)

# Primeiro Passo 💻
Bom, esse alerta como próprio nome já diz é um phishing. Então primeira coisa a se fazer é checar as informações que estão presente no e-mail. 
E as informações que encontrei foram essas:

- Alarme acionado como gravidade **média** às 04h24 AM do dia 07/02/2021
- O endereço IP SMTP do usúario que enviou o e-mail é observado como **172.16.20.3**
- O e-mail que gerou tudo foi **john@letsdefend.io** e o e-mail que foi recebido foi **susie@letsdefend.io**
- Informação do e-mail **"Hi Susie, Can we arrange a meeting today if you are available?"**

![Captura de Tela 2024-08-16 às 11 58 41](https://github.com/user-attachments/assets/95f7400d-57a2-4786-841c-390f9374dd43)

# Segundo Passo 🔎
Como nesse e-mail específico não há anexos ou urls de sites. Não tem como esse caso ser um phishing. Terminando de analisar vou criar o playbook do caso.

![Captura de Tela 2024-08-16 às 12 15 39](https://github.com/user-attachments/assets/1bc1b492-61a7-4028-a749-597dae3cd6be)``

![Captura de Tela 2024-08-16 às 12 16 21](https://github.com/user-attachments/assets/2f7403e6-e27f-4060-aedb-ef5df795c394)

![Captura de Tela 2024-08-16 às 12 21 05](https://github.com/user-attachments/assets/9a9bd1bb-b6d5-4080-a241-64db3a211ad1)

**Como já disse antes, esse e-mail não contém nenhum tipo de URL de site ou anexo então a resposta seria NO**

![Captura de Tela 2024-08-16 às 12 26 06](https://github.com/user-attachments/assets/cfa9201d-a971-4e49-bf37-303a1b0b4c98)

![Captura de Tela 2024-08-16 às 12 27 11](https://github.com/user-attachments/assets/8f4faa35-d620-4356-80d6-6373ed2cdeba)

![Captura de Tela 2024-08-16 às 12 28 48](https://github.com/user-attachments/assets/c3e4b9df-061d-4d7e-9544-9203160cd7f3)

![Captura de Tela 2024-08-16 às 12 29 26](https://github.com/user-attachments/assets/39f1fec3-1c99-460e-b4fa-443f4822b21d)


# Obrigado por ler até aqui! <3
<img src="https://media.tenor.com/qVKlQMB2DpsAAAAM/hacker-hacking.gif" width="230"></h2>





