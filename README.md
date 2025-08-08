# 🎫 TicketFlow

O **TicketFlow** é um sistema simples e eficiente para venda de ingressos online, com assentos numerados e QR Code para acesso rápido ao evento.  
O objetivo é oferecer uma experiência intuitiva para o usuário e um painel de gestão prático para organizadores.


## 📌 Objetivo

Facilitar a compra e o gerenciamento de ingressos, reduzindo filas e erros no controle de entrada.  
O projeto também serve como estudo de:
- Organização de repositório e documentação
- Boas práticas de README
- Estruturação de funcionalidades de um sistema real



## 🛠 Tecnologias Utilizadas

Mesmo sendo um projeto fictício, a arquitetura foi pensada para refletir tecnologias usadas no mercado:

- **Frontend:** HTML, CSS, JavaScript (React opcional)
- **Backend:** Node.js + Express
- **Banco de Dados:** MongoDB
- **Autenticação:** JWT (JSON Web Token)
- **Outros recursos:**
  - Geração de QR Codes (biblioteca `qrcode`)
  - Integração fictícia de pagamento (ex: Stripe)
 
    
## ⚙️ Funcionalidades

- **Compra de ingressos:**
  - Escolha do evento
  - Seleção de assentos no mapa
  - Pagamento online
- **Controle de assentos:**
  - Bloqueio automático de assentos já vendidos
  - Exibição visual no mapa
- **QR Code para entrada:**
  - Geração de QR Code único por ingresso
  - Validação no momento da entrada
- **Painel do organizador:**
  - Cadastro e edição de eventos
  - Relatórios de vendas
  - Controle de lotação

    
## 💡 Melhorias Futuras

Integração real com API de pagamento

Suporte para múltiplos idiomas

Notificações via e-mail e SMS

Aplicativo mobile nativo (React Native ou Flutter)

Dashboard com gráficos em tempo real




