# eth_wallets_generator
Массово генерирует кошельки, сохраняет сразу в 4 файла. Запустите, введите количество.  
  
```wallets.txt``` - только кошельки  
```private_key.txt``` - только приватники  
```seeds.txt``` - только сид-фразы  

```wallets.csv``` - таблица, в формате address_wallet:private_key:seed

# Установка
1. Создаем виртуальное окружение
```
python -m venv venv
.\venv\Scripts\activate
```

2. Устанавливаем все необходимые зависимости:
```
pip install -r requirements.txt
```

3. Запускаем скрипт (при запуске в консоли указываем кол-во кошельков)

```
python main.py 
```