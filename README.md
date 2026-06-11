✨ Microsoft Copilot Studio 

# **💡Criando um Agente**

Criar um agente no Copilot Studio envolve algumas etapas fundamentais que permitem personalizar e configurar o comportamento da IA para atender às necessidades específicas de um negócio ou projeto. Vou citar um exemplo de um ChatBot criado para dar suporte a usuários de um sistema ERP de uma empresa:



**📁 1. Objetivo**

Identificar o objetivo principal do agente (ex.: atendimento ao cliente, suporte interno). Determinar quais tarefas ou fluxos de conversa ele deve executar.

***

 **📁 2. Criação do agente**

 :leaves: Clique em Criar Novo Agente.

 :leaves: Dê um nome claro, por exemplo: Suporte ERP Ambiental.
 
 :leaves: Configure a personalidade do agente:

          Tom: profissional, amigável e orientado a soluções.

          Contexto: suporte especializado em ERP para gestão ambiental.

***

 **📁 3.  Configuração dos tópicos**

A criação e configuração de tópicos para um agente de suporte ERP segue uma lógica de conversas guiadas. Cada tópico funciona como uma “rota de atendimento” que organiza o diálogo e ajuda o agente a responder de forma estruturada. 
Vou detalhar como isso é feito:

 **:zap: Problemas de Login**

   Gatilhos: 
   
    “não consigo entrar”, “senha inválida”, “usuário bloqueado”.

   Fluxo:
    
    Saudação: “Você está com dificuldade de acesso, certo?”
    Pergunta: “Já tentou redefinir sua senha?”

Se sim → instruções de redefinição.

Se não → link para redefinição.

Persistindo → abrir ticket para suporte técnico.

**⚡Cadastro de Clientes/Fornecedores**

Gatilhos: 

    “cadastrar cliente”, “novo fornecedor”, “alterar dados”.

Fluxo:

    Pergunta: “Deseja incluir ou atualizar um cadastro?”

Se incluir → coletar dados básicos (nome, CNPJ, contato).

Se atualizar → pedir código/ID do cadastro.

Orientar passo a passo ou abrir formulário.


**⚡ Controle de Estoque**

Gatilhos: 

    “estoque baixo”, “entrada de mercadoria”, “inventário”.

Fluxo:

    Pergunta: “Deseja registrar entrada, saída ou consultar saldo?”

Se entrada → solicitar dados da nota de compra.

Se saída → vincular o pedido de venda.

Se consulta → mostrar saldo atual.

***

 **📁 4. Integrações e ações**

O agente pode se conectar a dados corporativos (como bases de conhecimento e sistemas internos). É possível configurar ações personalizadas para buscar informações, realizar cálculos ou interagir com APIs externas.
O conector que utilizei foi o SharePoint para buscar em uma página específica criada como base de conhecimento a resolução do problema informado no ChatBot. E futuramente pretendo criar o inverso, os problemas resolvidos vão alimentar essa base de conhecimento.

***

 **📁 5. Testes e ajustes**

O agente é testado diretamente no ambiente do Copilot Studio. Ajustes são feitos para melhorar a clareza das respostas e garantir que os fluxos funcionem corretamente. Durante a criação foi realizado diversas alterações devido a vários fatores, o mais específico relacionado a licença de Admin para realizar as conecções necessárias no ambiente.

***

 **📁 6. Publicação e uso**

Após os testes, o agente pode ser publicado e disponibilizado em diferentes canais (Teams, sites, aplicativos). É possível monitorar métricas de uso e treinar continuamente o agente para evoluir. Não realizei a publicação pois pretendo realizar mais algumas configurações e explorar certos conectores que ainda preciso estudar mais a fundo para ter um melhor aproveitamento.

***


 # 🎯Conclusão: 
 Realizei a criação de um ambiente de desemvolvimento para produzir o projeto proposto, assim não interferia em projetos já construidos no Copilot Studio na empresa que trabalho, usei uma conta corporativa para acesso ao ambiente. Assim conseguir criar um agente e trabalhar nele de forma espontânea e com liberdade. Conclui que para melhor desempenho de qualquer que seja o projeto sempre será necessário uma atualização, tanto de desenvolvimento quanto de script personalizados por mim, com isso será possível uma avaliação positiva dos colaboradores referente ao produto criado.

