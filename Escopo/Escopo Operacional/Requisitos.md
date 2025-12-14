### 1. Identificação e Visão Geral
### 1.1 Nomes Sugeridos
- HomeFix
- HomeHelp
- HomeTask
- TaskHelp
- TaskFix
- AutoTask
### 1.2 Objetivos do Sistema
- Desenvolver uma plataforma robusta e responsiva para ajudar os usuários a se organizarem com suas tarefas do dia a dia, a fim de melhorar a produtividade e a performance, além de ajudar a lembrar de manter a manutenção de seus lares e moradias, tudo de maneira automatizada.

### 2. Requisitos Funcionais (Módulos)
### 2.1 Módulo de Internet
---
ID | Requisito Funcional | Descrição Detalhada

---
RF-I.1 | Salvar na Nuvem | O sistema deve ter a opção de backup de todas as suas informações de sua conta na nuvem

---
RF-I.2 | Multidispositivos | O sistema deve ter acesso em vários dispositivos (mobile, desktop, etc.)

---
RF-I.3 | Multiformatos | O sistema deve ter acesso para vários formatos (aplicativo, web, etc.)

---

### 2.2 Módulo de Tarefas
---
ID | Requisito Funcional | Descrição Detalhada

---
RF-T.1 | Criação de tarefa | O usuário deverá ter a opção de criar tarefas (uma de cada vez), em qualquer momento e qualquer dispositivo

---
RF-T.2 | Visualização de tarefas | O usuário deverá ter a opção de visualizar suas tarefas (uma de cada vez ou todas de uma vez), em qualquer momento e qualquer dispositivo

---
RF-T.3 | Atualização de tarefa | O usuário deverá ter a opção de editar as informações de suas tarefas (uma de cada vez) em qualquer momento e qualquer dispositivo

---
RF-T.4 | Apagamento de tarefa | O usuário deverá ter a opção de deletar suas tarefas (uma de cada vez) em qualquer momento e qualquer dispositivo

---
RF-T.5 | Agendamento | O usuário deverá ter a opção de agendar certa tarefa, atribuir o nome e o horário, além de decidir o período de quando cada tarefa deverá ser feita (diariamente, 1 vez/semana, 1 vez/mes, etc) ou decidir marcar os dias para quando será feita (sem ser periódicas)

---
RF-T.6 | Personalização | O usuário deverá ter a opção de personalizar a tarefa, adicionando nome, cor, tipo da tarefa (com nome e cor para o tipo) e adicionar nota na tarefa.

---
RF-T.7 | Lembrete | O sistema deverá lembrar regularmente ao usuário (por meio de notificações) para quando ele terá que realizar certa tarefa (horário, dia da semana, mês e ano)

---
RF-T.8 | Lista de compras | O sistema deverá ter a opção de adicionar uma lista de compras, caso o usuário marque a opção "Compras"

---

### 2.3 Módulo de IA
---
ID | Requisito Funcional | Descrição Detalhada

---
RF-IA.1 | Inteligência Artificial | O sistema deverá ter integração com IA e várias funcionalidades provenientes dela

---
RF-IA.2 | IA Opcional | O sistema deverá dar a opção ao usuário de ativar ou desativar o modo IA

---
RF-IA.3 | Sugestões para mercado | A IA do sistema deverá dar sugestões de produtos novos no mercado, ou de novas marcas de produtos que o usuário compra regularmente

---
RF-IA.4 | Sugestões para limpeza | A IA do sistema deverá dar sugestões de produtos de limpeza diversos ao usuário, de acordo com as características de limpeza que o usuário faz (aspiradores novos, marcas de sabão, detergente, novas vassouras, dentre outros recursos)

---
RF-IA.5 | Previsões de estoque | A IA do sistema deverá fazer previsões de produtos que estejam acabando na casa do usuário

---
RF-IA.6 | Chatbot | O sistema deverá ter um chatbot online para dúvidas do usuário

---

### 2.4 Módulo de Central de Ajuda
---
ID | Requisito Funcional | Descrição Detalhada

---
RF-C.1 | Central de ajuda | O sistema deverá fornecer uma central de ajuda online ao usuário

---
RF-C.2 | Aba de seções | A central de ajuda deverá ter uma aba para visualizar as diversas seções da central

---
RF-C.3 | Pesquisa | A central de ajuda deverá ter uma aba de pesquisa para os usuários pesquisarem e selecionarem diretamente os tópicos desejados (dúvidas, questões, seções, etc.)

---
RF-C.4 | Dúvidas Frequentes | A central de ajuda deverá ter uma aba de dúvidas que ocorrem com frequência entre os usuários

---
RF-C.5 | Login e recuperação de senha | A central de ajuda deverá ter uma aba com dúvidas e questões relacionadas ao login e recuperação de senha

---
RF-C.6 | Gerenciamento de Conta | A central de ajuda deverá ter uma aba sobre dúvidas e questões relacionadas ao gerenciamento da conta (editar informações, como cadastrar e usar a conta, etc.)

---
RF-C.7 | Privacidade e Segurança | A central de ajuda deverá ter uma aba sobre dúvidas e questões relacionadas à privacidade e segurança da conta, com dicas de segurança sobre como proteger a conta, proteger informações pessoais, proteger informações de login, etc.

---
RF-C.8 | Chatbot | A central de ajuda deverá ter integração com o chatbot do módulo de IA

### 3. Requisitos Não Funcionais

---
Categoria | ID | Requisito Não Funcional

---
Desempenho | RNF-D.1 | O CRUD de tarefas no banco deve demorar no máximo poucos segundos

---
Desempenho | RNF-D.2 | As perguntas e respostas da IA no formato chatbot devem demorar no máximo poucos segundos

---
Desempenho | RNF-D.3 | As respostas das pesquisas na Central de Ajuda (RF-C.3) devem demorar no máximo poucos segundos

---
Usabilidade | RNF-U.1 | O sistema deve ter uma interface intuitiva e amigável.

---
Usabilidade | RNF-U.2 | A IA no formato chatbot deve dar perguntas e respostas fáceis e compreensivas para os diversos públicos de usuários do sistema (para aquelas perguntas e respostas que JÁ são pré-estabelecidas)

---
Usabilidade | RNF-U.3 | As sugestões e notificações da IA (RF-IA.3 e RF-IA.4) devem ser curtas e de fácil compreensão para os diversos públicos de usuários do sistema, em relação ao que ela se propõe a fazer nesses requisitos

---
Confiabilidade | RNF-C.1 | O CRUD de tarefas deve ser feito com perguntas antes do usuário confirmar as alterações

---
Confiabilidade | RNF-C.2 | As previsões de respostas da IA do chatbot devem ter uma boa taxa de acerto (para as perguntas e respostas que NÃO são pré-estabelecidas)

---
Confiabilidade | RNF-C.2 | As sugestões e notificações da IA (RF-IA.3 e RF-IA.4) devem ter uma boa taxa de acerto para o que ela se propõe a fazer nesses requisitos

---
Confiabilidade | RNF-C.3 | O CRUD de usuários deve ser feito com perguntas antes de serem confirmadas as alterações na base de dados

---
Segurança | RNF-S.1 | As informações de usuário devem possuir boa integridade e segurança de dados

---
Segurança | RNF-S.2 | As informações de tarefas do usuário devem possuir privacidade total ao próprio usuário, até que ele decida compartilhá-las através de links disponibilizados na própria tarefa

---
Manutenibilidade | RNF-M.1 | O sistema deve possuir facilidade de adaptações e atualizações ao longo do tempo

---
Escalabilidade | RNF-E.1 | O sistema deve suportar altas cargas de armazenamento e processamento de tarefas de usuários e usos da IA, sem comprometer sua estabilidade

---
Portabilidade | RNF-P.1 | O acesso ao sistema deve possuir compatibilidade com diferentes tipos de dispositivos (Celular, Tablet, Desktop, Laptop, etc.)

---
Portabilidade | RNF-P.2 | O acesso ao sistema deve possuir compatibilidade com navegadores modernos (Chrome, Firefox, Opera, Edge, etc.)

---
Portabilidade | RNF-P.3 | O acesso ao sistema deve possuir compatibilidade com diferentes formatos de aplicação (Apps de Instalação e Web)

---

**Obs:**
Desempenho - Resposta rápida para cargas de trabalho
Usabilidade - Facilidade de uso ao sistema
Confiabilidade - Garantia de estabilidade e redução erros
Segurança - Proteção contra acessos não autorizados
Manutenibilidade - Facilidade de atualização, depuração de modificação no sistema, em curto, médio e longo prazo
Escalabilidade - Capacidade de expansão do sistema para acomodar demandas crescentes
Portabilidade - Capacidade da flexibilidade do sistema para operar em vários ambientes ou plataformas