# 2. Requisitos Não Funcionais
A Tabela 2 a seguir contém os Requisitos Não Funcionais (RNF) elicitados utizando a técnica de Brainstorm .

| ID | Requisito | Categoria | Prioridade | Requisitos relacionados |
| --- | --- | --- | --- | --- |
| RNF01 | A aplicação deve ter um tempo de resposta inferior a 2 segundos para qualquer operação. | DESEMPENHO | ALTA | RF01 a RF10 |
| RNF02 | O sistema deve estar disponível 99,5% do tempo mensal. | CONFIABILDADE | ALTA | TODOS OS RF |
| RNF03 | A aplicação deve ser responsiva e funcionar em dispositivos móveis e desktops. | USABILIDADE | ALTA | RF01 a RF16 |
| RNF04 | Os dados dos usuários devem ser armazenados de forma segura com criptografia. | SEGURANÇA | ALTA | RF01 - RF14 - RF16 |
| RNF05 | O sistema deve seguir a LGPD (Lei Geral de Proteção de Dados). | LEGALIDADE | ALTA | RF01 - RF14 - RF16 |
| RNF06 | O login deve exigir autenticação com senha segura (mínimo de 8 caracteres, incluindo números). | SEGURANÇA | ALTA | RF16 |
| RNF07 | A interface deve seguir padrões de design intuitivo e acessível (ex: contrastes, legibilidade). | USABILIDADE | MÉDIA | RF01 a RF16 |
| RNF08 | O sistema deve permitir escalabilidade para suportar crescimento no número de usuários. | ESCALABILIDADE | MÉDIA | TODOS OS RF |
| RNF09 | Toda a comunicação entre cliente e servidor deve ser feita por meio de HTTPS. | SEGURANÇA | ALTA | TODOS OS RF |
| RNF10 | O código deve ser modularizado para facilitar manutenção e futuras melhorias. | MANUTENIBILIDADE | MÉDIA | TODOS OS RF |
| RNF11 | O sistema deve oferecer suporte multilíngue em até um ano de funcionamento. | PORTABILIDADE | BAIXA | RF01  a RF15 |
| RNF12 | O tempo de carregamento inicial da aplicação não deve exceder 3 segundos. | DESEMPENHO | ALTA | RF03 - RF16 |

Tabela 2: Requisitos Não Funcionais
