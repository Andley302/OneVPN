# One VPN

Este é um aplicativo desenvolvido em React Native, contendo códigos Java, incluindo a implementação do OpenVPN.

## Funcionamento

### Tela Inicial

O aplicativo apresenta uma tela inicial botões que abrirão dois modais:

1. **Servidores**: Exibe uma lista de servidores disponíveis para conexão.
2. **Modos de Conexão**: Permite a personalização dos modos de conexão. Os dados destas listas são provenientes de uma API web em PHP. O painel de gerenciamento dessa API inclui servidores, modos de conexão e IDs de dispositivos para usuários VIP.

### Iniciar Conexão

Ao pressionar o botão "Iniciar", a conexão é estabelecida, redirecionando para a tela de registro de conexão. Nessa tela, são exibidas informações detalhadas sobre a conexão.

### Tela VIP

Na tela VIP, o usuário encontra informações sobre o ID do dispositivo. O acesso VIP é concedido por meio do ID do dispositivo, e para adquiri-lo, o usuário é redirecionado para nosso site externo de API de pagamentos (Mercado Pago e Gerencia Net). Após o pagamento, o acesso é liberado, e um comprovante é enviado por e-mail.

### Configurações

A próxima tela apresenta configurações diversas, como DNS, idiomas, entre outros.

## Nota

Este é um aplicativo de código fechado. Para suporte ou questões relacionadas ao uso, entre em contato conosco através do e-mail de suporte.

---

**Observação:** Este README é uma orientação geral e você pode personalizá-lo conforme necessário para fornecer informações mais específicas sobre o seu aplicativo. Certifique-se de adaptar os detalhes de contato e outras informações conforme apropriado.
