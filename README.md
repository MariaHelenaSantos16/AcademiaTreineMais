# AcademiaTreineMais
Sistema criado pelo curso Programador de Sistemas, Senac Araguaína na turma 2025.5.42 no ano 2025.

## Descrição

Este sistema é voltado para uma academia pequena, para realizar:
- a organização dos horários de funcionamento da academia,
- a escala dos personal trainers,
- a lista de alunos matriculados,
- os planos de asssinaturas disponíveis,
- a estruturação de listas de treinos para os alunos acessarem.

## Requisitos

### Funcionais:

- Identificar e autenticar funcionário por CPF  
- Cadastrar, editar e excluir funcionário  
- Cadastrar, editar e excluir aluno  
- Registrar e editar avaliação física  
- Cadastrar, editar, ativar e inativar plano  
- Gerar contrato em PDF  
- Registrar e editar pagamento  
- Notificar vencimento da fidelidade  
- Cadastrar, editar treino e adicionar imagem/tutorial  
- Gerar treino em PDF  
- Cadastrar feriados e dias sem funcionamento  
- Exibir lista de alunos ativos e inativos  
- Exibir pagamentos do mês  
- Exibir relatório de lucro mensal  

### Não funcionais

- Garantir segurança dos dados   
- Suportar muitos cadastros de alunos 
- Permitir expansão para novas formas de pagamento  
- Gerar arquivos em PDF (contratos e treinos)  
- Ser compatível com desktop  
- Ter interface simples e reativa  
- Realizar notificações automáticas  
- Armazenar dados
- Possibilitar mudança de Temas: Claro e Escuro


## Telas

### Tela Inicial
- Identificação do funcionário via CPF
- Campo de CPF + Botão de acesso
- Primeira tela ao abrir o sistema

### Aba: Controle de Clientes
- Aparece após o login do funcionário
- Mostra a lista de alunos/clientes
- Opções para editar/cadastrar

### Menu Superior (aparece após login)
- Itens principais disponíveis no topo da tela

### Avaliação Física
- Peso, Altura, Medidas corporais, Idade
- Cadastro de avaliação por aluno

### Cadastro (guia expandível)
#### > Aluno:
- Nome completo, CPF, Telefone / WhatsApp, E-mail
- Contato de emergência
- Plano, Status do plano
- Avaliação física (opcional)
- Data de pagamento, Data de cadastro
- Vencimento da fidelidade
- Alerta de fidelidade próxima ao fim

#### > Funcionário:
- Nome completo, CPF, Telefone, Cargo
- Botões: Cadastrar / Excluir funcionário

### Calendário / Agenda
- Inserir feriados e dias sem funcionamento
- Exibição em formato de calendário

### Treinos
- Cadastrar treinos personalizados
- Campos: Nome do exercício, Séries, Tempo, Imagem/Tutorial
- Gerar PDF com treino para o aluno

### Planos
- Criar / Editar / Excluir planos
- Gerar contrato em PDF para assinatura

### Financeiro (ADM)
- Ver pagamentos mensais
- Listar inadimplentes
- Calcular lucros do período


