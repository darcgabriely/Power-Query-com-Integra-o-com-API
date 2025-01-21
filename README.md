# Power Query: Integracao com API

Este repositório contém um exemplo de como se conectar a uma API usando a linguagem Power Query M. O script demonstra como autenticar em uma API e recuperar dados de um endpoint protegido.

Como usar:
1. Pré-requisitos:
  - Power BI Desktop ou outra ferramenta que suporte Power Query M.
  - Acesso à API com credenciais válidas (login e senha).

2. Visão geral do Script:
   - Autenticar na API: Envia uma requisição POST com credenciais para obter um token de acesso.
   - Recuperar Dados: Usa o token de acesso para autenticar uma requisição GET e buscar dados na API.

3. Configuração
   Passo 1: Substitua os Marcadores

Substitua os marcadores no script pelos seus valores reais:

<seu_login>: Seu login da API.

<sua_senha>: Sua senha da API.

<url_da_api_de_login>: A URL do endpoint para autenticação na API.

<url_da_api_do_relatorio>: A URL do endpoint para recuperar o relatório.


Passo 2: Carregue o Script no Power Query

Abra o Power BI Desktop.

Vá em Página Inicial > Transformar Dados > Editor Avançado.

Cole o script no editor.


Passo 3: Valide a Conexão

Certifique-se de que as credenciais e URLs da API estão corretas. Verifique erros durante o carregamento dos dados.

OBS: O arquivo de codigo deste projeto se encontra na pasta deste repositorio




