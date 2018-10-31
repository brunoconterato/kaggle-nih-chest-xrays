Precisa baixar datasets em: 
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

Como executar:

1. Precisa criar a estrutura de pastas (no diret�rio raiz):
- images
- images/normal
- images/pneumonia
e incluir todas as imagens (treino, teste e valida��o) nessas pastas

2. Executar o script prepare_data_1_file.ipynb.
Este script cria o arquivo chest_xray.hdf5 com os datasets j� separados.
Por simplicidade, as imagens foram separadas apenas em Treino e Teste (para melhorar a an�lise, falta separa tamb�m a Valida��o).

3. Executar o script desafio x_ray.ipynb

Os arquivos j� vem com resultados de teste feitos no Crestle.