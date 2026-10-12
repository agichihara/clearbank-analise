\# ClearBank — Análise Financeira com Python



\## 1. Descrição do projeto



Este projeto foi desenvolvido como desafio final do módulo de Python aplicado à análise de dados.



O objetivo é processar transações financeiras armazenadas em um arquivo CSV, validar os registros, calcular indicadores financeiros mensais, identificar transações potencialmente suspeitas e exportar os resultados para um arquivo JSON.



\## 2. Funcionalidades



\- Leitura de arquivos CSV utilizando o módulo nativo `csv` e `csv.DictReader`.

\- Validação e limpeza de dados financeiros.

\- Tratamento de erros durante a leitura e conversão dos dados.

\- Conversão e manipulação de datas com `datetime`.

\- Cálculo de indicadores financeiros mensais:

&#x20; - Quantidade de transações.

&#x20; - Total de créditos.

&#x20; - Total de débitos.

&#x20; - Saldo mensal.

&#x20; - Média dos valores das transações.

&#x20; - Maior e menor transação de cada mês.

\- Identificação de transações acima de R$ 10.000,00.

\- Exibição de relatório formatado no terminal.

\- Exportação dos resultados para `relatorio.json`.



\## 3. Tecnologias utilizadas



\- Python 3.10 ou superior.

\- Google Colab.

\- Google Drive.

\- Módulos nativos: `csv`, `datetime`, `json` e `os`.



\## 4. Estrutura dos arquivos



\- `desafio-final.ipynb`: notebook com o código e as etapas da análise.

\- `transacoes.csv`: arquivo de entrada com os registros financeiros.

\- `relatorio.json`: arquivo gerado com os resultados da análise.



\## 5. Como executar



1\. Faça upload dos arquivos do projeto para o Google Drive.

2\. Abra `desafio-final.ipynb` no Google Colab.

3\. Execute a célula de conexão com o Google Drive e autorize o acesso.

4\. Confirme se o caminho de `transacoes.csv` corresponde à localização do arquivo.

5\. Execute todas as células do notebook na ordem apresentada.

6\. Consulte o relatório exibido e o arquivo `relatorio.json` gerado na pasta do projeto.



\## 6. Dados de teste



O arquivo de entrada foi preparado para testar o processamento de registros válidos e inválidos, incluindo campos vazios, identificadores inválidos, datas inexistentes, tipos não permitidos e valores financeiros inválidos.



A base de teste contém 25 registros, com 18 registros válidos e 7 inválidos, distribuídos entre janeiro e março de 2026. Também contém duas transações acima do limite definido para sinalização.



Essas quantidades representam os resultados esperados para a base de teste utilizada no desenvolvimento.



\## 7. Resultado esperado



Ao executar o notebook, o projeto apresenta o resumo da limpeza dos dados, as métricas financeiras mensais e a lista de transações sinalizadas.



O arquivo `relatorio.json` armazena os resultados para consulta e possível integração com outras aplicações.



\## 8. Observação



A sinalização de transações acima de R$ 10.000,00 é uma regra simplificada para fins didáticos e não representa, isoladamente, evidência de fraude ou irregularidade.

