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

## 🔍 Descrição das Análises

Foram criados quatro gráficos principais para explorar diferentes dimensões da criminalidade:

1. **Crimes por Ano e Sexo**
   - Agrupa o total de vítimas por ano, separadas por sexo (masculino e feminino).
2. **Crimes por Estado (UF)**
   - Total de vítimas em cada unidade federativa.
3. **Crimes por Estado x Ano**
   - Gráfico de barras empilhadas: para cada estado, o total de vítimas em cada ano.
4. **Crimes por Mês**
   - Total de vítimas em cada mês do ano, considerando todo o período.

---

## 💡 Principais Insights

- **Bahia como o local mais perigoso**: o estado da Bahia lidera o número de vítimas no período analisado.
- **2017 como o ano mais crítico**: registrou o maior número total de vítimas em todos os anos (2015-2022).
- **Queda em 2020**: observou-se uma redução significativa em 2020, possivelmente reflexo de restrições de mobilidade durante a pandemia.
- **Retomada em 2021**: após a queda, os números voltam a subir em 2021.
- **Predominância masculina**: as vítimas de crimes são majoritariamente do sexo masculino.

---

## 🚀 Como Reproduzir

1. Clone este repositório:
   ```bash
git clone https://github.com/seu-usuario/analise-crimes-sinesp.git
cd analise-crimes-sinesp
```
2. Instale as dependências:
   ```bash
pip install pandas matplotlib
```
3. Execute o notebook ou o script:
   - **Notebook**: abra `notebooks/analise_crimes_pandas.ipynb` e execute célula a célula.
   - **Script**: rode o script Python:
     ```bash
python scripts/gerar_graficos.py
```
4. Confira as figuras geradas na pasta `output/`.

---

## 🤝 Contribuições

Pull requests são bem-vindos! Sinta-se à vontade para abrir issues ou sugerir melhorias.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
```

