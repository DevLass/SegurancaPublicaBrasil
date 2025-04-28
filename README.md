```markdown
# Análise de Ocorrências Criminais (2015-2022)

Este projeto foi desenvolvido com o objetivo de **ensinar o uso do Pandas** para um amigo. Utilizando a base de dados **Ocorrências Criminais - SINESP (2015-2022)**. Durante o processo, além de exercitar técnicas de manipulação, filtragem e visualização, descobrimos insights surpreendentes sobre a criminalidade no Brasil.

---

## 🧰 Ferramentas e Tecnologias

- Python 3.x
- Pandas
- Matplotlib

> Para instalar as dependências:
```bash
pip install pandas matplotlib
```

---

### Descrição das Análises

Foram criados quatro gráficos principais para explorar diferentes dimensões da criminalidade:

1. **Crimes por Ano e Sexo**
   - Agrupa o total de vítimas por ano, separadas por sexo (masculino e feminino).
      <img src="https://raw.githubusercontent.com/DevLass/SegurancaPublicaBrasil/main/crimesanosexo.png" width="650"/>

2. **Crimes por Estado x Ano**
   - Gráfico de barras empilhadas: para cada estado, o total de vítimas em cada ano.
      <img src="https://raw.githubusercontent.com/DevLass/SegurancaPublicaBrasil/main/crimesestadoano.png" width="650"/>
      
3. **Crimes por Mês**
   - Total de vítimas em cada mês do ano, considerando todo o período.
      <img src="https://raw.githubusercontent.com/DevLass/SegurancaPublicaBrasil/main/crimesmes.png" width="650"/>

---

### 💡 Principais Insights Percebidos

- **Uniformidade Mensal**: existe uma uniformidade na incidência criminal entre os meses.
- **Predominância masculina**: as vítimas de crimes são majoritariamente do sexo masculino.
- **Bahia como o local mais perigoso**: o estado da Bahia lidera o número de vítimas no período analisado.
- **Tendências Temporais (2015-2022):**
  - **2017 como o ano mais crítico:** registrou o maior número total de vítimas no período analisado.
  - **Queda em 2020:** observou-se uma redução significativa no número de vítimas, possivelmente reflexo das restrições de mobilidade impostas pela pandemia.
  - **Retomada em 2021:** após a queda em 2020, os números voltam a subir no ano seguinte, indicando uma recuperação nos índices de criminalidade.


---


