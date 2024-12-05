# 📊 Calculadora de IMC com Streamlit

## Descrição do Projeto
Este é um aplicativo interativo desenvolvido com **Streamlit** para calcular o **Índice de Massa Corporal (IMC)**. Ele permite que os usuários insiram seus dados (peso e altura) e obtenham informações detalhadas sobre sua classificação de saúde, com base no IMC.

Além disso, o projeto inclui:
- Um gráfico interativo para visualizar as classificações de IMC.
- Dicas personalizadas baseadas no resultado.
- Comparação do IMC atual com um valor ideal.

## 🛠️ Tecnologias Utilizadas
- **Python**: Linguagem principal para lógica do aplicativo.
- **Streamlit**: Framework para criação de interfaces web interativas.
- **Matplotlib**: Biblioteca para geração de gráficos.

## 💻 Como Rodar o Projeto

### Passo a Passo
1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/calculadora-imc.git
cd calculadora-imc
```
2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv .venv
source .venv/Scripts/activate  # Para Windows
source venv/bin/activate  # Para Linux/Mac

```

3. Instale as dependências:
```bash
pip install streamlit
pip install matplotlib
```

4. Inicie o aplicativo
```bash	
streamlit run main.py
```

## 📝 Funcionalidades
- Entrada de dados: Permite que o usuário insira seu peso (em kg) e altura (em metros).
- Cálculo do IMC: O aplicativo calcula o IMC com base nos dados fornecidos e classifica em uma das categorias abaixo.
- Classificação do IMC:
    - Abaixo do peso
    - Peso ideal
    - Sobrepeso
    - Obesidade
    - Obesidade mórbida
- Comparação com IMC ideal: O valor calculado é comparado com o IMC ideal de 21.7.
- Exibição de resultados: O resultado do cálculo do IMC é mostrado em formato de texto e gráfico.
- Exibição de métricas: O aplicativo mostra as métricas de classificação do IMC em cards interativos para facilitar a visualização.
