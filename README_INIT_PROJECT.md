# jupyterlab-extension
Hello world of jupyterlab extension

## Initialize
### Pre-install python requirements
```shell
pip install -r requirements.txt
```
### Create extension from template
<h4>You can choose either way to create extension</h4>
- Init with Archive File [extension-template.tar.gz :v4.2.0](https://github.com/jupyterlab/extension-template/archive/refs/tags/v4.2.0.tar.gz)
```shell
    mkdir labext-template
    tar -zxf extension-template.tar.gz -C labext-template
    python init_extension.py
```
- Init with <code>copier</code> to create from remote repository
```shell
copier copy https://github.com/jupyterlab/extension-template .
```
- Build and install extension for development
```shell
pip install -ve .
```
- Star jupyter lab
```shell
jupyter lab
```

