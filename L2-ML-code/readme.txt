cài Miniconda chọn PATH
mở cmd
nhập các lệnh
conda config --append channels conda-forge
conda create -n course python=3.8
conda activate course
pip install -r requirements.txt
jupyter lab