# Entrada (Input)

**Problema de Negócio:** O Banco Elegance deseja desenvolver um sistema de previsão que identifique com antecedência os clientes propensos a encerrar suas contas bancárias. Isso permitirá que o banco adote medidas proativas para reter esses clientes, oferecendo soluções personalizadas, benefícios adicionais e um atendimento excepcional. O objetivo é evitar que os clientes de alto valor deixem o banco, mantendo sua lealdade e protegendo a reputação do Banco Elegance no setor financeiro.

**Questões de Negócio:**

1. Quais são os principais indicadores demográficos dos clientes que estão encerrando suas contas?
2. Existe sazonalidade no encerramento de contas bancárias?
3. Como o histórico de transações afeta o encerramento de contas?
4. Quais produtos bancários adicionais os clientes estão cancelando junto com suas contas?
5. Há correlações entre a antiguidade do cliente no banco e o encerramento de contas?
6. Quais são os principais motivos ou feedbacks dos clientes que estão encerrando suas contas?
7. Como os clientes que encerram suas contas se comparam aos que permanecem em termos de uso de serviços adicionais?
8. Quais métricas financeiras estão relacionadas ao encerramento de contas?
9. Existem clusters ou segmentos de clientes que têm comportamentos semelhantes em relação ao encerramento de contas?
10. Qual é a distribuição da taxa de encerramento de contas ao longo do tempo?

**Fonte de Dados:** Arquivo .csv com os dados clientes dos bancos, sendo que essa base contém os cliente que encerraram e não encerraram a conta.

# Saída (OutPut)

**Entrega do Problema de Negócio:** 

  1. Modelo de Classificação que diz informa a probabilidade do cliente encerrar a conta no banco.
  2. Tabela com os clientes classificados, informando a probabilidade destes mesmos desistirem de ter uma conta no banco.
  3. Lista automazida em que o cliente basta inserir os dados e clicar no botão de predição para saber a probabilidade de desistência desse cliente. Essa construção será via google sheets.

**Questões de Negócios:**

  1. Relatório com gráficos e análise corroborando as questões de negócio que serão respondidads.


# Tarefas(Taks)

**Modelo de Classificação:**

  *Etapa 1:* Compreensão dos Dados (Realizado)
    i. Descrição dos Atributos. (Realizado)
  
  *Etapa 2:* Preparação dos Dados
    Renomear colunas (Realizado)
    i. Quantidade de dados;
    ii. Verificação da Quantidade de dados nulos;(Realizado)
    iii. Preechimento(ou Exclusão) dos dados nulos;(Realizado)
    iv. Verificação da natureza das variáveis e mudança da natureza dessas variáveis.(Realizado)
    v. Estatística Descritiva dos dados; (Realizado)
    vi. Analise descritiva e relatorio resumidos(Realizado)

  *Etapa 3: Feature Engineering*
    i. Identificar a variável alvo. (Realizado)
    ii. Aprofundamento no negócios. (Realizado)
    iii. Hipótese de Negócios. (Realizado)

  *Etapa 4:* Análise Exploratória dos Dados
    i. Análise Univariada: verificação da dispersão dos dados e dos outliers; (Realizado)
    ii. Análise Multivariada: verificaçaõ da multivariedade de dados numéricos e categóricos(Realizado)
    iii. Responder algumas questões de negócios;(Realizado)
    iv. Resumo das variáveis que trazem mais informação sobre a variável alvo.(Realizado)

  *Etapa 5:* Modelagem dos Dados
    i. Padronização dos Dados;(realizado)
    ii. Normalização dos Dados;(Realizado)
    iii. Encoding dos Dados;(Realizado)

  *Etapa 6:* Seleção da Features;
    i. Escolhas das variáveis com maior ganho de informação da variável resposta.(Em construção)
    ii. Análise final das variáveis escolhidas por modelos, junto com a análise descritiva;

  *Etapa 7*: Treinamento dos Modelos
    i. Separação dos Dados entre Treino, Teste e Validação.
    ii. Treino com Vários Modelos de Classificação
    iii. Verificar performance analisando das métricas de Precisão, Recuperação, f1, matriz de confusão, curva de lift e curva de ganho
    iv. Análise final para escolha do melhor modelo.

  *Etapa 8:* Hiper Parametrização do Modelo
    i. Fine Tunning para determinar os melhores parâmetros e aumentar a performance do modelo.
    ii. Retreino final com todos os dados.

  *Etapa 9:* Entregas
    i. Modelo Final.
    ii. Lista com os clientes classificados com a probabilidade de encerramento de conta.
    iii. Construção da API para o treino do modelo.
    iv. Construção da Planilha via google sheets.


**Questões de Negócios:**

  *Etapa 10:* Responder as questões baseados em todo o script construídos. Construir relatório a parte com as questões respondidas. Escolher dataset correto 
  para responder essa questão.

  