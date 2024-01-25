# Visão computacional em jogos de basquete

Táticas e estatísticas em equipes profissionais de basquete são amplamente utilizadas. Esta operação pode ser otimizada e acelerada por um sistema automático de visão computacional. Nosso objetivo é desenvolver um sistema capaz de rastrear ações e entender jogos de basquete usando abordagens de visão computacional e modelos de aprendizado profundo, como o Detectron2. Nosso sistema rastreia trajetórias de jogadores a partir de vídeos e as retifica para um campo de basquete padrão, mostrando também o jogador que possui a bola.

## Ferramentas
- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/)
- [Detectron2](https://github.com/facebookresearch/detectron2)
- [Pytorch-Cuda](https://pytorch.org/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

## Detalhes dos arquivos

- ```main.py```: Inicializa classes e carrega ou retifica as imagens necessárias
- ```video_handler.py```: Gerencia o procedimento de leitura de quadros do vídeo de entrada
- ```rectify_court.py```:  Produz homografias, imagens retificadas, panoramas
- ```ball_detect_track.py```: Detecta e rastreia a bola
- ```player_detection.py```: Detecta e rastreia os jogadores
- ```player.py```: Contém a classe ```Player```
- ```tools```: Funções auxiliares
- ```resources```: Contém imagens modelo e vídeo de entrada
