OhmMaintenance — Concepção e Escopo do MVP
Plataforma mobile/web voltada para eletricistas, técnicos e engenheiros de campo para coleta, histórico e centralização de medições de instrumentos elétricos.

1. Visão Geral e Proposta de Valor
Nome: OhmMaintenance

Setor: Manutenção Elétrica, Engenharia de Campo e Eletrotécnica.

Descrição: Substitui pranchetas manuais e organiza o histórico de manutenções preventivas/corretivas de quadros, motores e instalações. Aceita medições analógicas e digitais (multímetros, alicates amperímetros, osciloscópios e megômetros).

Proposta de Valor: Centraliza e padroniza o registro rápido de leituras elétricas, gerando rastreabilidade imediata e facilitando diagnósticos de falha sem depender de equipamentos inteligentes caros.

2. Escopo do MVP (In / Out)
Dentro do Escopo (In Scope)
Cadastro de Clientes e Ativos: Cadastro básico de local/cliente e pontos de medição (ex: Quadro QGBT-01, Motor Bomba 02).

Formulário Rápido: Entrada manual de Tensão (V), Corrente (A), Resistência/Isolamento (Ω/MΩ), Temperatura (°C) e Frequência (Hz) + foto do display.

Histórico e Linha do Tempo: Visualização temporal de medições por ativo para identificar variações.

Exportação Simples: Relatório básico em PDF das medições para envio ao cliente.

Fora do Escopo (Out of Scope)
Integrações/Hardware: Conexão Bluetooth/BLE e OCR para leitura de display por IA.

Gestão Financeira: Emissão de NF, cobrança ou controle orçamentário.

CMMS Avançado: Controle de estoque, cálculo de MTBF/MTTR e geolocalização.

3. Requisitos e Histórias de Usuário
RF01 — Cadastro de Ativos: Cadastro hierárquico de clientes e ativos.

US01: Como técnico de campo, quero cadastrar clientes e equipamentos para organizar onde cada medição é realizada.

RF02 — Formulário de Medição: Entrada de grandezas elétricas e foto do display.

US02: Como eletricista, quero inserir rapidamente as leituras no app para eliminar o uso de papel.

US03: Como técnico, quero anexar foto do display como comprovante visual.

RF03 — Histórico e Timeline: Histórico cronológico filtrável por ativo.

US04: Como gestor, quero visualizar o histórico de um motor para identificar tendências de falha.

RF04 — Exportação PDF: Compilação de medições em relatório.

US05: Como engenheiro, quero gerar um PDF com as medições do dia para enviar ao cliente via WhatsApp ou e-mail.

4. Análise de Concorrência
Fluke Connect (Hardware + App): Sincronização Bluetooth e alta confiança, porém limitado ao ecossistema Fluke (alto custo) e sem foco em entrada manual rápida.

Produttivo / Tractian / Keeprun (SaaS / CMMS): Ordens de serviço e relatórios genéricos, mas sem foco específico em grandezas elétricas.

Planilhas + WhatsApp (Solução Informal): Custo zero e flexível, mas gera dados desestruturados e alto risco de perda de informações.

5. Análise SWOT
Pontos Fortes: Foco no nicho elétrico, independência de hardware e interface ágil para campo.

Fraquezas: Necessidade de digitação manual e dependência do engajamento inicial do técnico.

Oportunidades: Relatórios de conformidade/laudos, leitura por OCR no futuro e parcerias com escolas/fabricantes.

Ameaças: Resistência cultural de técnicos à digitalização e concorrência lançando módulos dedicados.

6. Próximos Passos
Validar histórias de usuário com a equipe.

Definir a arquitetura da aplicação e o modelo de dados (MER).

Iniciar a prototipagem de interface e desenvolvimento do MVP.
3. Iniciar o desenvolvimento da interface e prototipagem do MVP.**
