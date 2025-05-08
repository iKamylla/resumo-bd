# resumo-bd
Este repositório contém o resumo e dicas sobre o processo de configuração de uma instância de Bando de Dados na plataforma da microsoft Azure da DIO.

Criar uma Instância de Banco de Dados no Azure (Azure SQL Database)
Acesse o portal do Azure:
Vá para portal.azure.com e faça login com sua conta.

Crie um novo recurso:
Clique em "Criar um recurso" > "Banco de dados" > "SQL Database".

Configure o banco de dados:
Nome do banco (ex: meubancoSQL)
Grupo de recursos (crie um novo se quiser organizar melhor)

Servidor SQL: crie um novo servidor com login e senha fortes.

Escolha o plano de uso:
Use o plano gratuito ou básico para estudos.
Confirme os preços e o desempenho antes de avançar.

Configure o firewall:
Permita o IP do seu computador para conseguir acessar o banco.
Não deixe o banco aberto para todos os IPs.

Crie a instância:
Revise e clique em "Criar". Aguarde a implantação.

Conecte-se ao banco:
Use ferramentas como:
Azure Data Studio
SQL Server Management Studio (SSMS)
Informe o nome do servidor, login e senha definidos.

Teste com comandos SQL básicos:
Crie uma tabela, insira dados, faça SELECTs.

  Dicas para Estudo e Prática com Azure SQL
    Use senhas seguras e não compartilhe.
    Exclua os recursos após usar para evitar cobranças.
    Documente tudo: anote os passos, tire prints e registre erros ou soluções.
    Crie um repositório com resumos, comandos SQL e boas práticas.
    Faça testes práticos de conexão, criação de tabelas e manipulação de dados.
