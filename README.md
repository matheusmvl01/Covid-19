# Panorama do COVID-19 no Brasil e no Mundo

Este projeto realiza uma análise abrangente dos dados relacionados à pandemia de COVID-19, com foco em casos confirmados, mortes e outros indicadores relevantes tanto no Brasil quanto em escala global.

## Sobre o Projeto

O objetivo é explorar e compreender o impacto da pandemia utilizando dados do conjunto `owid-covid-data.csv`, disponibilizado pelo Our World in Data. Este dataset contém informações detalhadas como:
- Total de casos e mortes.
- Proporção de casos/mortes por milhão de habitantes.
- Testagem e indicadores de vacinação.
- Dados demográficos como densidade populacional e PIB per capita.

A análise foca em compreender a evolução temporal da pandemia, identificar discrepâncias regionais e extrair insights relevantes para políticas públicas e gestão de crises.

## Principais Resultados

- **Evolução Temporal**: O projeto identifica o crescimento exponencial inicial dos casos e mortes, seguido por momentos de desaceleração em alguns países.
- **Brasil**: O primeiro caso registrado foi em 1º de março de 2020 e a primeira morte ocorreu 21 dias depois. No total, 17,42% da população foi infectada, com uma taxa de mortalidade de 0,32%.
- **Disparidades Regionais**: Na índia, por exemplo, a taxa de mortalidade proporcional é baixa (0,03%), mesmo com altos números absolutos de mortes, devido à grande população.
- **Impacto Global**: Países como Estados Unidos, Brasil e Índia lideram em números absolutos de casos e mortes, mas países como França e Alemanha apresentam maiores impactos em termos proporcionais.

## Recursos Utilizados

- **Linguagens**: Python (bibliotecas Pandas, Matplotlib, NumPy).
- **Dados**: Dataset `owid-covid-data.csv` do Our World in Data.
- **Visualização**: Gráficos de linha e barras em escalas linear e logarítmica para destacar tendências e padrões.

## Como Utilizar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. **Instale as dependências**:
   Certifique-se de ter o Python instalado. Em seguida, instale as bibliotecas necessárias:
   ```bash
   pip install pandas matplotlib numpy
   ```
3. **Execute o script**:
   Use o Python para rodar o arquivo principal:
   ```bash
   python panorama_do_covid_19_no_brasil.py
   ```

## Visualizações Incluídas

- **Evolução Mundial**: Gráfico de linha mostrando o aumento de casos globais.
- **Análise Regional**: Gráficos destacando os países com maiores números de casos e mortes.
- **Brasil**: Gráficos de casos e mortes com escalas linear e logarítmica.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias no código ou na documentação.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
