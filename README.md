💸 GastosWhatsApp

Robô de RPA (UiPath) que automatiza o controle de gastos pessoais através de um grupo de WhatsApp — sem precisar de planilhas manuais ou apps de terceiros.

📋 Sobre o projeto

A ideia é simples: você manda uma mensagem no seu grupo de WhatsApp toda vez que gasta algo, e o robô cuida do resto — lendo, organizando e (em breve) somando tudo automaticamente no fim do mês.

Este projeto foi criado como estudo prático de UiPath e RPA, com foco em automação de interface (UI Automation) em um cenário real e não convencional — já que o WhatsApp não oferece uma API pública simples para uso pessoal.

⚙️ Como funciona
O robô abre o WhatsApp Web automaticamente via navegador
Busca e abre o grupo de gastos configurado
Identifica as mensagens de gasto enviadas no formato:
   Gasto Categoria: Valor

Exemplo: Gasto Uber: 25,90 4. Captura e organiza essas informações 5. (Em desenvolvimento) Soma os valores do mês e envia um resumo de volta no grupo

🛠️ Tecnologias
UiPath Studio — desenvolvimento do fluxo de automação
UI Automation — interação com o WhatsApp Web via navegador (Chrome)
Regex — extração de valores e categorias das mensagens
Excel (planejado) — armazenamento estruturado dos gastos
🚧 Status atual

Projeto em desenvolvimento ativo. Já implementado:

 Abertura automática do WhatsApp Web
 Busca e abertura do grupo de gastos
 Localização das mensagens de gasto na conversa
 Extração dos valores e categorias (Regex)
 Armazenamento em planilha Excel
 Cálculo do total mensal
 Envio automático do resumo mensal no grupo
 Agendamento para execução automática (ex: todo dia 1º do mês)
⚠️ Observação importante

Este projeto utiliza automação de interface (UI Automation) sobre o WhatsApp Web, e não a API oficial do WhatsApp Business. Por isso, é indicado apenas para uso pessoal e fins de estudo, não estando em conformidade com os Termos de Serviço do WhatsApp para uso comercial ou em larga escala.

👤 Autor

Desenvolvido por Ricardo Martini como projeto de aprendizado em UiPath e automação de processos (RPA).
