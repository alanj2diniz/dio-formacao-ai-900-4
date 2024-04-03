# dio-formacao-ai-900-4
 Teste AI Search Azure


Como fazer:
Acessar portal azure https://portal.azure.com/#create/Microsoft.Search
Create Resource -> Marketplace -> Azure AI Search
Criar de acordo com as configurações necessárias

Na sequencia, deve-se criar um recurso: Azure AI services 
Selecionar as configurações necessárias e Criar

Após criado os 2 servisço:
Azure AI services
AI Search

Criar uma conta de armazenamento:
Procurar na busca: Storage Accounts -> Create
Depois de criado, acessar o storage account e ir em Configuration
Alterar a configuração "Allow Blob anonymous access" para "Enabled" permitindo acesso externo

Ainda dentro do storage account, acessar Data Storage -> Containers
Clicar em "+ Container" para criar um novo
Acesar o container e fazer upload dos arquivos

Acessar AI Search -> Import Data
Selecionar a origem dos dados

Depois de importado, acessar o Search Explorer
Selecionar o "Index"



Insights:
São vários. Um insights muito útil seria dentro da empresa, na pesquisa de documentação de software.
A VTEX por exemplo possui um help https://help.vtex.com/ extenso e com muito conteúdo.
Muitas vezes a busca da própria VTEX não retorna o resultado esperado e o Google por exemplo consegue achar melhor o conteúdo.
Aqui por exemplo seria um ótimo caso para aplicar AI Search.