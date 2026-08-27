Requisitos Funcionais:

RF01: O sistema deve permitir o cadastro de empresas, e através do mesmo, o cadastro de seus respectivos funcionários.

RF02: O sistema deve ser capaz de cadastrar, atualizar, exibir informações de usuário e deletar as informações.

RF03: O sistema deve permitir o cadastro de perfil de maquinários.

RF04: O sistema deve permitir a inclusão de manuais e documentações técnicas dos maquinários cadastrados.

RF05: O sistema deve permitir a adição de documentação dos maquinários.

RF06: O sistema deve exibir o status de saúde de cada maquinário, através do mecanismo sensorial instalado nas mesmas.

RF07: O sistema registrar e exibir data, hora e turno para controle de documentação e manutenção.

Requisitos não Funcionais:

RNF01: O sistema deve ter mecanismo de acessibilidade.

RNF02: O sistema deve facilitar manutenções futuras através da análise preditiva dos sensores dos maquinários.

RNF03: O sistema deve ser responsivo e multiplataforma.

RNF04: O sistema deve possuir velocidade em seu funcionamento.

User Stories: 

Técnico de Manutenção US01: Visualização de alertas de sensores em tempo real. Como técnico de manutenção, quero receber notificações no meu dispositivo móvel quando um sensor (vibração, som, temperatura) detectar uma anomalia em uma máquina, para que eu possa agir rapidamente antes que ocorra uma falha. Critérios de aceitação: A notificação deve conter o nome da máquina, o tipo de alerta e o nível de urgência. O app deve abrir diretamente na tela a máquina afetada. 

Técnico de Manutenção US02: Registro de ordem de serviço. Como técnico de manutenção, quero registrar o fechamento de uma ordem de serviço, adicionar fotos do reparo e trocar o status da máquina pelo aplicativo, para que o histórico do maquinário esteja sempre atualizado para a equipe de gestão. Critérios de aceitação: Permitir anexar fotos tiradas na hora ou da galeria.

Gestor de Confiabilidade US03: Dashboard de saúde do maquinário. Como engenheiro de confiabilidade, quero visualizar um painel geral com o status de saúde de todo o parque fabril baseado nos dados dos sensores, para que eu possa prever quebras e planejar manutenções preventivas com antecedência. Critérios de aceitação: O dashboard deve exibir indicadores visuais para os níveis de vibração e ruído de cada ativo. O usuário deve conseguir filtrar por setor da fábrica, linha de produção ou criticidade da máquina. 

Gestor de Manutenção US04: configuração de limites de alerta. Como gestor de manutenção, quero configurar os limites toleráveis de vibração, ruído e temperatura para cada máquina, para que o sistema gere alertas automáticos sempre que os parâmetros saírem da normalidade operacional. Critérios de aceitação: Permitir definir limites diferentes para diferentes estados da máquina. Possibilidade de definir múltiplos níveis de alerta.

Administrador do Sistema US05: Gerenciamento de ativos e upload de manuais. Como administrador do sistema, quero cadastrar novas máquinas e fazer o upload de seus respectivos manuais em formato PDF, para que a base de conhecimento e os sensores fiquem vinculados corretamente aos ativos da fábrica. Critérios de aceitação: O sistema deve processar o PDF do manual, indexando o conteúdo automaticamente para a busca.
