# VPN Config Parser

автор:

- Поздеев Владислав Евгеньевич (tg: @wennerryle) (email: wennerryle@gmail.com)

Требования:

- [Python](https://www.python.org/downloads/) (linux: == 3.8; windows: == 3.12)
- Git

## Установка (linux only, python 3.8)

```bash
git clone https://github.com/wennerryle/vpn_config_parser
cd vpn_config_parser
python3.8 -m venv .venv
source .venv/bin/activate # активация виртуального окружения
pip install pandas
pip install pandas-stubs
pip install openpyxl # если нужна способность импорта в xlsx
pip install ./vpn_config_parser-0.1.0-cp38-cp38-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
```

## Установка (windows only, python 3.12)

&#9785; Запускать в Git Bash, иначе не заработает (если вы хотите использовать другой терминал, вы должны будете использовать другой скрипт, расположенный в .venv/Scripts)

```bash
# запускать из под git bash
git clone https://github.com/wennerryle/vpn_config_parser
cd vpn_config_parser
py -m venv .venv
source .venv/Scripts/activate # активация виртуального окружения, если не запускается то откройте в git bash!
pip install pandas
pip install pandas-stubs
pip install openpyxl # если нужна способность импорта в xlsx
pip install ./vpn_config_parser-0.1.0-cp312-none-win_amd64.whl
```

## Подготовка окружения

После развёртывания venv выберите нужную версию интерпретатора в VSCode чтобы работал вывод типов, но не меняйте терминал (он предложит перезапустить терминал - не соглашайтесь, т.к вы уже включили виртуальное окружения, а VSCode выбирает неправильное окружение)

## Запуск

Перед запуском убедитесь что вы находитесь в виртуальном окружении (bash пишет в начале строки __*(.venv)* ... $__ )

```bash
python3.8 ./src # на linux
py ./src # на windows
```
