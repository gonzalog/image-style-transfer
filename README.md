# Image Style Transfer

Based on [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)

# Run on Linux

```bash

 git clone https://github.com/gonzalog/image-style-transfer.git

 cd image-style-transfer

 python -m venv ./venv

 source ./venv/bin/activate

 pip install -r requirements.txt

 python main.py /path/to/your/content/image.jpg ~/Documents/GAN/01/starry-night.jpg 5000
```

# Example

## Content
<img height="400" src="examples/tortoise.jpg">

## Style
<img height="400" src="examples/starry-night.jpg">

## Result
<img height="400" width="579" style="object-fit: cover;" src="examples/starry-tortoise.png">
