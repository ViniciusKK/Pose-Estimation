# Pose Estimation para bois


## Introdução

Este repositório contém um projeto de **Pose Estimation** (Estimativa de Pose) aplicado a animais, especificamente a bois. A estimativa de pose é uma técnica de visão computacional que identifica a posição e a orientação das partes do corpo em imagens ou vídeos. Embora o código utilizado tenha sido originalmente treinado para detectar poses humanas, este projeto explora sua aplicação em animais, destacando os desafios e as limitações dessa abordagem.

## Tecnologias Utilizadas

- **Python 3.8+**
- **OpenCV**: Para processamento de imagens.
- **MediaPipe**: Biblioteca do Google para soluções de visão computacional, incluindo estimativa de pose.
- **Matplotlib**: Para visualização de resultados.

## Limitações

Dataset Diferente: O modelo foi treinado exclusivamente com dados humanos, o que limita sua capacidade de generalização para animais.

Anatomia Variável: Animais possuem estruturas corporais diferentes, exigindo modelos específicos para cada espécie.

## Melhorias Futuras

Para obter resultados mais precisos na estimativa de pose de animais, as seguintes melhorias são recomendadas:

Treinamento com Dataset Adequado:
Utilizar um dataset específico para animais, como o Animal-Pose Dataset, para treinar ou ajustar o modelo. Porém, sua importação e uso no Google Colab se demonstrou um desafio, sem muitas referências online para auxiliar.

Aprimoramento do Pré-processamento:
Melhorar o pré-processamento das imagens, como ajuste de iluminação e remoção de ruídos, para facilitar a detecção dos pontos de referência.

