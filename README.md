# Caderno Temático - QA - Quality Assurance

## Objetivo: 

Caderno criado com o objetivo de me auxiliar no início dos estudos na área de QA, por motivos pessoais de interesse e também profissionais, possívelmente.

Buscando compreender os principios iniciais e centrais do tema para prosseguir nos estudos:

- Conceitos básicos e fundamentais
- Tipos de teste
- Documentação de testes
- Técnicas de testes
- Ferramentas iniciais


## Fontes Listadas

Obs: Listei apenas 5 fontes, porém utilizei mais já que farei uso do caderno para estudos.

- https://roadmap.sh/qa
- https://www.guru99.com/manual-testing.html
- https://www.alura.com.br/artigos/quality-assurance
- http://softdesign.com.br/blog/ferramentas-de-teste-de-software/
- https://www.guru99.com/all-about-quality-assurance.html


## Prompts

Prompt 1 - Como estudante de ADS, sem conhecimento prévio em QA e com básico conhecimento em Python, Java, JS, React. Com grande interesse em trabalhar com Back-end, QA e IA, crie um guia de estudos por tópicos e subtópicos para que eu possa seguir

Resposta NotebookLM 1 - Com base nos seus conhecimentos em ADS e seu interesse em Back-end, QA e IA, aqui está um guia de estudos estruturado para consolidar sua transição para a área de qualidade de software de forma estratégica:
1. Fundamentos de Quality Assurance (QA)
Antes de automatizar, você deve entender a teoria e os processos que regem a qualidade.
Conceitos Iniciais:
O que é QA (Garantia de Qualidade) focado em processos e prevenção
.
Diferença entre QA e QC (Controle de Qualidade), que é reativo e foca na detecção de defeitos no produto final
.
O ciclo PDCA (Plan, Do, Check, Act) como base para melhoria contínua
.
Metodologias de Desenvolvimento:
Diferenças entre o modelo Waterfall (Cascata) e o Agile Testing
.
O papel do QA em times ágeis (Scrum/Kanban) e a mentalidade de que "qualidade é responsabilidade de todos"
.
Manifesto do Teste Ágil: testar continuamente e prevenir defeitos em vez de apenas encontrá-los
.
2. Tipos, Níveis e Técnicas de Teste
Essencial para saber o que testar e como abordar cada parte do sistema.
Técnicas de Visibilidade:
Caixa Preta: Foco em requisitos funcionais (entradas e saídas)
.
Caixa Branca: Teste da lógica interna e estrutura do código fonte (aproveite sua base em Java/Python)
.
Caixa Cinza: Abordagem híbrida
.
Níveis de Teste:
Unitário: Teste de componentes isolados (funções/métodos)
.
Integração: Validação da comunicação entre módulos e APIs
.
Sistema: Avaliação do software completo e integrado
.
Aceitação (UAT): Validação final com base nos requisitos do cliente
.
Testes Não-Funcionais:
Performance: Testes de carga e stress para medir estabilidade sob carga
.
Segurança: Busca por vulnerabilidades e riscos de dados
.
Usabilidade: Foco na experiência e intuitividade para o usuário
.
3. Documentação e Gestão de Testes
Aprender a organizar seu trabalho de forma profissional.
Artefatos de Teste:
Criação de Planos de Teste (escopo, recursos e cronograma)
.
Diferença entre Cenários de Teste (o que testar) e Casos de Teste (passo a passo detalhado)
.
Gestão de Defeitos:
Como relatar bugs com clareza (passos para reproduzir, resultados esperados vs. atuais)
.
Priorização de casos de teste com base em risco e impacto no negócio
.
4. QA Focado em Back-end e Automação (Hard Skills)
Como você já tem bases em linguagens de programação, este será seu maior diferencial.
Testes de API (Crucial para Back-end):
Uso de ferramentas como Postman ou Insomnia para validações manuais e repetíveis
.
Automação de APIs com RestAssured (Java) ou bibliotecas equivalentes em Python/JS
.
Banco de Dados: Realização de consultas SQL para validar a persistência e integridade dos dados testados
.
Frameworks de Automação Web/Mobile:
Selenium: Versátil e suporta Java, Python e JS
.
Cypress ou Playwright: Execução rápida e moderna em navegadores (ideal para quem já conhece JS/React)
.
CI/CD e DevOps: Integração de testes automatizados em pipelines (Jenkins, GitLab CI, GitHub Actions) para garantir entregas contínuas
.
5. Inteligência Artificial em QA
Seu interesse em IA pode ser aplicado para modernizar os processos de teste.
IA para Automação: Ferramentas que utilizam IA para orquestração de testes e geração automática de casos
.
Predição de Defeitos: Uso de Machine Learning para analisar dados históricos e identificar módulos do código com maior risco de falha
.
Otimização: Uso de modelos de IA para reduzir redundâncias em suítes de teste e otimizar a cobertura
.
6. Próximos Passos e Carreira
Certificações: Estude para a ISTQB Foundation Level (CTFL), que é o padrão global para profissionais da área
.
Portfólio: Documente seus scripts de automação e projetos de teste no GitHub
.
Especialização: Considere cursos focados em Testes Ágeis para alinhar técnica com as necessidades do mercado moderno
.

Prompt 2 - Liste os tipos de testes, diferenças entre eles e pontos negativos e positivos de cada um deles.

Resposta NotebookLM 2 - Os testes de software são classificados de diversas formas, dependendo do objetivo, do nível de visibilidade do código ou da fase do desenvolvimento. De acordo com as fontes, aqui estão os principais tipos, suas diferenças e os respectivos pontos positivos e negativos:
1. Classificação por Visibilidade (Técnicas de Caixa)
Esta categoria define o quanto o testador conhece da estrutura interna (código) do sistema.
Teste de Caixa Preta (Black Box): Foca apenas nas entradas e saídas, validando os requisitos funcionais sem conhecimento do código interno
.
Positivo: Reflete a visão real do usuário final e não exige conhecimento em programação
.
Negativo: Existe a possibilidade de deixar caminhos lógicos do código sem cobertura
.
Teste de Caixa Branca (White Box): Avalia a estrutura interna, lógica e fluxos de dados do código-fonte
.
Positivo: Garante que todos os caminhos, loops e condições do código sejam validados
.
Negativo: Exige alto conhecimento técnico e acesso total ao código
.
Teste de Caixa Cinza (Grey Box): Uma abordagem híbrida onde o testador tem conhecimento parcial da estrutura interna (como bancos de dados ou arquitetura), mas executa os testes pela perspectiva do usuário
.
Positivo: Equilibra a validação funcional com a estrutural, sendo ideal para testes de integração e APIs
.
2. Testes Funcionais (O que o sistema faz)
Verificam se as operações e ações do software funcionam conforme os requisitos especificados
.
Teste de Unidade (Unit Testing): Valida as menores partes isoladas do código, como funções ou métodos
.
Positivo: Detecta erros muito cedo, quando a correção é mais barata
.
Negativo: Não garante que as unidades funcionarão bem quando integradas
.
Teste de Integração: Verifica a comunicação e o fluxo de dados entre diferentes módulos ou serviços que já foram aprovados individualmente
.
Positivo: Identifica incompatibilidades de interface e erros de comunicação entre partes do sistema
.
Teste de Sistema: Examina o software completo e integrado para garantir que ele atenda a todos os requisitos especificados
.
Teste de Aceitação (UAT): Realizado geralmente por usuários finais para confirmar se o produto está pronto para entrega e atende às expectativas do negócio
.
Teste de Regressão: Re-executa testes em funcionalidades existentes para garantir que novas mudanças ou correções não quebraram o que já estava funcionando
.
Positivo: Oferece confiança para lançar atualizações frequentes
.
Negativo: Pode se tornar muito repetitivo e demorado se for feito apenas manualmente
.
Smoke e Sanity Testing: O Smoke é um teste rápido para checar se as funções básicas operam após um novo build
. O Sanity foca em verificar uma correção específica ou mudança pontual
.
3. Testes Não-Funcionais (Como o sistema funciona)
Validam atributos de qualidade como desempenho, segurança e usabilidade sob certas condições
.
Teste de Desempenho (Performance): Avalia a velocidade, estabilidade e eficiência sob carga
.
Teste de Carga (Load): Simula o uso por muitos usuários simultâneos para ver se o sistema aguenta o tráfego esperado
.
Teste de Stress: Leva o software ao limite para identificar o ponto exato em que ele falha
.
Teste de Usabilidade: Analisa o quanto o sistema é amigável e intuitivo para o usuário final
.
Positivo: Identifica dificuldades de navegação e design que ferramentas automáticas não percebem
.
Teste de Segurança: Busca brechas, vulnerabilidades e falhas na proteção de dados e autenticação
.
4. Execução: Manual vs. Automatizado
Uma das diferenças fundamentais está no modo de execução.
Teste Manual: Executado por um humano interagindo com a aplicação
.
Prós: Essencial para avaliar a experiência do usuário (UX), adaptável a mudanças rápidas e ideal para testes exploratórios
.
Contras: Lento, cansativo para o executor e propenso a falhas humanas em tarefas repetitivas
.
Teste Automatizado: Utiliza scripts e ferramentas para executar casos de teste de forma autônoma
.
Prós: Extremamente rápido para testes de regressão, permite maior cobertura e execução frequente em pipelines de CI/CD
.
Contras: Exige conhecimento em programação, tem alto custo inicial e não substitui o julgamento humano em usabilidade
.

Prompt 3 - Qual a diferença de QA e QC, não apenas na teoria mas também na prática do dia-a-dia da profissão?

Resposta NotebookLM 3 - A diferença entre Quality Assurance (QA) e Quality Control (QC) reside fundamentalmente no foco da atuação: enquanto um se preocupa em prevenir que os problemas ocorram através da melhoria de processos, o outro foca em detectar falhas no produto final antes que ele chegue ao cliente
.
Aqui estão as distinções detalhadas, separando a teoria da realidade prática do cotidiano profissional:
1. Diferenças Teóricas
Teoricamente, as duas áreas são complementares, mas possuem objetivos e momentos de atuação distintos:
Característica
Quality Assurance (QA)
Quality Control (QC)
Foco
Processo: Garante que os métodos de criação sejam eficazes
.
Produto: Examina a qualidade do resultado final
.
Abordagem
Proativa: Atua para prevenir o surgimento de defeitos
.
Reativa: Atua para identificar e corrigir defeitos existentes
.
Momento
Ao longo de todo o ciclo de vida do software
.
Geralmente após a conclusão de uma funcionalidade ou do produto
.
Objetivo
Garantir que a qualidade seja "construída" no produto
.
Garantir que o produto atenda aos requisitos técnicos especificados
.
2. A Prática no Dia a Dia da Profissão
Na prática do mercado atual, especialmente em times ágeis, os papéis muitas vezes se sobrepõem sob a figura da "pessoa de QA", mas as atividades diárias se dividem claramente:
O dia a dia em QA (Processos e Prevenção)
O profissional atua de forma estratégica para evitar retrabalho e custos exponenciais de correção tardia
.
Definição de Padrões: Estabelece diretrizes, melhores práticas de codificação e critérios de aceitação para o time
.
Planejamento de Testes: Elabora a estratégia macro de como o sistema será validado, identificando riscos antecipadamente
.
Melhoria Contínua (PDCA): Utiliza o ciclo Plan-Do-Check-Act para avaliar se os processos atuais estão gerando muitos bugs e como otimizá-los
.
Treinamento e Auditoria: Orienta o time sobre padrões de qualidade e realiza auditorias para garantir que as normas da empresa (como ISO 9000) sejam seguidas
.
O dia a dia em QC (Execução e Verificação)
O profissional atua diretamente com o "teclado", verificando se o que foi desenvolvido realmente funciona
.
Execução de Testes: Realiza testes manuais e automatizados para validar entradas e saídas do sistema
.
Gestão de Defeitos: Identifica bugs, elabora relatórios detalhados para os desenvolvedores e retesta as correções (testes de regressão)
.
Inspeções e Walkthroughs: Participa de revisões técnicas do produto pronto para garantir que ele não quebre em produção
.
Monitoramento: Verifica o comportamento do software em ambientes de teste (staging) ou produção para garantir estabilidade imediata
.
3. A Realidade nos Times Modernos
Atualmente, a distinção clássica é menos rígida devido à adoção do Agile Testing
.
QA como Facilitador: O profissional de QA hoje não é apenas um "caçador de bugs" (QC), mas um mentor que ajuda desenvolvedores a escreverem melhores testes unitários e a adotarem práticas como TDD e BDD
.
Shift-Left: A tendência é trazer o QA para o início do projeto. Se o QA atua apenas como QC no final do processo, ele se torna uma "contenção de danos", o que gera estresse e perda de valor do produto
.
Qualidade é de todos: Em metodologias ágeis, embora o QA lidere o processo, toda a equipe compartilha a responsabilidade pela qualidade do que é entregue
.

Prompt 4 - Liste os principais conceitos de QA

Resposta NotebookLM 4 - Os principais conceitos de Quality Assurance (QA) abrangem desde a fundamentação teórica sobre o que é qualidade até a aplicação técnica de processos e ferramentas para garantir que um software atenda aos requisitos esperados.
Com base nos documentos fornecidos, os conceitos fundamentais são:
1. Definição de QA e Diferença de QC
Quality Assurance (QA): Refere-se a práticas e técnicas orientadas ao processo, usadas para monitorar e melhorar a qualidade do software durante todo o seu ciclo de vida, desde o planejamento até a manutenção
. É uma abordagem proativa e preventiva, focada em garantir que os métodos e padrões corretos sejam seguidos para evitar defeitos
.
Quality Control (QC): Foca no produto final. É uma abordagem reativa que visa identificar e corrigir defeitos após o desenvolvimento, por meio de inspeções e execuções de testes
.
Ciclo PDCA: O processo de QA é frequentemente guiado pelo ciclo Plan-Do-Check-Act (Planejar, Fazer, Checar, Agir), que serve para a melhoria contínua dos processos organizacionais
.
2. Técnicas de Teste (Visibilidade)
Estas técnicas definem quanto do código interno é visível para quem está testando:
Caixa Preta (Black Box): O teste foca apenas em entradas e saídas, sem conhecimento da estrutura interna ou do código-fonte
.
Caixa Branca (White Box): Valida a lógica e estrutura interna do software, exigindo acesso total ao código-fonte e algoritmos
.
Caixa Cinza (Grey Box): Uma abordagem híbrida onde o testador tem conhecimento parcial da estrutura interna (como banco de dados ou arquitetura), mas executa os testes pela perspectiva do usuário
.
3. Níveis de Teste
Os testes são organizados em níveis de granularidade:
Teste de Unidade (Unit Testing): Valida as menores partes isoladas do código, como funções ou métodos
.
Teste de Integração: Verifica a comunicação e o fluxo de dados entre diferentes módulos ou serviços
.
Teste de Sistema: Avalia o software completo e integrado como um todo para garantir que atenda aos requisitos especificados
.
Teste de Aceitação (UAT): Realizado por usuários finais ou clientes para confirmar se o produto está pronto para entrega e atende às necessidades de negócio
.
4. Categorias de Teste (Funcional vs. Não-Funcional)
Testes Funcionais: Verificam o que o sistema faz, validando se as operações e ações cumprem os requisitos especificados (ex: login, pagamentos)
.
Testes Não-Funcionais: Verificam como o sistema funciona sob certas condições, avaliando atributos como desempenho, segurança, usabilidade, escalabilidade e confiabilidade
.
5. Documentação e Planejamento
Plano de Teste: Documento que define o escopo, abordagem, recursos e cronograma das atividades de teste
.
Cenário de Teste: Descrição de alto nível de uma funcionalidade que pode ser testada (ex: "Verificar a funcionalidade de pagamento")
.
Caso de Teste: Um conjunto detalhado de passos, dados de teste, pré-condições e resultados esperados para validar um requisito específico
.
6. Conceitos Adicionais Importantes
Teste de Regressão: Reexecução de testes em funcionalidades existentes para garantir que novas mudanças ou correções não quebraram o que já estava funcionando
.
Teste Ágil (Agile Testing): Prática colaborativa onde o teste ocorre continuamente desde o início do projeto. A qualidade é responsabilidade de todo o time e o foco é prevenir defeitos em vez de apenas encontrá-los
.
Priorização de Testes: Técnica para focar nos testes mais importantes ou de maior risco quando o tempo é limitado, pois o teste exaustivo é impossível
.
Modelos de Maturidade: O CMMI avalia a maturidade dos processos de desenvolvimento em 5 níveis
, enquanto o TMM (Test Maturity Model) foca especificamente na maturidade dos processos de teste
.


## Conclusão: Os prompts foram pensados para um uso real no dia-a-dia, para verificar como e o quanto a ferramenta seria útil para iniciar meus estudos no tema escolhido. Apenas com os 3 primeiros prompts ainda não foram identificados problemas nas respostas geradas pela IA.






