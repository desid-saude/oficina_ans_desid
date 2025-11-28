# Taxa de Cesarianas - Análise de Dados TISS/ANS

## Sobre este repositório

Este repositório contém os arquivos desenvolvidos como material prático para a **Oficina Bases de Dados TISS e DIOPS da ANS**, realizada em 28 de novembro de 2025 no Tribunal de Contas da União, em Brasília.

## Parceria DESID e ANS

O material foi desenvolvido em parceria entre:

- **DESID** (Departamento de Economia e Desenvolvimento em Saúde do Tribunal de Contas da União)
- **ANS** (Agência Nacional de Saúde Suplementar)

Essa colaboração visa construir capacidades perenes para análise de dados abertos em saúde suplementar, fortalecendo estudos sobre as relações público-privadas em saúde.

## Conteúdo

Os arquivos deste repositório implementam uma atividade prática da oficina:

- **`TaxaCesarea.ipynb`** - Notebook original em Python
- **`TaxaCesarea_R.ipynb`** - Mesmo notebook convertido para R
- **`Ementa-Oficina-de-Dados-da-ANS.docx`** - Documentação completa da oficina

## O que o código faz

Os notebooks demonstram a análise de dados do TISS (Troca de Informações na Saúde Suplementar) para construir um indicador de taxa de cesarianas por UF, integrando informações de diferentes bases de dados da ANS.

### Principais etapas:

1. Download automatizado de dados TISS 2024 via API dos Dados Abertos
2. Limpeza, tratamento e harmonização de dados
3. Identificação de outliers e valores atípicos
4. Construção do indicador de taxa de cesariana
5. Análises descritivas e visualizações

## Linguagens disponíveis

- **Python** (`TaxaCesarea.ipynb`) - com pandas, plotly, matplotlib
- **R** (`TaxaCesarea_R.ipynb`) - com tidyverse, ggplot2, plotly

Ambos rodam nativamente no Google Colab.

## Origem dos dados

Os dados utilizados são públicos e estão disponíveis em:
- **Portal Brasileiro de Dados Abertos**: https://dados.gov.br/

## Referências

- Documentação técnica do TISS: Portal de Dados Abertos da ANS
- Ementa da oficina: `Ementa-Oficina-de-Dados-da-ANS.docx`

---

*Desenvolvido para a Oficina de Dados da ANS - DESID/TCU - Novembro de 2025*
