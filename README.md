### 6.2 – Página Detalhada de Edital
Objetivo: Fornecer ao usuário todas as informações relevantes de um edital antes da submissão.
Atividade: Criar uma página dedicada com o conteúdo completo de cada edital selecionado, incluindo prazos, valores, critérios e documentos exigidos.
Valor agregado: Ajuda na tomada de decisão informada e no planejamento da proposta.

### 6.3 – Editor Completo de Projeto
Objetivo: Oferecer um ambiente estruturado para o usuário desenvolver sua proposta completa.
Atividade: Desenvolver a tela de edição com campos para descrição, objetivos, metas, orçamento, etc. Incluir botões de salvar rascunho e finalizar.
Valor agregado: Permite o desenvolvimento progressivo da proposta com segurança e organização.

### 7.1 – Integração com Biblioteca de Calendário
Objetivo: Visualizar de forma clara os prazos e compromissos associados aos editais e projetos.
Atividade: Utilizar uma biblioteca como fullcalendar para mostrar eventos e deadlines. Diferenciar tipos de eventos com cores.
Valor agregado: Ajuda na organização e no cumprimento de prazos importantes.

### 7.2 – Criação de Evento Manual
Objetivo: Permitir que o usuário insira seus próprios eventos relacionados aos projetos e editais.
Atividade: Criar um formulário para adicionar eventos com campos de data, título e descrição. Armazenar no localStorage.
Valor agregado: Aumenta o controle do usuário sobre sua própria agenda de participação.

### 8.1 – Sistema de Notificações Mockado
Objetivo: Alertar o usuário sobre prazos e mudanças importantes na plataforma.
Atividade: Criar um componente de notificação com badge e lista de mensagens simuladas.
Valor agregado: Melhora a usabilidade e evita esquecimentos de prazos críticos.

### 8.2 – Regras Simples para Geração de Notificações
Objetivo: Gerar notificações automáticas com base em lógica simples.
Atividade: Criar regras como “faltam 2 dias para o fim do edital X” e notificar o usuário.
Valor agregado: Automatiza alertas importantes e contribui para a retenção de usuários ativos.

### 9.1 – Comentários nas Propostas
Objetivo: Permitir que usuários troquem feedbacks e colaborem diretamente dentro de uma proposta.
Atividade: Adicionar uma área de comentários ao final de cada proposta, com campo de autor e data.
Valor agregado: Cria um ambiente colaborativo e melhora a qualidade das propostas.

### 9.2 – Compartilhamento de Propostas (mock)
Objetivo: Simular o compartilhamento de uma proposta com outros usuários.
Atividade: Criar uma função que adiciona e mostra “colaboradores” no projeto, baseando-se em e-mails digitados.
Valor agregado: Prepara o terreno para colaboração real futura com controle de permissões.

### 10.1 – Dashboard de Métricas Pessoais
Objetivo: Apresentar dados sobre a atividade do usuário na plataforma.
Atividade: Criar cards e gráficos com número de projetos submetidos, taxa de aprovação e valores simulados.
Valor agregado: Gera insights pessoais, motiva engajamento e melhora a percepção de progresso.

### 10.2 – Exportação Simples de Dados
Objetivo: Permitir que o usuário baixe seus dados para análise externa.
Atividade: Criar um botão para exportar em CSV informações dos projetos e propostas.
Valor agregado: Oferece autonomia ao usuário e facilita apresentações ou relatórios offline.

### 11.1 – Separar Serviços por Contexto
Objetivo: Preparar a arquitetura da aplicação para uso com backend real.
Atividade: Organizar todas as funções de acesso a dados em arquivos separados por tema, como editais.js ou usuarios.js.
Valor agregado: Facilita a manutenção do código e a futura substituição do mock por chamadas reais de API.

### 11.2 – Criar Adapter de LocalStorage para Backend
Objetivo: Tornar possível alternar entre mock e dados reais sem refatorar tudo.
Atividade: Criar funções genéricas como saveToLocal/saveToBackend, que usem lógica condicional para acessar o localStorage ou uma API.
Valor agregado: Proporciona transição suave do protótipo para o produto final com backend real.

### 12.1 – Firebase Config Inicial
Objetivo: Iniciar a estrutura de backend real utilizando o Firebase.
Atividade: Criar e configurar um projeto no Firebase e integrá-lo ao app Next.js.
Valor agregado: Permite escalabilidade, autenticação segura e armazenamento em nuvem.

### 12.2 – Autenticação Firebase
Objetivo: Substituir o sistema de login mock por autenticação real.
Atividade: Implementar login com e-mail/senha e integração com Google via Firebase Auth.
Valor agregado: Melhora segurança, permite login real e prepara o app para produção.

### 13.1 – Listagem de Propostas por Edital
Objetivo: Exibir todas as propostas que o usuário criou para um edital específico.
Atividade: Criar uma aba ou seção na página do edital que mostre os projetos relacionados.
Valor agregado: Facilita a navegação e gerenciamento de propostas ativas e passadas.

### 13.2 – Filtros e Busca de Propostas
Objetivo: Ajudar o usuário a localizar rapidamente uma proposta específica.
Atividade: Adicionar filtros por status (rascunho, enviado, aprovado) e campo de busca por nome.
Valor agregado: Melhora a produtividade e evita perda de tempo procurando dados.

### 13.3 – Sistema de Status de Proposta
Objetivo: Indicar em que etapa cada proposta se encontra.
Atividade: Adicionar rótulos visuais (ex: “Rascunho”, “Enviado”, “Aprovado”, “Rejeitado”) com ícones.
Valor agregado: Dá clareza sobre o andamento da proposta e reduz incertezas.

### 13.4 – Histórico de Alterações
Objetivo: Registrar mudanças feitas em uma proposta.
Atividade: Criar uma timeline com data, campo alterado e valor anterior/novo.
Valor agregado: Facilita auditoria e controle colaborativo da proposta.

### 13.5 – Upload de Arquivos Complementares
Objetivo: Permitir envio de documentos exigidos pelo edital.
Atividade: Criar campo de upload com tipos aceitos (PDF, DOCX, etc.).
Valor agregado: Centraliza todas as informações necessárias para submissão em um só lugar.

### 13.6 – Validador de Campos Obrigatórios
Objetivo: Impedir o envio de propostas incompletas.
Atividade: Implementar verificação automática de preenchimento mínimo antes de permitir salvar ou enviar.
Valor agregado: Reduz erros de submissão e aumenta chance de aprovação.

### 13.7 – Sistema de Rascunhos Automáticos
Objetivo: Evitar perda de trabalho por fechamento acidental da aba.
Atividade: Salvar automaticamente alterações em localStorage ou Firebase a cada X minutos.
Valor agregado: Melhora a experiência do usuário e protege o tempo investido.

### 13.8 – Editor com Sugestões Inteligentes (Mock)
Objetivo: Ajudar o usuário a melhorar a escrita da proposta.
Atividade: Inserir sugestões simuladas de melhoria ao lado de cada campo textual.
Valor agregado: Estimula o aperfeiçoamento da proposta e educa o usuário.

### 13.9 – Seletor de Modelos de Proposta
Objetivo: Acelerar a escrita com estruturas pré-definidas.
Atividade: Criar templates com tópicos orientadores e exemplos simulados.
Valor agregado: Reduz barreiras para iniciantes e padroniza a qualidade das submissões.

### 14.1 – Integração com Google Drive (Mock)
Objetivo: Simular exportação automática da proposta para o Drive do usuário.
Atividade: Criar botão com ícone do Google Drive que salva uma cópia localmente e exibe aviso.
Valor agregado: Cria hábito de backup externo mesmo sem integração real.

### 14.2 – Modo Apresentação da Proposta
Objetivo: Permitir visualizar a proposta em formato de leitura amigável.
Atividade: Criar uma tela com layout limpo, sem campos editáveis.
Valor agregado: Facilita revisão e compartilhamento visual da ideia.

### 14.3 – Impressão e Exportação em PDF
Objetivo: Permitir envio físico ou formal da proposta.
Atividade: Criar botão que exporta a proposta no modo apresentação em PDF.
Valor agregado: Adiciona versatilidade e utilidade no mundo offline.

### 14.4 – Destaque de Propostas Finalizadas
Objetivo: Ajudar o usuário a distinguir projetos prontos dos inacabados.
Atividade: Aplicar selo ou borda colorida para propostas marcadas como finalizadas.
Valor agregado: Melhora a organização e evita erros de envio.

### 14.5 – Marcação de Propostas Favoritas
Objetivo: Permitir que o usuário destaque projetos prioritários.
Atividade: Criar botão de “estrela” ou “coração” que mova a proposta para o topo da lista.
Valor agregado: Personaliza a experiência e ajuda a focar no que importa.

### 14.6 – Integração com Trello (Mock)
Objetivo: Simular organização das propostas por quadro Kanban.
Atividade: Criar interface visual com colunas tipo “ideia”, “em rascunho”, “finalizado”.
Valor agregado: Oferece visão macro do progresso de todas as propostas.

### 14.7 – Criação de Equipes de Projeto (Mock)
Objetivo: Simular estrutura de equipe por proposta.
Atividade: Permitir adicionar nomes fictícios e atribuições por função (redator, coordenador etc.).
Valor agregado: Prepara para integração real com times e divisão de tarefas.

### 14.8 – Avaliação Simulada por Pares
Objetivo: Simular uma análise externa da proposta.
Atividade: Gerar feedback automático ou permitir troca entre usuários do sistema.
Valor agregado: Aumenta qualidade das propostas antes do envio real.

### 14.9 – Relatório de Pontos Fortes e Fracos (Mock)
Objetivo: Apontar áreas que merecem revisão.
Atividade: Criar painel com análise simulada de aspectos como clareza, impacto e orçamento.
Valor agregado: Educa o usuário e melhora a proposta com base em critérios avaliativos.

### 15.1 – Integração com Chat de Suporte (Mock)
Objetivo: Simular atendimento em tempo real.
Atividade: Adicionar ícone de chat com respostas pré-programadas sobre como preencher campos.
Valor agregado: Aumenta confiança do usuário e reduz abandono.

### 15.2 – Página de Dúvidas Frequentes (FAQ)
Objetivo: Ajudar usuários com perguntas comuns.
Atividade: Criar seção com colapsáveis sobre funcionamento da plataforma, prazos, etc.
Valor agregado: Reduz suporte necessário e melhora usabilidade.

### 15.3 – Cadastro de Novo Edital (Mock)
Objetivo: Simular envio de novo edital pela organização.
Atividade: Criar tela administrativa com campos para título, regras e datas.
Valor agregado: Permite testes futuros com perfis de admins e curadores.

### 15.4 – Tela de Convite para Editais por E-mail (Mock)
Objetivo: Simular envio de convite para amigos participarem de um edital.
Atividade: Criar formulário com campo de e-mail e mensagem.
Valor agregado: Incentiva uso da plataforma de forma viral e colaborativa.

### 15.5 – Seletor de Idioma da Plataforma
Objetivo: Tornar a aplicação acessível a falantes de outros idiomas.
Atividade: Adicionar um dropdown para trocar entre “PT-BR” e “EN” com textos mockados.
Valor agregado: Prepara a plataforma para expansão internacional.

### 15.6 – Timeline da Plataforma
Objetivo: Mostrar evolução do projeto/propostas ao longo do tempo.
Atividade: Criar linha do tempo visual com marcos importantes.
Valor agregado: Dá perspectiva e estimula progresso contínuo.

### 15.7 – Gamificação com Pontos e Selos
Objetivo: Estimular engajamento dos usuários.
Atividade: Criar pontos por ações (ex: preencher tudo, submeter, revisar), com selos visuais.
Valor agregado: Torna a experiência mais divertida e recompensadora.

### 15.8 – Página Pública com Ranking de Propostas
Objetivo: Simular ambiente de competição positiva entre participantes.
Atividade: Criar leaderboard com pontuação simulada e nomes fictícios.
Valor agregado: Estimula a qualidade e aumenta a interação com a plataforma.

### 15.9 – Simulador de Chance de Aprovação (Mock)
Objetivo: Indicar ao usuário a maturidade da proposta.
Atividade: Criar um gráfico fictício com nota de 0 a 100 com base em critérios simples.
Valor agregado: Gera consciência crítica e incentiva melhoria contínua.

