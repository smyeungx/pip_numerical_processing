python -m pip install -U setuptools pip  
pip install numpy numba scipy matplotlib cupy-cuda12x vispy scikit-image pywin32 opencv-python opencv-contrib-python  
python -m cupyx.tools.install_library --cuda 12.x --library cutensor  
python -m cupyx.tools.install_library --cuda 12.x --library cudnn  
python -m cupyx.tools.install_library --cuda 12.x --library nccl  
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121  
pip sigpy  

  
