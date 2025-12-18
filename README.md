# ⚛️ Simulação da Desigualdade CHSH com Qiskit

Este projeto implementa uma simulação quântica para demonstrar a violação da **Desigualdade CHSH (Clauser-Horne-Shimony-Holt)**, um experimento fundamental que testa o Teorema de Bell.

O código utiliza o framework **Qiskit** para criar circuitos quânticos, gerar emaranhamento e realizar medições em diferentes bases, provando que a mecânica quântica não pode ser explicada por teorias de variáveis ocultas locais.

## 📄 Sobre o Experimento

O experimento CHSH consiste em medir correlações entre dois qubits emaranhados.
* **Limite Clássico (Realismo Local):** $|S| \leq 2$
* **Limite Quântico (Tsirelson):** $S = 2\sqrt{2} \approx 2.82$

Se o valor calculado de $S$ for maior que 2, a desigualdade é violada, confirmando as previsões da mecânica quântica.

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Qiskit** (Criação de circuitos)
* **Qiskit Aer** (Simulação local)
* **Matplotlib** (Visualização gráfica)

## 📦 Instalação

Para rodar este notebook, instale as dependências necessárias executando o seguinte comando no seu terminal ou célula do notebook:

```bash
pip install qiskit qiskit-aer qiskit-ibm-runtime matplotlib pylatexenc
