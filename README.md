# Pipeline ETL com Integração de IA Generativa (GPT-4)

## 📌 Sobre o Projeto
Este projeto demonstra um ciclo completo de **Data Engineering** e **Data Science**, focado no processo de ETL (Extract, Transform, Load). A grande inovação aqui é a utilização de Inteligência Artificial para realizar a etapa de transformação, criando uma personalização em massa que seria impossível de forma manual.

## 🛠️ O Fluxo ETL
1. **Extração (Extract):** Leitura de uma lista de IDs a partir de um arquivo CSV e coleta dos dados detalhados dos usuários através de uma API REST.
2. **Transformação (Transform):** Utilização da API da OpenAI (GPT-4) para analisar os dados do usuário e gerar mensagens personalizadas e exclusivas.
3. **Carregamento (Load):** Atualização dos dados do usuário na API original, fechando o ciclo de dados.

## 🧰 Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas:** `pandas` (manipulação de dados), `requests` (consumo de APIs).
* **IA:** OpenAI API (GPT-4) para Processamento de Linguagem Natural (NLP).
* **API de Destino:** Santander Dev Week 2023 API.

## 🚀 Como Executar
1. Instale as dependências: `pip install pandas requests`
2. Configure sua `OPENAI_API_KEY`.
3. Execute o script principal para processar os usuários.

## 📈 Impacto de Negócio
Este modelo de pipeline demonstra como empresas podem escalar o atendimento personalizado e o marketing direcionado utilizando o poder da IA generativa de forma automatizada e eficiente.

## 👩‍💻 Autora
Feito com 💛 por Bruna Guimarães
