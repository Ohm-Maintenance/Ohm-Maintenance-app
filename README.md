Requisitos Funcionais: RF01:

O sistema deve permitir o cadastro de empresas, e através do mesmo, o cadastro de seus respectivos funcionários

RF02: O sistema deve ser capaz de cadastrar, atualizar, exibir informações de usuário e deletar as informações

RF03: O sistema deve permitir o cadastro de perfil de maquinários.

RF04: O sistema deve permitir a inclusão de manuais e documentações técnicas dos maquinários cadastrados

RF05: O sistema deve permitir a adição de documentação dos maquinários

RF06: O sistema deve exibir o status de saúde de cada maquinário,  através do mecanismo sensorial instalado nas mesmas.

Requisitos não Funcionais:

RNF01: O sistema deve ter mecanismo de acessibilidade

RNF02: O sistema deve facilitar manutenções futuras através da análise preditiva dos sensores dos maquinários

RNF03: O sistema deve ser responsivo e multiplataforma

RNF04: O sistema deve possuir velocidade em seu funcionamento

User Stories:

Técnico de Manutenção US01: Consulta Rápida de Manuais via IA/Busca. Como técnico de manutenção, quero pesquisar por termos, códigos de erro ou tirar dúvidas diretamente em um chat integrado aos manuais do equipamento, para que eu possa encontrar a solução e o procedimento de reparo corretos em segundos, sem precisar carregar manuais impressos volumosos. Critérios de Aceite: O sistema deve aceitar busca por texto livre e comandos de voz (falar o sintoma). A resposta deve indicar a página exata do manual oficial ou o trecho correspondente. O chat deve funcionar offline (com base nos manuais baixados localmente no tablet/smartphone). 

Técnico de Manutenção US02: Visualização de Alertas de Sensores em Tempo Real. Como técnico de manutenção, quero receber notificações no meu dispositivo móvel quando um sensor (vibração, som, temperatura) detectar uma anomalia em uma máquina, para que eu possa agir rapidamente antes que ocorra uma falha catastrófica (manutenção preditiva). Critérios de Aceite: A notificação push deve conter o nome/ID da máquina, o tipo de alerta (ex: vibração excessiva) e a severidade (Baixa, Média, Crítica). O app deve abrir diretamente na tela de diagnóstico da máquina afetada. 

Técnico de Manutenção US03: Registro de Ordem de Serviço (OS) em Campo. Como técnico de manutenção, quero registrar o fechamento de uma ordem de serviço, adicionar fotos do reparo e trocar o status da máquina pelo aplicativo, para que o histórico do maquinário esteja sempre atualizado para a equipe de gestão. Critérios de Aceite: Permitir anexar fotos tiradas na hora ou da galeria. O sistema deve funcionar mesmo sem internet, sincronizando os dados automaticamente assim que houver conexão.

Gestor de Confiabilidade US04: Dashboard de Saúde do Maquinário. Como engenheiro de confiabilidade, quero visualizar um painel geral com o status de saúde de todo o parque fabril baseado nos dados dos sensores, para que eu possa identificar gargalos, prever quebras e planejar manutenções preventivas com antecedência. Critérios de Aceite: O dashboard deve exibir indicadores visuais (cores como Verde/Amarelo/Vermelho) para os níveis de vibração e ruído de cada ativo. O usuário deve conseguir filtrar por setor da fábrica, linha de produção ou criticidade da máquina. 

Analista de Vibração/Som US05: Análise de Espectro e Dados Brutos dos Sensores. Como analista de vibração/som, quero visualizar gráficos detalhados de tendência, espectro acústico dos sensores, para que eu possa diagnosticar o tipo exato de falha mecânica (ex: desalinhamento, desbalanceamento, falha de rolamento). Critérios de Aceite: O sistema deve plotar gráficos temporais e espectrais dos dados coletados pelos sensores IoT. O usuário deve conseguir comparar dados atuais com o histórico de linha de base (baseline) do equipamento. 

Gestor de Manutenção US06: Configuração de Limites de Alerta (Thresholds). Como gestor de manutenção, quero configurar os limites toleráveis de vibração, ruído e temperatura para cada máquina, para que o sistema gere alertas automáticos sempre que os parâmetros saírem da normalidade operacional. Critérios de Aceite: Permitir definir limites diferentes para diferentes estados da máquina (ex: partida, operação contínua, marcha lenta). Possibilidade de definir múltiplos níveis de alerta (Aviso e Alarme Crítico).

Administrador do Sistema US07: Gerenciamento de Ativos e Upload de Manuais. Como administrador do sistema, quero cadastrar novas máquinas e fazer o upload de seus respectivos manuais em formato PDF, para que a base de conhecimento e os sensores fiquem vinculados corretamente aos ativos da fábrica. Critérios de Aceite: O sistema deve processar o PDF do manual, indexando o conteúdo automaticamente para a busca inteligente (RAG/IA). Permitir associar o ID do sensor físico IoT ao cadastro da máquina correspondente.
