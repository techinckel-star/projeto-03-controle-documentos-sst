# Protocolo de Automação — Controle de Documentos de SST

## Objetivo

Analisar os documentos fictícios de Segurança do Trabalho, controlar datas de vencimento, identificar pendências e auxiliar no acompanhamento dos riscos ocupacionais relacionados à NR-1.

## Arquivos de entrada

- `apoio/documentos_ficticios.md`
- `apoio/criterios_acompanhamento.md`

## Instruções para a IA

1. Leia integralmente os arquivos de entrada.

2. Utilize a data de referência informada nos documentos para analisar os vencimentos.

3. Organize os documentos em uma tabela contendo:
   - Nome do documento;
   - Data de emissão;
   - Data de vencimento ou revisão prevista;
   - Situação identificada;
   - Pendência;
   - Providência recomendada;
   - Responsável pelo acompanhamento.

4. Identifique documentos vencidos, próximos do vencimento ou que precisam de confirmação de vigência.

5. Não classifique como vencido um documento cuja data de validade não tenha sido informada.

6. Analise as informações fornecidas sobre mudanças nos ambientes, nas atividades e nos processos de trabalho.

7. Sinalize situações que possam exigir revisão do PGR ou nova avaliação dos riscos ocupacionais.

8. Indique as pendências que precisam ser encaminhadas à clínica ocupacional, à empresa responsável pelos laudos ou à profissional de Segurança do Trabalho.

9. Não invente informações, datas, prazos legais ou resultados de avaliações técnicas.

10. Quando faltarem dados, registre a informação como pendente de confirmação.

## Formato da saída

Gere um relatório em Markdown com as seguintes seções:

1. Resumo das pendências.
2. Tabela de controle dos documentos.
3. Pontos de atenção relacionados aos riscos ocupacionais.
4. Providências recomendadas.
5. Informações que precisam ser confirmadas.
6. Observação sobre a necessidade de conferência humana.

Salve o resultado em:

`saida/relatorios/relatorio_controle.md`

## Verificação final

Antes de concluir, confira se as datas foram interpretadas corretamente, se as informações estão de acordo com os arquivos de entrada e se nenhuma informação foi inventada.

O relatório deverá servir como ferramenta de apoio, sem substituir a avaliação da profissional responsável.