# Reconhecedor de formas

Simples script em python para reconhecer e categorizar formas geométricas passadas por vídeo. 

## Instalação

### 1º Passo: Instalação do ambiente

Crie uma pasta e em seguida execute o comando:.

```bash
python3 venv -m ambient
```
Depois ative o ambiente:

```bash
source ambient/bin/activate
```

### 2º Passo: Instalação de bibliotecas

Com o projeto dentro da pasta, rode o comando para instalar as libs:

```bash
pip3 install -r requirements.txt
```

## Uso

caso queira testar outros videos, basta alterar uma das variaveis abaixo, passando o caminho do novo video

```python
import foobar

import cv2 as cv

VIDEO_1 = 'video-1.mp4'
VIDEO_2 = 'video-2.mp4'
)
```
Depois execute:
```bash
python3 main.py
```
## License
[MIT](https://choosealicense.com/licenses/mit/)