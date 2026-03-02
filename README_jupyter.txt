# Jupyter

## Installation

```
pip install jupyterlab
```

## Configuration

환경설정 파일을 생성합니다.

```
jupyter notebook --generate-config
```

기본 설정을 진행합니다.

```
vi ~/.jupyter/jupyter_lab_config.py

c.ServerApp.allow_remote_access = True
c.ServerApp.allow_root = True
c.ServerApp.allow_unauthenticated_access = True
c.ServerApp.ip = '0.0.0.0'
```

Jupyter Lab을 실행합니다.

```
jupyter lab
```