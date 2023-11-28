# chatBot

## instalando dependências para rodar local
```bash
## Install tensorflow
python3 -m pip install tensorflow[and-cuda]
python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
# Install pytorch
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```