# evento_aws_cloud_bh

Este repositório armazena as fotos tiradas durante o evento AWS Cloud Experience. As imagens foram processadas utilizando o serviço de OCR (Reconhecimento Óptico de Caracteres) AWS Textract.

Posteriormente, foi gerado um resumo em formato Markdown utilizando o agente da CLI do Amazon Q a partir do texto extraído.

## Resumo do Evento

O resumo detalhado do evento, gerado a partir das fotos, pode ser encontrado no seguinte arquivo:

[Resumo Estruturado: AWS Cloud Experience Belo Horizonte](resumo_evento_aws_bh.md)

## Resumo Estruturado: AWS Cloud Experience Belo Horizonte

**Temas Gerais do Evento:** Data Foundation, Analytics, AI/ML & IA Generativa, Modernização de Aplicações para ISVs, Segurança.

---

**Apresentação 1: Estratégia de IA Generativa, Ferramentas e IA Responsável (Palestrante AWS)**

*   **Slides:** 2-10
*   **Resumo:**
    *   Aborda questões executivas chave sobre estratégia de IA Generativa, adoção, regulamentações, modelos específicos de domínio e IA multimodal (Slide 2).
    *   Apresenta o Amazon Bedrock como plataforma para GenAI, cobrindo customização (Knowledge Bases, Fine-tuning), orquestração (Agents, Flows), escolha de modelos (Anthropic, Meta, Cohere, Stability AI, etc.) e opções de inferência (Provisioned, On-demand, Batch) (Slide 3).
    *   Menciona modelos Amazon Nova para geração e compreensão de conteúdo (Slide 4).
    *   Destaca a importância do *data flywheel* para GenAI e lista os principais provedores de modelos (Slide 5).
    *   Lista recursos da AWS para aprendizado e desenvolvimento: AWS DeepRacer, Coursera, AI/ML Scholarship, Machine Learning University, GenAI for Executives (Slide 6).
    *   Enfatiza a questão central para CEOs: "Qual é a nossa estratégia de IA generativa?" (Slide 7).
    *   Discute desafios ("DESAFIOS") em IA: conformidade legal/regulatória, proteção de PI, mitigação de viés, prevenção de mau uso, privacidade, responsabilidade, transparência e alucinações (Slide 9).
    *   Descreve seis passos para construir um programa de IA responsável: apoio da alta administração, equipe diversificada, implementar *guardrails* (cultura, testes, vigilância) (Slide 10).
    *   (Slide 8 parece metafórico, discutindo velocidade, direção e autonomia).
*   **Links/Chamadas para Ação:** Nenhum mencionado explicitamente no texto, mas referencia vários serviços e programas da AWS.

---

**Apresentação 2: Adoção da Nuvem - Do Planejamento à Sustentação (Fernando Sapata, Select Solutions)**

*   **Slides:** 11-13
*   **Resumo:**
    *   Título: "Adotando a nuvem do jeito certo: Do planejamento à sustentação" (Slide 11).
    *   Apresenta o palestrante Fernando Sapata, Diretor de Operações na Select Solutions, membro da AWS Partner Network (Slide 11).
    *   Fornece um histórico da Select Solutions: fundada em 2016, parceria AWS iniciada em 2019, marcos de crescimento, foco em startups e PMEs, competência SaaS (Slide 12).
    *   Destaca o status de Parceiro AWS da Select Solutions e validações de serviço (Slide 13).
*   **Links/Chamadas para Ação:** Nenhum mencionado explicitamente no texto.

---

**Apresentação 3: Panorama da Nuvem 2025 & Fireside Chat (AWS + Convidados)**

*   **Slides:** 14-15
*   **Resumo:**
    *   Título: "Panorama da computação em nuvem para 2025" (Slide 14).
    *   Apresenta um Fireside Chat/Talk Show com:
        *   Bruno Braga (Diretor de TI, Hotmart)
        *   Vitor Mattioli Rolim (Gerente de Tecnologia Data & AI, Inter)
        *   Lara Salvador Geo (Diretora de Inovação, Rede MaterDei de Saúde) (Slide 15).
*   **Links/Chamadas para Ação:** Nenhum mencionado explicitamente no texto.

---

**Apresentação 4: Técnicas de LLM & Observabilidade (Palestrante Datadog)**

*   **Slides:** 16-22
*   **Resumo:**
    *   Explica técnicas de aplicação de LLM usando "cadeias" (*chains*) e "agentes" (*agents*) para dividir tarefas (Slide 16).
    *   Detalha a arquitetura de Geração Aumentada por Recuperação (RAG - *Retrieval-Augmented Generation*) para aumentar as respostas do LLM com dados externos (Slide 17).
    *   Lista desafios com LLMs: Alucinações, qualidade variável, dependências/custos de terceiros, segurança (Slide 18).
    *   Introduz a Observabilidade de LLM com Datadog para entender performance, monitorar operações (latência, tokens, custo) e avaliar qualidade/segurança (vazamentos de PII, injeção de prompt) (Slide 19).
    *   Discute a solução de problemas (*troubleshooting*) de aplicações LLM usando *traces* e métricas do Datadog (Slide 20).
    *   Mostra capacidades de monitoramento para *throughput*, latência e uso de tokens (Slide 21).
    *   Distingue Observabilidade de IA (monitorar sistemas de IA) de AIOps (usar IA para automação de operações de TI), mencionando produtos Datadog (LLM Observability, Watchdog, BitsAI) (Slide 22).
*   **Links/Chamadas para Ação:** Foco implícito nos produtos Datadog.

---

**Apresentação 5: Modernização de Aplicações com Amazon Q (Palestrante AWS)**

*   **Slides:** 23-26
*   **Resumo:**
    *   Tema: "Mantenha, modernize e transforme" com Amazon Q Code Transformation (Slide 23).
    *   Destaca capacidades de transformação: .NET Framework para .NET multi-plataforma em Linux, COBOL em mainframe para Java na AWS, VMware para EC2, upgrades de Java (v8/v11 para v17/v21) (Slide 23).
    *   Mostra o Amazon Q Developer auxiliando em transformações Java (1000 apps, 2 dias, 10 min avg) (Slide 24).
    *   Afirma economias significativas com transformação Java: 4.500 anos de desenvolvimento, $260M anuais (Slide 25).
    *   Resume casos de uso do Amazon Q Developer: eliminar débito técnico, impulsionar produtividade do desenvolvedor (assistência de código, documentação, testes), melhorar segurança/qualidade do código (Slide 26).
*   **Links/Chamadas para Ação:** Foco nas capacidades do Amazon Q.

---

**Apresentação 6: Fundações de Dados para IA Generativa (Lucas Rehem de Azevedo, AWS)**

*   **Slides:** 27-41 (Nota: Slides 39 & 41 parecem idênticos)
*   **Resumo:**
    *   Título: "Arquitetando fundação de dados que potencializam IA Generativa" (Slide 27).
    *   Agenda: Entregar valor com Dados & GenAI, Personalizar, Escalar com segurança, Como começar (Slide 28).
    *   Mostra casos de uso de GenAI em diversas indústrias (Mídia, Saúde, Manufatura, Serviços Financeiros) (Slide 29).
    *   Ilustra os componentes necessários da Fundação de Dados: Armazenamento, Governança, Bancos de Dados, Analytics/Lakes, Integração (Slide 30).
    *   Enfatiza o aproveitamento de arquiteturas de dados existentes (lakes, warehouses, BDs operacionais, streaming) para GenAI (Slide 31).
    *   Apresenta a pilha completa de serviços de Dados & IA da AWS, cobrindo fontes de dados, armazenamento/gerenciamento, governança, ação (Analytics, Search, AI/ML, GenAI) e experiências/personas de usuário (Slides 32, 35).
    *   Destaca perspectivas de CDOs: qualidade dos dados é o desafio nº 1, estratégia de dados ponta-a-ponta é crítica para GenAI (Slide 33).
    *   Define características de uma fundação de dados moderna: Abrangente, Integrada, Governada (Slide 34).
    *   Discute a simplificação da integração de dados com capacidades Zero-ETL entre várias fontes (Aurora, RDS, DynamoDB, etc.) e destinos (Redshift, OpenSearch) (Slide 36).
    *   Descreve os papéis dentro de uma comunidade de dados moderna: Produtores, Equipe de Tecnologia, Consumidores (Slide 37).
    *   Mostra gerenciamento de dados simplificado usando GenAI (Amazon Q) integrado com QuickSight, SageMaker, Glue, DataZone, Redshift (Slide 38).
    *   Fornece passos para iniciar a jornada de GenAI: Seja ágil (selecione caso de uso), Aprenda/Organize (treine equipes), Escale (pessoas, processo, tecnologia) (Slide 40).
    *   Lista recursos para começar: Immersion Days, Professional Services, Partner Network, Innovation Center, Marketplace, etc. (Slide 39/41).
*   **Links/Chamadas para Ação:** Referência a vários serviços e programas da AWS para dados e IA.

---

**Apresentação 7: BI Generativo com Amazon Q no QuickSight (Luiz Yanai, AWS)**

*   **Slides:** 42-52
*   **Resumo:**
    *   Título: "Reimagine a inteligência de negócios com IA generativa" (Slide 42).
    *   Agenda: Oportunidade GenAI para usuários de negócios, Funcionalidades do Amazon Q no QuickSight, Recursos/como começar (Slide 43).
    *   Posiciona o QuickSight como um serviço de BI unificado (dashboards modernos, relatórios *pixel-perfect*, análises embarcadas) (Slide 44).
    *   Contrasta os pontos fortes do BI tradicional com as capacidades da GenAI, introduzindo o "BI Generativo" (Slide 45).
    *   Apresenta o Amazon Q no QuickSight como um assistente de dados alimentado por IA (Slide 46).
    *   Destaca recursos do Q no QuickSight: criação de dashboards assistida por IA, resumos executivos/Q&A, *storytelling* de dados, embarcar recursos GenAI em apps customizados (Slides 47, 50).
    *   Discute a evolução do BI em direção ao "BI GENERATIVA" para maior acessibilidade (Slide 49).
    *   Fornece recursos: Informações sobre Amazon Q no QuickSight, Comunidade QuickSight (Slide 52).
*   **Links/Chamadas para Ação:** Chamada para experimentar o QuickSight gratuitamente por 30 dias (Slide 51), links/info para Q no QuickSight e Comunidade (Slide 52).

---

**Apresentação 8: GenAI & ML No-Code com SageMaker Canvas (Cristiano Scandura, AWS)**

*   **Slides:** 53-77
*   **Resumo:**
    *   Título: "Acelere a inovação com IA generativa e machine learning sem código" (Slide 53).
    *   Explica como o SageMaker Canvas capacita equipes acelerando fluxos de trabalho e habilitando usuários de negócios (Slide 54).
    *   Aborda desafios na inovação com ML/GenAI: demanda por especialistas, necessidade de habilidades técnicas, colaboração necessária (Slide 55).
    *   Apresenta recursos do SageMaker Canvas: modelos prontos (incluindo FMs via Bedrock/JumpStart), construção ponta-a-ponta sem código, colaboração via Studio/QuickSight (Slide 56).
    *   Mostra aplicações do Canvas em diferentes tipos de problemas: GenAI, Tabular, Séries Temporais, CV, NLP (Slide 57).
    *   Detalha o ciclo de vida de ML sem código no Canvas:
        *   Preparar Dados: +50 conectores, visualização de pipeline, insights de ML, +300 transformações, interação em linguagem natural (Slides 58-64).
        *   Treinar e Avaliar Modelos: Construir modelos (regressão, classificação, previsão, fine-tuning de FM), usar AutoML ou selecionar algoritmos, analisar métricas (Slides 65-67).
        *   Customizar Modelos de Fundação: Selecionar de Bedrock/JumpStart, aplicar RAG/fine-tuning, avaliar modelos (Slides 68-69).
        *   Gerar Previsões: Previsões no app, análise *what-if*, automatizar previsões em lote, deploy com um clique, compartilhar com QuickSight (Slides 70-73).
    *   Discute colaboração e deploy: pipelines MLOps, SageMaker Model Registry (Slide 74).
    *   Inclui slides específicos sobre construção de modelos de Séries Temporais, enfatizando equilíbrio e variáveis relacionadas (Slides 75-76).
    *   Fornece links para recursos do SageMaker Canvas e posts de blog (Slide 77).
*   **Links/Chamadas para Ação:** Links/info para SageMaker Canvas e posts de blog (Slide 77).

---

**Apresentação 9: Escalando GenAI com Bedrock Multi-Agents (Renan Lima, AWS)**

*   **Slides:** 78-107
*   **Resumo:**
    *   Título: "Escalando IA Generativa com Bedrock Multi-Agents" (Slide 78).
    *   Apresenta recursos do Amazon Bedrock: escolha de FM, customização, ferramentas GenAI (RAG, Guardrails, Flows, Agents), segurança (Slide 79).
    *   Define Agentes GenAI como sistemas autônomos que planejam, raciocinam, agem, usando dados corporativos e ferramentas (Slide 80).
    *   Fornece contexto e casos de uso para agentes (processamento de sinistros, CX, marketing, análise de causa raiz) (Slide 81).
    *   Destaca necessidades dos clientes: automatizar fluxos de trabalho, mover mais rápido, encontrar soluções robustas/escaláveis (Slide 83).
    *   Lista blocos de construção de Agentes Bedrock: escolha de FM, memória/KBs/Guardrails, ferramentas/ações, observabilidade, colaboração multi-agente (Slide 84).
    *   Foca nos benefícios da colaboração multi-agente: resolução de problemas complexos, desenvolvimento mais rápido, confiança/segurança (Slide 85).
    *   Ilustra a evolução do agente: começar simples, expandir capacidades (Slides 86-88).
    *   Alerta contra agentes monolíticos, listando desafios: complexidade, confusão, custo/latência (Slides 89-90).
    *   Demonstra como múltiplos agentes especializados, orquestrados por um supervisor, lidam com tarefas de forma mais eficaz (exemplos de RH: férias, licenças, promoção) (Slides 91-93).
    *   Aborda limitações de agentes isolados e introduz capacidades de colaboração multi-agente do Bedrock (roteamento, planejamento, observabilidade, segurança) (Slides 94-95).
    *   Destaca duas oportunidades principais: Unificar a experiência do cliente e Automatizar processos complexos (Slide 96).
    *   Explica o roteamento do agente supervisor baseado em classificação de intenção e descrições de colaboração (Slides 97-100).
    *   Mostra automação de processos complexos usando um agente supervisor orquestrando múltiplos especialistas para uma tarefa de estratégia de marketing (Slides 101-103).
    *   Apresenta um caso de uso de assistente bancário com um supervisor orquestrando agentes de finanças, empréstimos, hipotecas e títulos (Slides 104-106).
*   **Links/Chamadas para Ação:** Chamada para experimentar a colaboração multi-agente do Bedrock, lista exemplos, pede feedback (Slide 107).

---

**Apresentação 10: Segurança em IA Generativa (Matheus Anderle de Souza, AWS)**

*   **Slides:** 108-111, 113-115, 117-121, 123-126, 127-133 (Nota: Slide 112 ausente, 120/121 duplicado)
*   **Resumo:**
    *   Título: "A abordagem da AWS para proteger a IA generativa" (Slide 108).
    *   Agenda: Uso seguro de IA, Segurança do Amazon Q, Fluxo de dados/ferramentas de proteção (Slide 109).
    *   Reconhece que GenAI traz inovação mas também novos riscos/desafios (Slide 110).
    *   Define dimensões da responsabilidade em IA: Proteção, Controlabilidade, Explicabilidade, Equidade, Privacidade/Segurança, Veracidade/Robustez, Governança, Transparência (Slide 111).
    *   Detalha responsabilidade em Proteção (segurança, alinhamento, gerenciamento de risco probabilístico com ferramentas como Guardrails) e Segurança (prevenir acesso não autorizado, usar controles determinísticos, filtrar dados *antes* do FM) (Slide 113).
    *   Lista diretrizes de segurança em Governança, Conformidade/Privacidade, Controles, Gerenciamento de Risco, Resiliência (Slide 114).
    *   Apresenta o Amazon Q Business como um assistente GenAI seguro e pronto para empresas (Slides 115-116).
    *   Detalha recursos de segurança do Q Business (PrivateLink, guardrails, IAM Identity Center, CloudTrail, FIPS) e privacidade/governança de dados (dados do cliente não usados para treino, armazenamento regional, criptografia) (Slides 117-118).
    *   Mostra recursos da UI do Q Business que apoiam a confiança (contexto, referências de fontes, histórico) (Slide 119).
    *   Reitera benefícios do Bedrock, enfatizando segurança/privacidade (Slides 120-121).
    *   Detalha segurança/privacidade de dados do Bedrock: nenhum dado do cliente para treino de FM, criptografia, PrivateLink, criptografia com chave do cliente para modelos fine-tuned, integração IAM/GuardDuty, suporte GDPR/HIPAA/PCI (Slide 123).
    *   Ilustra fluxos de dados do Bedrock entre conta do cliente, serviço Bedrock, contas de deploy e staging de modelos (Slides 124-126).
    *   Revisa técnicas para usar dados empresariais com segurança: RAG, Agentes IA, Customização de Modelo (Slide 127).
    *   Recomenda limitar acesso usando princípios Zero Trust e ferramentas AWS IAM (Identity Center, Access Analyzer, Verified Permissions, Verified Access) (Slide 128).
    *   Enfatiza identidade/segurança integradas, autorizando acesso em múltiplos pontos (app, agente, KB, ferramentas) (Slide 129).
    *   Detalha capacidades do Amazon Bedrock Guardrails: avaliar prompts/respostas, configurar filtros (conteúdo nocivo, PII, tópicos negados), filtrar alucinações (Slides 130-131).
    *   Mostra a pilha GenAI geral na AWS, da infraestrutura às aplicações (Slide 132).
    *   Slide final "OBRIGADO" (Slide 133).
*   **Links/Chamadas para Ação:** Nenhum mencionado explicitamente no texto, mas referencia vários serviços e recursos de segurança da AWS.

--- 