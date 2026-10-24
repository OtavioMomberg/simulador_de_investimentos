# 📈 Simulador de Investimentos

Uma ferramenta que realiza a simulação de investimentos em fundos imobiliários, informando sugestões de valores a investir com base no aporte
do investidor, monstrando o patrimônio acumulado de acordo com os anos e os dividendos mensais.

# 🧩 Funcionalidades

- Sugere um valor para ser utilizado para investir com base em 30% do salário do investidor;
- Realiza a projeção do patrimônio acumulado de acordo com a taxa de rendimento mensal, aporte e quantidade de anos;
- Calcula os dividendos mensais com base no patrimônio acumulado estimado;
- Projeta cenários de patrimônio e dividendos em 2, 5, 10, 20 e 30 anos;
- Permite a simulação de diferentes modelos de investidores como "Conservador", "Moderado" e "Agressivo",
- sugerindo diferentes percentuais para cada tipo de FII disponível na ferramenta;

# 💡Percentuais de acordo com os tipos de FII

1. Conservador

| FII | Percentual(%) |
| --- | --- | 
| **PAPEL** | 30 | 
| **TIJOLO** | 50 | 
| **HÍBRIDO** | 10 | 
| **FOF** | 10 | 
| **DESENVOLVIMENTO** | 0 | 
| **HOTELARIA** | 0 | 

2. Moderado

| FII | Percentual(%) |
| --- | --- | 
| **PAPEL** | 32 | 
| **TIJOLO** | 35 | 
| **HÍBRIDO** | 8 | 
| **FOF** | 5 | 
| **DESENVOLVIMENTO** | 10 | 
| **HOTELARIA** | 10 |

3. Agressivo

| FII | Percentual(%) |
| --- | --- | 
| **PAPEL** | 50 | 
| **TIJOLO** | 10 | 
| **HÍBRIDO** | 5 | 
| **FOF** | 5 | 
| **DESENVOLVIMENTO** | 20 | 
| **HOTELARIA** | 10 |

# 🧮 Calculos

- A projeção do patrimônio acumulado foi feita por meio da função VF (Valor Futuro), a qual necessita dos seguintes paramêtros:
  - Taxa Mensal;
  - Quantidade de Anos;
  - Aporte.
- O percentual de cada tipo de FII é mostrado dinamicamente de acordo com o perfil do investidor utilizando uma tabela de suporte contendo
uma tabela com chave, perfil, tipo de FII e o percentual. Os valores são buscados utilizando a função PROCV a qual busca verticalmente por uma chave a esquerda
da tabela, quando encontra, ela pega o percentual daquela chave em especifico e retorna ao campo.
- Intervalos nomeados foram utilizados para facilitar a legibilidade das funções e facilitar a manutenção e expansão da ferramenta:
  ![Intervalos Nomeados](https://github.com/OtavioMomberg/simulador_de_investimentos/blob/main/imagens/intervalos_nomeados.png)

# 🖼️ Imagens do Projeto

![Img1](https://github.com/OtavioMomberg/simulador_de_investimentos/blob/main/imagens/img1.png)


![Img2](https://github.com/OtavioMomberg/simulador_de_investimentos/blob/main/imagens/img2.png)


![Img3](https://github.com/OtavioMomberg/simulador_de_investimentos/blob/main/imagens/img3.png)
