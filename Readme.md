📋 Resolução do Prompt (Resultado Esperado da IA)
Se você executar esse prompt no n8n ou em uma IA de assistência, o fluxo proposto utilizará a seguinte arquitetura de nós:

Google Forms Trigger (ou Webhook Node):

Função: Capturar automaticamente os novos envios de formulário em tempo real.

If Node (Filtro / Validação):

Condição: Verificar se o campo email contém uma estrutura válida (ex: contendo @ e domínio) e não está vazio.

Ação: Se Falso, o fluxo encerra sem executar nenhuma ação posterior. Se Verdadeiro, prossegue para os próximos nós.

Google Sheets Node:

Operação: Append Row (Adicionar linha).

Função: Mapear as respostas recebidas do formulário para colunas específicas na planilha comercial (ex: Nome, E-mail, Telefone, Data de Cadastro).

Gmail Node:

Operação: Send Email.

Função: Enviar o e-mail de notificação/confirmação contendo as informações registradas.

🚀 Instruções para Submissão na DIO
Criar o arquivo: Copie o texto em Markdown acima e salve com o nome desafio-n8n.md (ou .txt).

Hospedar o arquivo:

Via Google Drive: Faça o upload do arquivo, clique em Compartilhar, altere para "Qualquer pessoa com o link" e copie a URL.

Via GitHub: Crie um repositório público (ex: meus-desafios-criativos), envie o arquivo .md e copie o link da página do arquivo.

Submeter: Cole o link gerado no campo de submissão da plataforma da DIO.
