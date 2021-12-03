sudo apt update
sudo apt install python3.9
sudo  apt-get install python3.9-dev python3.9-venv

git clone https://github.com/t0in4/MoscowSecureTraffic

python3.9 -m venv MoscowSecureTraffic

source MoscowSecureTraffic/bin/activate

cd MoscowSecureTraffic

pip install -r requirements.txt

cd telegram_bot

vim telegram_bot.py

на строке 280 добавить ключ для TELEGRAM_TOKEN = os.environ.get("TELEGRAM_TOKEN", "ключ взятый у @botfather")






