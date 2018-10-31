Precisa baixar datasets em: 
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

Como executar:

1. Precisa criar a estrutura de pastas (no diretório raiz):
- images
- images/normal
- images/pneumonia
e incluir todas as imagens (treino, teste e validação) nessas pastas

2. Executar o script prepare_data_1_file.ipynb.
Este script cria o arquivo chest_xray.hdf5 com os datasets já separados.
Por simplicidade, as imagens foram separadas apenas em Treino e Teste (para melhorar a análise, falta separar também a Validação).

3. Executar o script desafio x_ray.ipynb

Os arquivos já vem com resultados de teste feitos no Crestle.
