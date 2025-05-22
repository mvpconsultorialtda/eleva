### Instruções 1
🌳 MENU LATERAL – ELEVA

🧭 Geral
🗂️ Editais Abertos
 → Todos os editais públicos disponíveis na plataforma.


🏆 Projetos Aprovados
 → Galeria de projetos já aprovados (para inspiração, estudo, transparência).


📈 Ranking de Arrecadação
 → Lista com maiores captadores:


Por Pessoa


Por Empresa


Por Instituição



👤 Minha Área
🧾 Meus Editais
 → Onde o usuário já está inscrito, em rascunho ou submetido.


🧪 Meus Projetos
 → Projetos em andamento ou criados pelo usuário.


🛠️ Minhas Tarefas
 → Atividades e entregas pendentes.


📥 Projetos Sugeridos pela Eleva
 → Projetos que o usuário pode adotar ou propor.


🤝 Minhas Parcerias
 → Lista de colaboradores, empresas ou instituições com quem o usuário já trabalhou.



⚙️ Conta
🪪 Meu Perfil
 → Dados pessoais, documentos, vinculações (CPF/CNPJ etc).


🔔 Notificações
 → Alertas e avisos importantes.


🚪 Sair


### Instruções 2

🌱 Resumo do Projeto: Eleva
Eleva é uma plataforma digital desenvolvida pela MVP Consultoria com foco em potencializar a participação em editais públicos e privados de fomento à educação, inovação, arte e cultura.
A plataforma conecta proponentes (pessoas físicas ou jurídicas) com projetos estruturados e oferece todo o suporte técnico, operacional e estratégico para inscrição, gestão e execução dos projetos contemplados.

🛠️ O que a Eleva faz:
Seleciona e apoia proponentes com ou sem ideia inicial.


Apresenta editais disponíveis e oportunidades alinhadas ao perfil do usuário.


Escreve e submete os projetos para os editais escolhidos.


Gere todas as fases do projeto, incluindo prestação de contas, acompanhamento e entregas.


Atua como terceirizada ou parceira do proponente, recebendo por meio dos próprios recursos captados.


Entrega os produtos e resultados previstos, principalmente em projetos de base tecnológica.



🌿 Diferenciais:
Visual inspirado na natureza e crescimento (verde, branco, árvore como símbolo).


Navegação simples e fluida, com foco na experiência do usuário.


Plataforma que permite atuação desde a ideia até a execução.


Suporte integral: técnico, criativo, jurídico e administrativo.



###Instrução 3.2 – Atualizer o componente de menu lateral com mais itens se nem todos tiverem lá
Implementar um componente de menu lateral funcional, contendo os principais links para navegação dentro da plataforma. Os itens do menu serão:
Editais Abertos


Projetos Aprovados


Ranking de Arrecadação


Meus Projetos


Propostas em Andamento


Agenda & Prazos


Suporte / Briefing


O menu deverá apresentar uma divisão visual clara entre seções “Geral” (que abrange informações globais da plataforma) e “Pessoal” (relacionadas ao usuário e seus projetos). Cada item contará com ícones minimalistas e interativos que realcem a usabilidade, com efeitos de hover e clique para melhorar a experiência.

###Instrução 3.3 – Criar a Página Inicial / Dashboard
Construir uma página inicial que funcione como dashboard para o usuário, onde ele será recebido com um card de boas-vindas personalizado, mostrando o nome do usuário para criar uma conexão amigável.
Além disso, incluir destaques rápidos que ofereçam uma visão geral relevante, como o número total de editais disponíveis, o ranking pessoal do usuário baseado em sua performance na plataforma e um histórico dos seus últimos acessos.
Por fim, apresentar uma sugestão de edital aberto que possa interessar ao usuário, incentivando sua participação ativa na plataforma.

###Instrução 3.4 – Implementar Página "Editais Abertos"
Desenvolver uma página para listar todos os editais abertos, utilizando dados mockados inicialmente. Cada edital será exibido com informações essenciais como nome, tema, e prazo final para inscrição.
Para facilitar a busca, poderá ser implementado um sistema simples de filtros por área de atuação, permitindo que o usuário refine a lista conforme seus interesses.
Cada edital listado terá um botão “visualizar” que pode levar para uma página detalhada futuramente.

###Instrução 3.5 – Implementar Página "Projetos Aprovados"
Construir uma página que apresente os projetos aprovados organizados em cards visuais. Cada card exibirá o título do projeto, uma breve descrição e o status atual, como “aprovado” ou “financiado”.
O layout deve ser limpo e facilitar a leitura rápida do status dos projetos, para que o usuário possa acompanhar facilmente seus progressos e realizações.

###Instrução 3.6 – Implementar Página "Ranking de Arrecadação"
Criar uma página com uma tabela que exiba rankings de arrecadação, permitindo filtros para segmentar por Pessoa Física, Empresa ou Instituição.
As colunas da tabela incluirão o nome do participante, o total arrecadado em valores financeiros e o número de projetos submetidos ou apoiados.
O objetivo é incentivar a competitividade saudável e transparência dentro da plataforma.

###Instrução 3.7 – Criar Página "Meus Projetos"
Desenvolver uma página dedicada aos projetos criados pelo usuário logado, listando-os com seus respectivos status: rascunho, enviado ou aprovado.
Incluir um botão “Criar novo projeto” para permitir que o usuário inicie rapidamente um novo desenvolvimento, facilitando o fluxo de trabalho dentro da plataforma.

###Instrução 3.8 – Criar Página "Propostas em Andamento"
Implementar uma página com um editor de texto simples, que pode ser baseado em Markdown ou RichText, para que o usuário desenvolva suas propostas em andamento.
As propostas terão salvamento automático utilizando localStorage, garantindo que o conteúdo não seja perdido caso o usuário saia da página.
Incluir um botão “Enviar”, que inicialmente não terá funcionalidade, mas servirá para futura implementação do envio real da proposta.

###Instrução 3.9 – Criar Página "Agenda & Prazos"
Criar uma página com um calendário visual que exiba eventos importantes como prazos de envio, reuniões e outras datas relevantes, utilizando dados mockados para demonstração.
Esta funcionalidade ajudará o usuário a organizar seu tempo e não perder datas críticas para os editais e projetos.

###Instrução 3.10 – Criar Página "Suporte / Briefing"
Desenvolver uma página contendo um formulário simples para contato e suporte, com campos para nome, e-mail e mensagem.
O botão “Enviar” no momento apenas imprimirá as informações no console para simular o envio, servindo como base para futura integração com backend real.

###Instrução 4.1 – Criar mocks de dados (em arquivos JSON locais)
Preparar arquivos JSON que simulem as bases de dados da aplicação para facilitar o desenvolvimento frontend sem backend imediato. Arquivos a criar:
editais.json (lista de editais)


projetosAprovados.json (projetos aprovados)


ranking.json (dados do ranking)


meusProjetos.json (projetos do usuário)


agenda.json (eventos da agenda)


Estes mocks serão utilizados para alimentar as páginas e componentes até a integração real.

###Instrução 4.2 – Criar funções de leitura dos dados mockados
Implementar funções JavaScript que leiam os arquivos JSON locais simulando chamadas assíncronas via Promise e setTimeout, para dar uma sensação realista de requisição.
Exemplos: getEditais(), getProjetos(), getRanking().
Estas funções facilitarão o desenvolvimento e teste dos componentes que exibem dados.

###Instrução 4.3 – Criar funções de escrita utilizando localStorage
Desenvolver funções para salvar dados no localStorage do navegador, como propostas em andamento, novos projetos criados e mensagens enviadas no suporte.
Estas funções possibilitarão que o usuário tenha uma experiência persistente, mesmo sem backend, garantindo que seus dados não sejam perdidos em recarregamentos.

###Instrução 4.4 – Simular login e dados de usuário
Criar um sistema simples de login simulado, armazenando no localStorage informações básicas do usuário, como ID e nome.
Esses dados serão usados para personalizar a experiência, como exibir o nome no dashboard e associar projetos e propostas ao usuário.

###Instrução 5.1 – Modularizar dados via hooks ou serviços
Estruturar o código para separar a lógica de acesso a dados em hooks (React) ou serviços, como useEditais e useProjetos, facilitando a manutenção e futura substituição dessas chamadas por integrações reais, como Firebase.

###Instrução 5.2 – Esboçar modelo de collections para Firebase
Documentar o modelo inicial das collections no Firebase que suportarão a aplicação, com nomes e campos principais para cada coleção:
users (usuários)


editais (editais)


projetos (projetos)


ranking (dados do ranking)


mensagens (suporte e briefing)

