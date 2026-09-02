# env
Создаем папку и заходим в нее
Создаем файл с зависимостями
```bash
touch requirements.txt
```

Открываем в nano
```bash
nano requirements.txt
```

Прописываем, например:
```
numpy
pandas
notebook
```
`Ctrl+O`, `Enter`, `Ctrl+X`

Создаем окружение
```bash
python3 -m venv .venv
```
Активируем
```bash
source .venv/bin/activate
```
Деактивируем конду, на всякий случай:
```bash
conda deactivate
```
Обновляем пип
```bash
pip install --upgrade pip
```
Устанавливаем зависимости
```bash
pip install -r requirements.txt
```
