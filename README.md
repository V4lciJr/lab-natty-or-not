# 🚀 Painel Interativo de Análise do Mercado de Trabalho Brasileiro 📊

Este projeto é uma ação de extensão universitária que visa democratizar o acesso a informações cruciais sobre o cenário profissional do Brasil. Desenvolvido com base em Ciência de Dados e Inteligência Artificial, nosso painel transforma dados complexos e dispersos em insights claros e acionáveis para estudantes, profissionais, educadores e empresas.

Em um mercado de trabalho em constante evolução, o acesso a dados atualizados e interpretáveis é um diferencial. Nosso objetivo é capacitar o público com as ferramentas necessárias para tomar decisões de carreira e educacionais mais informadas.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias e bibliotecas:

  * **Python 🐍:** Linguagem de programação principal.
  * **Streamlit 🚀:** Framework para a construção da interface do painel web interativo.
  * **LangChain 🔗:** Framework para orquestração de agentes de IA, permitindo a interação com Large Language Models (LLMs) e ferramentas externas.
  * **ChatOpenAI (GPT-4.1-mini) 🤖:** Utilizado como LLM para capacidades de processamento de linguagem natural e raciocínio dos agentes.
  * **GoogleSerperAPIWrapper 🌐:** Ferramenta integrada ao LangChain para realizar buscas avançadas na internet.
  * **Beautiful Soup 🧺:** Biblioteca para web scraping, usada para extrair dados de websites como o IBGE.
  * **Pandas 🐼:** Biblioteca para manipulação e análise de dados.
  * **NLTK & spaCy 💬:** Bibliotecas para Processamento de Linguagem Natural (PLN), utilizadas na análise de textos de vagas.
  * **Dotenv 🔑:** Para gerenciamento seguro de variáveis de ambiente (como chaves de API).

## 🔍 Funcionalidades Principais

Nosso painel é dividido em seções interativas, cada uma impulsionada por agentes de Inteligência Artificial dedicados:

  * **1. Visão Geral do Mercado:** 🇧🇷

      * Um panorama rápido e atualizado das estatísticas do mercado de trabalho brasileiro (taxa de desemprego, subutilização, desalentados) diretamente do IBGE via web scraping.
      * Manchetes recentes sobre o cenário de empregos, coletadas via busca inteligente no Google.
      * Identificação dos setores com maior crescimento.

  * **2. Tendências por Área Profissional/Setor:** 📈

      * Análises aprofundadas sobre as tendências emergentes em diversas áreas e setores, ajudando a identificar onde estão as maiores oportunidades e para onde o mercado está se movendo.

  * **3. Pesquisa Personalizada de Vagas:** 🕵️‍♀️

      * Permite que o usuário pesquise uma vaga específica (ex: "Desenvolvedor Python", "Analista de Dados").
      * Agentes de IA realizam buscas inteligentes na web para encontrar vagas relevantes e apresentam os resultados.
      * *(Em desenvolvimento: futuras implementações incluirão métricas como percentual de vagas júnior/pleno/sênior e um "score" de compatibilidade com o perfil do usuário.)*

  * **4. Habilidades e Skills Demandadas:** 🎯

      * Com base na vaga pesquisada pelo usuário, esta seção lista as habilidades técnicas e comportamentais (soft skills) mais procuradas pelo mercado.
      * Um guia prático para direcionar o desenvolvimento profissional e a aquisição de novas competências.

## ✅ Resultados e Contribuições
Com o desenvolvimento das atividades, alcançamos um protótipo funcional que demonstra o potencial da Inteligência Artificial na democratização de informações complexas do mercado de trabalho. Conseguimos integrar web scraping de fontes como o IBGE com agentes de IA avançados baseados em LLMs, apresentando os dados em um painel interativo e intuitivo.

Este trabalho contribui significativamente para o contexto de pesquisa ao aplicar conceitos de Ciência de Dados e IA na resolução de um problema social relevante. Para a comunidade, oferece uma ferramenta valiosa para o planejamento de carreira e educação, transformando dados brutos em conhecimento acionável.

## 🚧 Desafios Enfrentados
Durante o desenvolvimento, enfrentamos alguns desafios notáveis:

Escassez de APIs Abertas: A maioria das grandes plataformas de emprego não oferece APIs públicas e gratuitas, o que nos forçou a depender fortemente do web scraping.
Bloqueios de Web Scraping: Sites como o LinkedIn possuem robustos sistemas de detecção e bloqueio de requisições automatizadas. Isso exigiu um aprendizado contínuo sobre técnicas de rate limiting, user-agent rotation e outras estratégias para evitar o bloqueio e garantir a coleta de dados de forma ética e eficiente. Essas dificuldades ressaltam a importância de sempre considerar as políticas de uso e a conformidade legal ao realizar web scraping.
