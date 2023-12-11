# Bikin folder untuk Environment (mesin pyhton)/library
py -m venv (nama environment)
# Bikin folder web untuk aplikasi web.
mkdir web
# Masuk ke Environment (jalanin mesin).
(git bash) -> source (nama environemnt)/Scripts/activate
# Lihat libary environment
pip list
# cek update pip (virtual terminal)
python.exe -m pip install --upgrade pip
# install package flask
pip install flask
# bikin folder structure di dalam folder web
mkdir static templates
# bikin folder css dan js di dalam static
mkdir css js
# jalankan server web
py app.py
# keluar environment untuk matiin mesin
deactivate