# 1. Requisitos Funcionais
A Tabela 1 a seguir contém os Requisitos Funcionais (RF) elicitados utizando a técnica de Brainstorm.

| ID | Requisito | Prioridade | Requisitos Relacionados |
| --- | --- | --- | --- |
| RF01 | O sistema deve possuir uma tela de login para autenticação de usuários. | ALTA | BASE |
| RF02 | O sistema deve permitir o cadastro de novos usuários com e-mail e senha. | ALTA | RF01 |
| RF03 | O sistema deve permitir que o usuário realize login com suas credenciais. | ALTA | RF01 |
| RF04 | O sistema deve manter a sessão do usuário ativa enquanto ele estiver navegando, e permitir logout. | MÉDIA | RF01 - RF03 |
| RF05 | O sistema deve permitir o cadastro de receitas e despesas. | ALTA | RF01 - RF03 |
| RF06 | O sistema deve permitir a edição e exclusão de transações. | ALTA | RF05 |
| RF07 | O sistema deve permitir a categorização de transações. | ALTA | RF05 |
| RF08 | O sistema deve exibir o saldo mensal atualizado automaticamente. | ALTA | RF05 - RF07 |
| RF09 | O sistema deve gerar relatórios e gráficos financeiros mensais. | MÉDIA | RF05 - RF07 - RF08  |
| RF10 | O sistema deve permitir o filtro de transações por período e categoria. | MÉDIA | RF05 - RF07 |
| RF11 | O sistema deve permitir configurar lembretes para despesas fixas. | BAIXA | RF05 |
| RF12 | O sistema deve exportar transações em formato CSV ou PDF. | BAIXA | RF05 |
| RF13 | O sistema deve permitir o cadastro de metas financeiras mensais. | MÉDIA | RF05 - RF07 |
| RF14 | O sistema deve permitir o planejamento de metas para aquisição de bens de alto valor (ex: carro, casa, reforma). | MÉDIA | RF13 |
| RF15 | O sistema deve permitir o gerenciamento de orçamentos mensais por categoria. | ALTA | RF05 - RF07 |
| RF16 | O sistema deve possuir uma calculadora de juros simples e compostos. | MÉDIA | INDEPENDENTE |
| RF17 | O sistema deve possuir uma calculadora de câmbio, considerando cotação atual e taxas, exibindo valor líquido e bruto. | MÉDIA | INTEGRAÇÃO COM API EXTERNA |
| RF18 | O sistema deve permitir o envio de documentos (contratos, extratos) para análise por IA. | ALTA | RF01 - RF03 |
| RF19 | A IA deve gerar um resumo detalhado e informativo do conteúdo do arquivo, sem modificá-lo. | ALTA | RF18 |
| RF20 | O sistema deve exibir informações atualizadas sobre ações da bolsa de valores e criptomoedas. | MÉDIA | INTEGRAÇÃO COM API EXTERNA |
| RF21 |  O sistema **não deve** permitir a compra ou venda de ativos — apenas visualização de dados. | ALTA | RF20 |

Tabela 1: Requisitos Funcionais
