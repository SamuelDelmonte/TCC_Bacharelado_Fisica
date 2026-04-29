# Reinterpretação da Equação de Schrödinger via Regressão Simbólica

Este repositório contém o código-fonte e os experimentos realizados para o meu Trabalho de Conclusão de Curso (TCC) em Bacharelado de Física. O projeto utiliza **Regressão Simbólica (PySR)** e **Python** para explorar soluções da Equação de Schrödinger em um poço de potencial infinito.

## 📌 Resumo do Projeto
O objetivo principal é demonstrar como algoritmos de aprendizado de máquina podem "redescobrir" leis físicas a partir de dados numéricos, simplificando a manipulação algébrica da mecânica quântica e servindo como ferramenta pedagógica.

## 🛠️ Ferramentas Utilizadas
* **Linguagem:** Python 3.x
* **Manipulação Simbólica:** [SymPy](https://sympy.org)
* **Cálculo Numérico:** [NumPy](https://numpy.org) e [SciPy](https://scipy.org)
* **Regressão Simbólica:** [PySR](https://github.com)
* **Visualização:** [Matplotlib](https://matplotlib.org)

## 🚀 Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook/script principal:
   `jupyter notebook main_simulation.ipynb`

## 📊 Estrutura do Repositório
* `/src`: Scripts Python para geração de dados e treinamento do modelo.
* `/notebooks`: Experimentos interativos e visualização da função de onda $\Psi(x, t)$.
* `/results`: Equações geradas pelo PySR e gráficos de erro (Pareto).
* `artigo_esboço.pdf`: Documento com a fundamentação teórica.

## 📜 Referência Acadêmica
Se este código for útil para sua pesquisa, cite o artigo base:
> *Delmonte, S. C. (2025). Reinterpretação da Equação de Schrödinger via Regressão Simbólica: Uma Abordagem Computacional com Python.*
