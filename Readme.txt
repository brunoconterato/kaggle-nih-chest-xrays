Execução do desafio https://www.kaggle.com/nih-chest-xrays

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

Resumo de métricas obtidas:
Epoch 100/100
3513/3513 [==============================] - 15s 4ms/step - loss: 0.1642 - acc: 0.9402 - f1_score: 0.9592 - val_loss: 0.1413 - val_acc: 0.9428 - val_f1_score: 0.9614
Accuracy:  0.9427839342495196

Qualquer problema, entre em contato!
