
# 🗺️ Análise da Distribuição de Farmácias em São Paulo com Google Maps

Bem-vindo à **Análise da Distribuição de Farmácias em São Paulo**! Este projeto tem como objetivo mapear e analisar a distribuição de farmácias na cidade de São Paulo utilizando **Python**, **Selenium**, **Folium** e o **Google Maps**. Vamos explorar quais bairros possuem mais farmácias, quais redes dominam e visualizar essas informações em um mapa interativo. 📊🏥
![Mapa de Calor das Farmácias em São Paulo](https://github.com/LauraMattz/Pharmacy_Distribution_Analysis_SaoPaulo/blob/main/pharmacy_heatmap_sao_paulo.png?raw=true)

## 🚀 Visão Geral do Projeto

Este projeto utiliza **web scraping** e **análise geoespacial** para entender a distribuição das farmácias em São Paulo. A ideia surgiu ao notar uma grande quantidade de farmácias em um bairro, e eu queria saber se essa tendência era a mesma para a cidade inteira.

Ferramentas utilizadas:
- **Selenium** para automatizar a coleta de dados do **Google Maps**.
- **Folium** para visualizar os dados coletados em um mapa interativo.
- **Pandas** e **Counter** para analisar e manipular os dados obtidos.

## 🌟 Funcionalidades

- **Coleta de Dados Automatizada** do Google Maps para 96 bairros de São Paulo.
- **Mapa de Calor Interativo** mostrando a densidade de farmácias pela cidade.
- **Análise das Redes de Farmácias Mais Populares**.
- **Insights Geoespaciais** para planejamento urbano e oportunidades de negócio.

## 🛠️ Tecnologias Utilizadas

- **Python** 🐍: Linguagem principal para coleta, análise e visualização dos dados.
- **Selenium** 🤖: Automação da interação com o Google Maps para coletar dados das farmácias em todos os bairros.
- **Folium** 🗺️: Utilizado para criar mapas interativos que mostram a distribuição de farmácias.
- **Pandas** 📊: Para organizar, manipular e resumir os dados de maneira eficiente.
- **Google Maps** 🌍: Fonte dos dados geoespaciais das farmácias.

## 📝 Como Utilizar

### Pré-requisitos

Certifique-se de ter **Python 3.7+** e **ChromeDriver** instalados. O projeto também depende de alguns pacotes Python:

- Selenium
- Folium
- Pandas
- Matplotlib

Para instalar as dependências, execute:

```bash
pip install -r requirements.txt
```

### Executando a Análise

1. **Clone o Repositório**:

   ```bash
   git clone https://github.com/seu-usuario/Pharmacy_Distribution_Analysis_SaoPaulo_Maps.git
   cd Pharmacy_Distribution_Analysis_SaoPaulo_Maps
   ```

2. **Configure o ChromeDriver**:

   Certifique-se de que o **ChromeDriver** esteja instalado e configurado corretamente no seu ambiente. Você pode baixá-lo [aqui](https://sites.google.com/chromium.org/driver/).

3. **Execute o Notebook ou o Script**:

   Utilize os notebooks na pasta `notebooks/` ou os scripts disponíveis na pasta `scripts/` para coletar e analisar os dados.

## 🌐 Visualização dos Resultados

Os resultados incluem um **mapa de calor interativo** que destaca as áreas com maior concentração de farmácias e outras áreas que têm poucos ou nenhum estabelecimento desse tipo. Esses insights são extremamente úteis para:

- **Planejamento Urbano**: Identificar regiões desassistidas e onde há saturação de farmácias.
- **Empreendedores**: Encontrar oportunidades de abrir novas farmácias em locais estratégicos.
- **Tomadores de Decisão**: Melhorar o acesso aos serviços de saúde na cidade.

## 🏆 Conclusões

O projeto mostra que a **Zona Sul** de São Paulo possui a maior concentração de farmácias, enquanto algumas áreas do **Centro** e **Zona Norte** apresentam uma baixa cobertura. Essas informações podem guiar tanto **estratégias empresariais** quanto **políticas públicas** voltadas para a melhoria do acesso aos serviços de saúde.

## 💡 Próximos Passos

- **Cruzamento de Dados**: Relacionar os dados de farmácias com informações populacionais e de infraestrutura, como proximidade a hospitais e UPAs.
- **Previsão de Demanda**: Utilizar modelos de **Machine Learning** para prever a demanda de farmácias em diferentes regiões.

## ✨ Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests. Vamos tornar este projeto ainda mais poderoso! 🤝

## 📜 Licença

Este projeto está licenciado sob a **MIT License**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

### 🔗 Links Úteis

- [Documentação Selenium](https://www.selenium.dev/documentation/en/)
- [Folium no GitHub](https://github.com/python-visualization/folium)

Esperamos que este projeto seja útil para **análise urbana**, **planejamento estratégico**, e **oportunidades de negócio**. Se tiver alguma dúvida, sinta-se à vontade para perguntar! 🚀📍✨

