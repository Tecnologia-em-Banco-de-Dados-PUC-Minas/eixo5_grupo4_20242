# Etapa 3 - PRÉ-PROCESSAMENTO DE DADOS

Na terceira etapa do projeto, os dados coletados estão disponíveis, oriundos de diferentes fontes e formatos. Assim, o objetivo principal desta fase é realizar o pré-processamento dos dados, garantindo que estejam limpos, padronizados e prontos para as análises subsequentes e para o treinamento dos algoritmos de machine learning. O pré-processamento é uma etapa crítica para assegurar a qualidade e a consistência dos dados, o que impacta diretamente nos resultados das análises.

### Ações Realizadas no Pré-Processamento:

1. **Exploração Inicial dos Dados**:
   - Realizamos uma análise exploratória para entender a estrutura e o conteúdo dos dados, identificando inconsistências, valores ausentes e possíveis outliers.
   
2. **Remoção de Dados Inválidos ou Inconsistentes**:
   - Foram removidos dados e valores que não deveriam estar presentes, como registros duplicados, dados incompletos ou inconsistências em variáveis-chave (como idades negativas ou faixas de renda incompatíveis).

3. **Tratamento de Valores Ausentes**:
   - Valores ausentes foram tratados de acordo com a natureza dos dados. Em algumas variáveis, a imputação de valores foi aplicada (como a mediana ou a média), enquanto, em outras, optou-se pela remoção dos registros incompletos.

4. **Conversão de Tipos de Dados**:
   - Variáveis que estavam em formatos diferentes (como strings que deveriam ser numéricas) foram convertidas para o tipo de dado correto, assegurando que pudessem ser utilizadas nas análises posteriores.

5. **Padronização de Variáveis**:
   - Os valores de determinadas variáveis foram padronizados. Por exemplo, nomes de estados e cidades foram convertidos para um formato uniforme, e as unidades monetárias foram ajustadas para o mesmo padrão de referência (reais, em caso de dados de renda).

6. **Criação de Novas Variáveis Derivadas**:
   - Algumas variáveis derivadas foram criadas com base nas existentes, para facilitar análises mais detalhadas. Exemplo: criação de categorias específicas para faixas etárias e grupos de renda.

7. **Junção de Dados de Múltiplas Fontes**:
   - Foi realizada a junção de diferentes bases de dados do IBGE e de outras fontes relevantes, garantindo que todas as variáveis necessárias estivessem presentes no conjunto final de dados.

### Ferramentas Utilizadas no Pré-Processamento:

Para realizar o pré-processamento dos dados, foi escolhida a **linguagem Python**, devido à sua robustez e ao amplo ecossistema de bibliotecas especializadas em manipulação de dados e machine learning. As principais ferramentas utilizadas foram:

- **Pandas**: Utilizada para manipulação e análise de dados estruturados, especialmente para a remoção de valores ausentes, duplicação de registros e a criação de variáveis derivadas.
- **NumPy**: Empregada para a realização de operações matemáticas e conversões de tipos de dados.
- **Matplotlib e Seaborn**: Utilizadas para a visualização inicial dos dados, ajudando a identificar outliers e inconsistências durante a exploração dos dados.
- **Databricks**: Integrado ao ambiente de nuvem, o Databricks foi utilizado para o processamento em larga escala e a execução de pipelines ETL (Extração, Transformação e Carga).
- **Jupyter Notebooks**: Ambiente interativo que facilitou a experimentação e a documentação do processo de pré-processamento.

### Justificativa para a Escolha das Ferramentas:

- **Python** foi escolhido como a principal linguagem de programação devido à sua flexibilidade e ao suporte oferecido para bibliotecas de ciência de dados.
- **Pandas** e **NumPy** são amplamente aceitos como as melhores ferramentas para manipulação de dados, oferecendo facilidade e eficiência no tratamento e conversão dos dados.
- **Databricks** foi selecionado devido à sua capacidade de escalabilidade e integração com o Azure, possibilitando o processamento eficiente de grandes volumes de dados e o gerenciamento de pipelines complexos.
