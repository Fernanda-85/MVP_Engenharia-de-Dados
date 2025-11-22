# MVP_Engenharia-de-Dados
### QUAL TIME FEZ MAIS GOLS? ESSE TIME FOI O CAMPEÃO?
### QUAL TIME TEVE MAIS VITÓRIAS E QUAL TIME TEVE MAIS DERROTAS? FOI CAMPEÃO/REBAIXADO?
### QUAL ESTÁDIO FOI MAIS UTLIZADO?
### QUEM JOGOU EM CASA GANHOU MAIS QUE VISITANTE?
### QUAL JOGO TEVE MAIOR PÚBLICO? ERA UM JOGO DECISIVO?
🚴 Análise de Dados: Sistema de Bike Sharing
📌 Visão Geral do Projeto
Este projeto de análise de dados explora padrões de demanda em um sistema de compartilhamento de bicicletas, fornecendo insights valiosos para tomada de decisão estratégica. Através de técnicas de ETL, modelagem de dados e análise exploratória, identificamos fatores-chave que influenciam o comportamento dos usuários.

🎯 Objetivos Principais
Analisar o impacto da sazonalidade no volume de aluguéis
Investigar a influência das condições meteorológicas na demanda
Comparar padrões de uso entre usuários casuais e registrados
Identificar horários de pico e variações diárias/semanais
Fornecer recomendações acionáveis baseadas em dados
📊 Principais Insights
🌦️ Impacto do Clima
Dias claros: 40% mais aluguéis que dias chuvosos/nevados
Neblina: reduz demanda em 25% comparado a dias claros
📅 Sazonalidade
Verão: 35% do total de aluguéis (pico de demanda)
Inverno: 15% do total (menor demanda)
⏰ Padrões Temporais
Dias úteis: Picos às 8h e 17h-18h (deslocamento)
Fins de semana: Pico ao meio-dia (uso recreativo)
🌡️ Fatores Ambientais
Correlação de 0.75 entre temperatura e número de aluguéis
🛠️ Tecnologias Utilizadas
Plataforma: Databricks
Linguagens: SQL, Python
Visualização: Matplotlib, Seaborn
Processamento: ETL, Modelagem de Dados
Versionamento: Git e GitHub
📂 Estrutura do Projeto
Base de Dados
Origem: /databricks-datasets/bikeSharing/
Arquivos principais: day.csv e hour.csv
Modelagem de Dados
Tabelas SQL criadas:

dados_dia (16 atributos)
dados_hora (17 atributos)
Catálogo de dados documentado

Processamento (ETL)
Criação da tabela diária:
CREATE TABLE dados_dia AS
SELECT * FROM bikeSharing.day;
📊 Análise Exploratória
Consultas SQL para agregações: Utilização de SQL para realizar agregações e calcular métricas chave, como a média de aluguéis por hora, dia e condições climáticas.
Visualizações com Python: Criação de gráficos usando bibliotecas como Matplotlib e Seaborn para visualizar padrões de uso, como as variações de demanda por hora, clima e estação do ano.
Identificação de padrões e tendências: Análise dos dados para descobrir comportamentos recorrentes e influências de fatores como clima, sazonalidade e horários de pico.
📈 Principais Resultados
Recomendações Operacionais
Ajustar frota conforme previsão do tempo e estações: Planejamento da quantidade de bicicletas disponível baseado nas condições climáticas e nas estações do ano.
Campanhas promocionais no inverno/dias chuvosos: Implementar campanhas de incentivo ao uso das bicicletas durante períodos de baixa demanda.
Aumentar disponibilidade nos horários de pico: Garantir que haja um número adequado de bicicletas disponíveis nos horários de maior demanda, como as manhãs e final da tarde nos dias úteis.
Estratégias de Marketing
Incentivos para uso recreativo nos fins de semana: Criar estratégias de marketing para incentivar o uso das bicicletas para lazer, especialmente aos finais de semana.
Parcerias com pontos turísticos e empresas locais: Explorar parcerias que possam aumentar a visibilidade e a utilização do sistema de bike sharing.
Melhorias de Infraestrutura
Proteção contra condições climáticas adversas: Garantir que as estações de bicicletas ofereçam proteção contra condições climáticas como chuvas fortes ou temperaturas extremas.
Otimização da distribuição das estações: Analisar os padrões de uso e otimizar a distribuição das estações para cobrir melhor áreas com maior demanda.
🚀 Como Reproduzir o Projeto
Clone o repositório:
git clone https://github.com/brunosuassuna/MVP-Engenharia-de-Dados
💡 Habilidades Demonstradas
✅ Engenharia de Dados

Experiência em processos de ETL e modelagem de dados para análise eficiente e organização das informações.
✅ Análise Exploratória

Proficiente em SQL e Python para análise e manipulação de grandes volumes de dados, identificando padrões e insights importantes.
✅ Visualização de Dados e Storytelling

Habilidade em criar visualizações impactantes usando Matplotlib e Seaborn, facilitando a compreensão de dados e apresentando insights de maneira clara.
✅ Solução de Problemas Baseada em Dados

Capacidade de identificar e resolver problemas operacionais com base em dados reais, implementando soluções que melhoram a eficiência e a tomada de decisão.
✅ Documentação Técnica

Produção de documentação detalhada e bem estruturada, garantindo a clareza no processo e a comunicação eficaz entre as partes interessadas.
