📊 Projeto de Integração: UX Research & Machine Learning
Este repositório documenta um estudo de caso que transforma dados brutos de uma pesquisa de UX (User Experience) em um modelo de Machine Learning aplicável a decisões de negócio e design.

O objetivo principal é demonstrar a sinergia entre a coleta de dados qualitativos/quantitativos (Pesquisa) e a análise preditiva (Ciência de Dados).

💡 Contexto da Pesquisa
A base de dados (RESULTADOPESQUISA - Dados sensiveis retirados - RESULTADOPESQUISA (1).csv) é o resultado de uma pesquisa com o público-alvo em descobrir quem compraria a solução para seu problema.

O foco da pesquisa foi:

Identificar Dores: Quais são as principais queixas estéticas dos usuários.

Mapear Hábitos: Quais produtos e cuidados de beleza já são praticados.

Avaliar Propensão: Medir o impacto dessas queixas na autoestima e a disposição a pagar por uma solução.

🛠️ O Dataset PrincipalO arquivo principal é: RESULTADOPESQUISA - Dados sensiveis retirados - RESULTADOPESQUISA (1).csvEste arquivo CSV contém Tamanho da base de dados linhas 1460, 17 colunas, incluindo dados como:Dados Demográficos: Idade, Estado civil, Estado (SIGLA), Escolaridade.Dados Comportamentais: Faixa salarial, Se trabalha ou estuda.Dados da Queixa (UX): Principal queixa (Acne, Manchas, etc.), Impacto na autoestima (Alto, Médio, Baixo), Disposição a pagar.

A partir da análise exploratória, o projeto se concentra em um desafio específico:
[Classificação/Predição]

Objetivo
[Exemplo: Prever se um usuário com uma determinada queixa e nível de autoestima estará disposto a COMPRAR uma solução estética (coluna "Se você pudesse comprar uma solução..." = SIM/NÃO)]

ModeloS UtilizadoS
[Regressão Logística, Random Forest, Decision Tree e GradientBoosting]

✅ Tecnologias e Dependências
Este projeto foi desenvolvido utilizando:

Linguagem: Python

Análise de Dados: pandas, numpy

Visualização: matplotlib, seaborn

Machine Learning: scikit-learn

Ambiente: Jupyter Notebook









