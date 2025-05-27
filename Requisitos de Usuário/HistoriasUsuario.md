# 3. História de Usuário
A Tabela 3 a seguir contém as Histórias de Usuárias elicitadas.

| **ID** | **História de Usuário** | **Critérios de Aceitação** | **Prioridade** | **RF/RNF Relacionado** |
| --- | --- | --- | --- | --- |
| US01 | Como usuário, quero registrar minhas receitas e despesas, para ter controle sobre meus ganhos e gastos mensais. | O sistema deve permitir inserir valores, datas, descrições e categorias de receitas/despesas. O saldo mensal deve ser atualizado automaticamente. | Alta | RF01 - RF03 - RNF01 - RNF03 |
| US02 | Como usuário, quero categorizar cada transação, para entender melhor onde estou gastando meu dinheiro. | Deve ser possível escolher categorias pré-definidas ou criar novas ao cadastrar uma transação. | Alta | RF02 - RNF01 - RNF03 |
| US03 | Como usuário, quero visualizar meu saldo a qualquer momento, atualizado automaticamente, para saber quanto ainda posso gastar. | O saldo deve ser exibido de forma clara na tela inicial e refletir todas as transações do mês. | Alta | RF03 - RNF01 - RNF12 |
| US04 | Como usuário, quero acessar gráficos e relatórios de gastos mensais, para analisar meus hábitos financeiros. | O sistema deve gerar relatórios e gráficos interativos com base nas transações por período e categoria. | Alta | RF04 - RF06 - RNF01 |
| US05 | Como usuário, quero poder editar ou excluir transações que cadastrei por engano, para manter os dados corretos. | O sistema deve permitir a edição e exclusão de qualquer transação cadastrada. | Alta | RF05 - RNF01 |
| US06 | Como usuário, quero filtrar minhas transações por período e por categoria, para analisar meus gastos com mais detalhe, podendo ser de forma simultânea ou por período. | Os filtros devem funcionar por intervalo de datas e categorias, com atualização imediata da visualização. | Média | RF06 - RF04 - RNF01 |
| US07 | Como usuário iniciante, quero uma interface clara e fácil de usar, para que eu consiga gerenciar minhas finanças mesmo sem conhecimento técnico. | O sistema deve ter menus intuitivos, textos explicativos e usabilidade testada com usuários reais. | Alta | RNF03 - RNF07 - RNF12 |
| US08 | Como usuário, quero configurar lembretes para despesas fixas, para não esquecer de registrá-las mensalmente. | O sistema deve permitir cadastrar lembretes com recorrência e notificação. | Média | RF08 - RNF01 |
| US09 | Como usuário, quero exportar minhas transações em CSV ou PDF, para guardar backups ou compartilhar com meu contador. | Deve haver uma opção de exportação com seleção de período e formato. | Média | RF09 - RNF01 - RNF10 |
| US10 | Como usuário, quero acessar uma calculadora de juros simples e compostos, para planejar investimentos ou dívidas. | A calculadora deve solicitar valor inicial, taxa, tempo e tipo de juros e exibir os cálculos corretamente. | Alta | RF11 - RNF01 - RNF03 |
| US11 | Como usuário, quero definir e acompanhar orçamentos por categoria, para evitar ultrapassar meus limites mensais. | O sistema deve permitir configurar limites por categoria e alertar quando eles forem atingidos. | Alta | RF12 - RF02 - RNF01 |
| US12 | Como usuário, quero criar metas financeiras para compras caras, como casa ou reforma, para me planejar melhor. | O sistema deve permitir definir um objetivo, valor-alvo, prazo e mostrar o progresso mensal. | Alta | RF13 - RF10 - RNF01 |
| US13 | Como usuário, quero acessar uma calculadora de câmbio com taxas, para saber quanto receberei ao trocar moedas. | A calculadora deve usar cotação atual (API) e aplicar taxas, mostrando valor líquido e bruto. | Alta | RF14 - RNF01 - RNF09 |
| US14 | Como usuário, quero enviar contratos ou extratos para análise por IA, para entender melhor documentos financeiros. | O sistema deve aceitar upload de arquivos e retornar um resumo claro sem alterar o conteúdo. | Alta | RF15 - RNF04 - RNF05 - RNF10 |
| US15 | Como usuário, quero visualizar dados da bolsa e criptomoedas, para acompanhar investimentos em tempo real. | O sistema deve exibir cotações em tempo real, mas não permitir compra ou venda de ativos. | Média | RF15 - RNF01 - RNF09 |
| US16 | Como usuário, quero poder me cadastrar e fazer login com segurança, para acessar meus dados financeiros pessoais. | O sistema deve exigir autenticação segura, com senha forte, validação e criptografia de dados. | Alta | RF16 - RNF04 - RNF05 - RNF06 |

Tabela 3: História de Usuário
