# MVP Conceitual — IA Pronta | Diagnóstico de IA para pequenas empresas

**Integrantes do grupo:**

| Nome completo | Registro Acadêmico (RA) |
|---|---|
| Ana Paula Lopes Travassos | 2026108913 |
| Rhuan Ryuji Yui Isozaki | 2026105656 |
| Marcelo Martins Araujo Junior | 2026108269 |
| Luiz Gustavo da Silveira | 2026103979 |


> **Status:** protótipo conceitual, **não funcional**. Todos os preços, custos e resultados deste MVP são **premissas ilustrativas do grupo**, não cotações nem resultados reais das entrevistas.

## 1. Problema e oportunidade

As entrevistas mostram que a adoção empresarial de IA depende de dados confiáveis, integrações, conhecimento técnico, segurança e avaliação financeira. Muitas pequenas empresas não dispõem de equipe ou orçamento para começar com uma consultoria ampla. A lacuna proposta é a falta de uma **avaliação rápida, acessível e orientada a ROI** que recomende por onde iniciar, com governança e revisão humana.

## 2. Proposta de valor

O **IA Pronta** transforma planilhas simples, dados de processos e um questionário em um **diagnóstico de prontidão digital**, uma lista priorizada de casos de uso de IA e uma **simulação de custos versus benefícios**. A pessoa responsável aprova qualquer recomendação antes da execução. Não se trata de substituir consultorias empresariais, mas de criar uma etapa de triagem e aprendizagem antes de projetos maiores.

## 3. Público-alvo e modelo de negócio

- **Público-alvo:** pequenas e médias empresas de varejo, serviços e escritórios, começando por operações de 5 a 50 colaboradores.
- **Decisor:** dono, gerente operacional, analista administrativo ou consultor de transformação digital.
- **Modelo:** B2B SaaS, plano de referência **R$ 299/mês** por empresa e onboarding de referência **R$ 600** (premissas para exercício; não há precificação validada).
- **Parcerias:** consultorias e empresas de integração poderiam executar projetos aprofundados mediante novo contrato, sem conexão comercial pressuposta com entrevistadas.

## 4. Funcionalidades essenciais

1. Questionário de contexto, objetivo e indicadores atuais (sem enviar dados pessoais desnecessários).
2. Importação de dados estruturados **anonimizados** em CSV e diagnóstico de faltas, duplicidades e inconsistências.
3. Motor de priorização de oportunidades de IA: **impacto potencial × prontidão dos dados × risco × esforço**.
4. Calculadora de ROI com premissas editáveis, sem prometer ganho automático.
5. Relatório executivo (problema, oportunidade, riscos, custo, prazo, responsável e etapas sugeridas).
6. Aprovação humana obrigatória antes de qualquer ação ou integração; histórico de revisões.

## 5. Como a IA é aplicada

Um modelo de linguagem transforma descrições de processos em hipóteses de automação e explicações; algoritmos convencionais calculam qualidade dos dados e projeções financeiras; uma camada de regras evita projetos de alto risco sem revisão humana. As recomendações devem citar os dados de origem, apresentar incerteza e permitir correção. **Nenhum dado é enviado automaticamente a serviços externos no protótipo conceitual.**

## 6. Representação visual

Ver [`prototipo_ia_pronta.svg`](prototipo_ia_pronta.svg): tela demonstrativa com painel de diagnóstico, oportunidade prioritária, economia **hipotética** de tempo e botão de revisão humana. O SVG é a representação visual; nenhuma funcionalidade de IA real foi implementada.

## 7. Hipótese de validação

**Hipótese central:** gerentes de PMEs conseguem identificar um primeiro caso de uso de IA com custo-benefício plausível e entender as recomendações sem apoio técnico intenso.

- **Amostra-piloto:** 5 empresas voluntárias, usando dados fictícios/anonimizados.
- **Teste:** apresentar a jornada e um relatório simulado; comparar diagnóstico manual versus protótipo; avaliar compreensão e intenção de uso.
- **Critérios propostos de sucesso:** pelo menos 4/5 relatam clareza e utilidade; pelo menos 3/5 indicam intenção de piloto; ganho de tempo potencial estimado de 20% em uma tarefa específica, **a ser medido**, não presumido como fato.
- **Guardrails:** não processar dados pessoais/sensíveis sem fundamento legal e medidas adequadas, nem permitir decisão operacional automática irreversível.

## 8. Viabilidade econômica preliminar — premissas simuladas

### Perspectiva de quem opera o IA Pronta

| Indicador | Premissa | Cálculo |
|---|---:|---|
| Construção do piloto (valor único) | R$ 12.000 | UX + desenvolvimento + testes + segurança |
| Custos mensais fixos | R$ 2.000 | nuvem, manutenção leve, monitoramento e suporte limitado |
| Custo variável por empresa/mês | R$ 35 | consumo de IA e processamento (hipótese) |
| Receita mensal por empresa | R$ 299 | plano simulado |
| Margem de contribuição | R$ 264/empresa | 299 − 35 |
| Ponto de equilíbrio operacional | **8 empresas** | arredondamento acima de 2.000 ÷ 264 |
| Operação com 20 clientes | **R$ 3.280/mês** | 20 × (299 − 35) − 2.000 |

**Limites da simulação:** não inclui salários integrais dos fundadores, tributos, inadimplência, comissão de pagamento, marketing, CAC e todos os custos jurídicos. Por isso, o resultado é **margem operacional simplificada, não lucro líquido ou projeção de retorno garantido**. R$ 12 mil inicial só seriam recuperados em aproximadamente 3,7 meses **depois** de atingir e sustentar 20 clientes, ignorando demais custos e tempo de aquisição.

### Perspectiva de um cliente hipotético

| Indicador | Premissa |
|---|---:|
| Tempo economizado se a automação realmente funcionar | 20 h/mês |
| Custo-hora para simular benefício | R$ 35/h |
| Benefício mensal estimado | R$ 700 |
| Assinatura mensal | R$ 299 |
| Benefício líquido mensal recorrente | **R$ 401** |
| Onboarding único | R$ 600 |
| Prazo de retorno do onboarding | **~1,5 mês** (600 ÷ 401) |
| ROI hipotético de 12 meses | **~100,6%**: (8.400 − 4.188) ÷ 4.188 |

A economia de 20 h é **hipótese a validar**. Valorizar horas liberadas como ganho econômico pressupõe que possam ser efetivamente realocadas ou traduzidas em custos evitados. Uma economia de tempo não equivale automaticamente a aumento de caixa.

## 9. Diferencial frente aos casos

A Semantix, a Digibee e a AGR focam integração, agentes e inteligência empresarial em projetos estruturados; a CPTM exemplifica eficiência com dados operacionais; o CEIA demonstra pesquisa de ponta; o CapCut acessibilidade de IA para criação. **IA Pronta** propõe a camada inicial de *diagnóstico, priorização e análise econômica* para empresas com menos estrutura. Isso é uma oportunidade **inferida**, não lacuna confirmada por todas as entrevistas.

## 10. Fontes

- UFG — Projeto SOFIA: https://jornal.ufg.br/n/187223-a-inteligencia-artificial-que-promete-nos-fazer-sentir-aromas
- CEIA — Monitoramento em saúde mental: https://ceia.ufg.br/algoritmos-inteligentes-para-apoio-ao-monitoramento-remoto-de-saude-mental/
- Semantix — Plataforma empresarial: https://semantix.ai/pt/
- Digibee — Digital Workers: https://www.digibee.com/pt-br
- Digibee — Aporte Série B 2023: https://www.digibee.com/news/digibee-receives-series-b-funding-in-2023
- CPTM — Estudo de agentes em falhas: https://semanadetecnologia.com.br/31semana/files/artigos/981_artigo_iaemdiagnosticodefalhas.pdf
- AGR Tech — Soluções: https://agrconsultores.com.br/agr-tech/
- Flip by AGR — Apresentação: https://pt.linkedin.com/posts/flip-agr_o-flip-aprende-o-jeito-da-sua-empresa-activity-7519397934350823424-xfAq
- CapCut — IA Design: https://www.capcut.com/pt-br/tools/ai-design
