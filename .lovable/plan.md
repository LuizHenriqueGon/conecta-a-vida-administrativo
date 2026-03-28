

## Portal Administrativo de Postos de Saúde

### Visão Geral
Portal completo para administradores de postos de saúde com dashboard, gestão de campanhas de vacinação e painel de alertas de doação de sangue. Design clean e moderno com fundo branco e acentos em azul.

---

### Páginas e Funcionalidades

#### 1. Layout Principal
- Sidebar com navegação: Dashboard, Campanhas, Alertas, Configurações
- Header com nome do posto, avatar do admin e botão de logout
- Sidebar colapsável com ícones

#### 2. Dashboard (`/`)
- Cards com métricas: campanhas ativas, doses aplicadas no mês, alertas emitidos, agendamentos do dia
- Gráfico de vacinações por semana (últimas 8 semanas)
- Lista das próximas campanhas
- Alertas recentes de doação de sangue

#### 3. Campanhas de Vacinação (`/campanhas`)
- Tabela com todas as campanhas (nome, período, status, doses aplicadas/disponíveis)
- Filtros por status (ativa, encerrada, agendada) e busca por nome
- Botão "Nova Campanha" abre formulário completo:
  - Nome da vacina, descrição, faixa etária, documentos necessários
  - Datas de início/fim, horários de atendimento
  - Doses disponíveis (controle de estoque)
  - Status: rascunho, ativa, pausada, encerrada
- Página de detalhes da campanha com:
  - Informações completas + edição
  - Relatório de vacinados (tabela com nome, data, dose)
  - Agendamentos (lista com horário, paciente, status)
  - Indicador visual de estoque restante

#### 4. Alertas de Doação de Sangue (`/alertas`)
- Lista de alertas com tipo sanguíneo, nível de urgência (crítico/alto/médio), data e local
- Badges coloridos por urgência (vermelho = crítico, laranja = alto, amarelo = médio)
- Botão "Novo Alerta" com formulário:
  - Tipo(s) sanguíneo(s) necessário(s) (A+, A-, B+, B-, AB+, AB-, O+, O-)
  - Nível de urgência
  - Local de doação, horário de funcionamento
  - Mensagem/observações
- Possibilidade de encerrar/arquivar alertas

#### 5. Configurações (`/configuracoes`)
- Informações do posto de saúde (nome, endereço, telefone)
- Horário de funcionamento

---

### Design
- Fundo branco, sidebar cinza claro, acentos em azul (#2563EB)
- Cards com sombras sutis e bordas arredondadas
- Tipografia limpa, estilo dashboard SaaS
- Responsivo para tablets e desktop
- Dados mockados para todas as telas (sem backend real nesta fase)

