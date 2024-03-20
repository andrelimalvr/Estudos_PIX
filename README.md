# PIX

## Descrição

O Pix foi muito utilizado desde o seu lancamento, logo, este projeto visa filtrar a quantidade de transações e quanto foi transitado de valor via pix tanto para PJ quanto para PF 

## Tecnologias Usadas

- **Front-end**: Python, HTML, SQL
- **Back-end**: Streamlit
- **API de PIX**: Pix API
- **Deploy**: Streamlit

## Funcionalidades

- Pesquisa de valores transacionados por cidade.
- Exibição de informações como valor total, valor em 2023 e 2024.
- Exibição de previsões de transações para os próximos dias.

## Problemas Resolvidos

- Este projeto visa facilitar a busca filtradas pelas transações que são representadas pelas funcionalidades acima, deixa mais intuitivo para quem busca a informação, originalmente só seria apenas por arquivos csv, onde precisaria de uma pessoa mais técnica para ler as informações.

## Estudo de caso

- Muito desse projeto foi feito em Python, mas também houve outras fontes que foram trazendo corpo para o projeto, que é importante para o projeto em si.
- Tive que fazer ETL em planilhas CSV utilizando SQL, na qual ficaria mais facil para limpar os dados
- Depois, com python, eu apenas linkei os csv para a funcionalidade do projeto e como que eu queria que ela fosse filtrada.
- Seja por cidade, estado, ano, mês
