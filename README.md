Tech Challenge – Fase 3 – Análise PNAD COVID-19 (IBGE)
Autor
Vitor Santos
RM: rm366038
Instituição: FIAP – Pós Tech

Descrição do Projeto
Este projeto tem como objetivo analisar o comportamento da população brasileira durante a pandemia da COVID-19 utilizando dados da PNAD COVID-19 (IBGE), com foco em:
Sintomas clínicos
Gravidade dos casos
Procura por atendimento médico
Perfil demográfico
Relação com trabalho e tipo de ocupação
Diferenças regionais e estaduais
A análise busca gerar insights estratégicos para planejamento hospitalar e apoio à tomada de decisão em cenários de crise sanitária.


Fonte dos Dados
Instituto: IBGE
Base: PNAD COVID-19
Período analisado: 3 meses (conforme exigência do enunciado)
Formato: CSV (compactado em .zip no repositório devido ao limite de tamanho do GitHub)

Estrutura do Repositório:

Python: Tech_Challenge_Fase3_RM_rm366038.ipynb
Documentacao: Tech_Challenge_Fase3.pdf
Arquivos CSV (IBGE): PNAD_COVID
Dicionario dos Codigos: Dicionario_PNAD_COVID

O notebook realiza automaticamente:

Limpeza e tratamento dos dados
Criação das variáveis derivadas
Geração dos gráficos
Produção das análises

Perguntas de Pesquisa Utilizadas:

Perfil populacional:

- A002 – Idade
- A003 – Sexo
- A004 – Cor ou raça
- A005 – Escolaridade
- Saúde e sintomas
- B0011 – Teve febre
- B0012 – Teve tosse
- B00111 – Perda de cheiro ou sabor
- B002 – Procurou estabelecimento de saúde
- B011 – Resultado do teste COVID-19
- Proteção e higiene
- F002A2 – Uso de álcool 70%
- F002A3 – Uso de máscara

Trabalho:

- C007C – Tipo de trabalho
- Situação de trabalho presencial/remoto (variável derivada)

Principais Análises Realizadas:

- Gravidade dos sintomas por faixa etária
- Procura por atendimento médico por idade e gravidade
- Comparação entre população que trabalha e que não trabalha
- Diferenças regionais e por Unidade da Federação
- Relação entre tipo de trabalho e impacto clínico
- Visão macro da população
- Ranking das UFs com maior impacto proporcional

Tecnologias Utilizadas:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

Conclusão:

Os resultados indicam que:

A gravidade clínica aumenta com a idade.
A população economicamente ativa apresentou maior exposição.
Estados com menor estrutura socioeconômica apresentaram maior impacto proporcional.
A pressão sobre o sistema de saúde está fortemente associada aos casos graves.
As diferenças regionais são relevantes para o planejamento de políticas públicas.
