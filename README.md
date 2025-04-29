# Previsão de Colesterol com Machine Learning

## Descrição
Este projeto usa Machine Learning para prever o nível de colesterol de uma pessoa com base em variáveis como:
- Grupo sanguíneo
- Fumante ou não
- Nível de atividade física
- Idade
- Peso
- Altura

O modelo foi treinado em Python e disponibilizado com uma interface web usando Gradio.

## Como executar
1. Instale as dependências: pip install pandas numpy scikit-learn gradio
2. Execute o notebook do app: jupyter notebook app_gradio_colesterol.ipynb
    Ou, se exportar para .py, basta rodar: python app_gradio_colesterol.py
3. Acesse no navegador: Após rodar, o Gradio exibirá um link (ex: http://127.0.0.1:7860) para usar a interface.

## Arquivos
- modelo_colesterol.ipynb – Treina o modelo e salva como .pkl
- app_gradio_colesterol.ipynb – Cria uma interface web para usar o modelo

## Contribuição
Esse projeto foi feito como aprendizado no curso de Engenharia de Software e está aberto para a comunidade.