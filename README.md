# VPN Config Parser

автор(ы):

- Поздеев Владислав Евгеньевич (tg: @wennerryle) (email: wennerryle@gmail.com)

Требования:

- [Python](https://www.python.org/downloads/) (== 3.8)
- Git

#### Установка (linux only)

```bash
git clone https://github.com/wennerryle/vpn_config_parser
cd vpn_config_parser
python3.8 -m venv .venv
source .venv/bin/activate
pip install pandas
pip install pandas-stubs
pip install openpyxl # если нужна способность импорта в xlsx
pip install ./vpn_config_parser-0.1.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
```

После установки зависимостей и развёртывания venv выберите нужную версию интерпретатора в VSCode
