# PLANO — DICA 2 · Implantar, Capacitar e Acompanhar (v7.2)

Curso 2 de 2 da **Formação DICA** (Diagnosticar, Implantar, Capacitar, Acompanhar). O DICA 1 (`formacao-dica-diagnostico-v72`) entrega o mapa de oportunidades da Clínica Vila Serena; este curso pega a recomendação e leva até o assistente andar sozinho. Papel do Profissional 2030: **Consultor**, recorte pequeno negócio.

Empresa do curso: **Clínica Vila Serena (fictícia)**, fisioterapia e estética, 9 pessoas, a dona atende e administra, recepção pelo WhatsApp. Segundo caso: **Imobiliária Ponto Firme (fictícia)**, 4 corretores. Rotuladas como fictícias em toda aparição.

Fonte: `~/projetos/mapacliente` trilhas 4, 5 e 6 (só leitura), atualizada conforme [ATUALIZACAO.md](ATUALIZACAO.md). Regras: sem promessa de renda, sem valor em R$, sem número sem fonte (critério numérico só como "regra combinada" em branco), sem ferramenta ou modelo fixo, sem conector não oficial do WhatsApp, LGPD onde há dado pessoal.

## As 8 aulas

| # | slug | aula | objetivo (≤ 160) | diagrama | prática ("pronto quando") | fonte |
|---|---|---|---|---|---|---|
| 1 | `primeiro-assistente` | O primeiro assistente: 3 critérios e o que não escolher | escolher o primeiro assistente pelos 3 critérios, escrever o que ele não faz e combinar a métrica de 30 dias e o plano de desligar. | 5 candidatas → alta dor → baixo risco → escopo claro → canal oficial → escolhido | ficha de 1 página do primeiro assistente: faz / não faz / métrica observável de 30 dias / caminho para humano / plano de desligar | 4.1; F1–F4 |
| 2 | `playbook` | O playbook operacional: 7 partes, exemplos resolvidos e saída fixa | escrever o playbook da recepção nas 7 partes, com 3 exemplos resolvidos, formato de saída fixo e versão no topo. | 7 partes (contexto, objetivo, entradas, regras, exemplos, saída, limites) + histórico | playbook v1.0 da recepção com as 7 partes, 3 exemplos (simples, difícil, devolve para humano), saída com campos nomeados e histórico | 4.2 |
| 3 | `tres-fases` | Aprovação em 3 fases no pequeno negócio | ligar o assistente na fase 1, escrever com a dona o que é "importante" e combinar por escrito quando sobe e quando volta de fase. | escada: fase 1 aprova tudo → fase 2 aprova o importante → fase 3 só exceção (volta) | quadro das 3 fases da clínica + tabela do "importante" + regra de subir e de voltar escrita e marcada como regra do consultor; **simconversa** "a dona quer pular para a fase 3" | 4.3, 5.3 |
| 4 | `construir` | Construir sem virar fábrica: kit aberto, no-code ou nada | decidir entre kit aberto, fluxo no-code ou nada para o assistente escolhido e testar 15 casos antes de ligar. | pergunta → nada resolve? → kit aberto serve? → no-code → 15 casos → liga | decisão escrita (caminho, motivo, o que fica de fora) + bateria de 15 casos com resposta esperada e resultado | 4.4, 4.5; F6; vídeo "Consultoria de IA na prática" |
| 5 | `capacitar` | Capacitar: a dona, o campeão interno e o treino de 90 minutos | escolher o campeão interno, conduzir o treino de 90 minutos e deixar o manual de 1 página e o registro de dúvidas funcionando. | campeão → papéis → treino 90 min (3 terços) → manual → registro de dúvidas | roteiro do treino + manual de 1 página + registro de dúvidas com 3 linhas + folha de papéis | 5.1, 5.2 |
| 6 | `acompanhar` | Acompanhar: check-in de 20 minutos, 5 indicadores, 3 alertas | conduzir o check-in de 20 minutos, medir 5 indicadores contra a linha de base e reagir aos 3 alertas. | ciclo semanal: registro → 5 números → check-in → 1 ajuste → relatório (volta) + cadência | pauta de 20 min + planilha dos 5 indicadores com linha de base + relatório de 1 página de 4 semanas simuladas | 5.3 |
| 7 | `manter` | Manter e padronizar: manutenção, próxima área e biblioteca por nicho | escrever o escopo de manutenção sem preço, montar o mapa de 12 meses da clínica e passar o checklist antes de entregar. | frente única (diagnóstico) × bastidor padrão (biblioteca) → mapa de 12 meses | escopo de manutenção (inclui/não inclui) + mapa de 12 meses + checklist pré-entrega preenchido | 5.4, 6.1; vídeo "De construtor a consultor" |
| 8 | `projeto-final` | Projeto final: DICA de ponta a ponta na Clínica Vila Serena | montar o dossiê DICA da Clínica Vila Serena, avaliar pela rubrica e gerar o plano de 90 dias com datas. | dossiê: diagnóstico → playbook → fases → treino → 4 check-ins → plano | dossiê com as 6 peças, rubrica com nota ≥ 3 em todos os critérios, plano do gerador | 6.4; prof2030-consultor a8 |

A aula 8 fecha com `mapa` (4 degraus: escolher, playbook e fases, treinar, acompanhar) + `gerador` (plano de 90 dias com os exercícios das aulas).

## simconversa da aula 3 — "a dona quer pular para a fase 3"

Personagem: Renata, dona da Clínica Vila Serena (fictícia). Semana 2 da fase 1. Ensina, da fonte 4.3: dado antes de opinião, porta de volta, risco alto nunca sai da fase 1, a tabela do "importante" feita com a dona, quem decide é a dona.

Caminho melhor = 3 falas × 2 = 6 pontos. Desvios com nota baixa (lição do placar).

## Decisões
- simfila não entra na aula 6: a fila de aprovação não é fila de tarefas com interromper e retomar.
- Vídeos: só os publicados no GitHub (consultoria-ia-na-pratica v2 na aula 4, consultor-ia-2027 v2 na aula 7), com EN/ES declarados.
- Números da fonte que viram "regra combinada": aparecem como lacuna `[número combinado]` nos modelos.
