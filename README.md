# Gocache

### Projeto de Detecção de Ataques DDoS
Este projeto tem como objetivo detectar ataques DDoS (Distributed Denial of Service) utilizando técnicas de ciência de dados e aprendizado de máquina. A análise é feita com base em logs de servidor HTTP, identificando padrões de tráfego anômalos que indicam um ataque.

### Estrutura do Projeto

- **dados/:** Contém os arquivos CSV com os dados de logs de servidor.
    - **arquivo_sem_ataque.csv:** Logs de tráfego normal.
    - **arquivo_com_ataque.csv:** Logs contendo um período de tráfego normal, seguido de um ataque DDoS e o retorno ao tráfego normal.
- **teste_gocache.ipynb:** Contém o algoritmo com a análise e desenvolvimento do modelo.
