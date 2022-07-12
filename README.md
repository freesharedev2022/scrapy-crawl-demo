# install
config database from file .env.example
require python >3.9.0

install venv
```
python3 -m venv venv
```

open bash
```
source venv/bin/activate
```

install lib 
```
pip3 install -r requirements.txt
```

run demo
```
scrapy crawl vnexpress
```

if you want deactive venv
```
deactivate
```