python -m pip install -U setuptools pip  
pip install numpy scipy matplotlib cupy-cuda12x vispy  
python -m cupyx.tools.install_library --cuda 12.x --library cutensor  
python -m cupyx.tools.install_library --cuda 12.x --library cudnn  
python -m cupyx.tools.install_library --cuda 12.x --library nccl  
pip sigpy  

