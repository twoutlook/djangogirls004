# 使用 c9.io 再開發

## 沒有 djangogirls004 的 folder

## need to setup myvenv 

    sudo apt install python3.5-venv
    python3.5 -m venv myvenv
    source myvenv/bin/activate
    pip install django~=1.9.0
    pip install --upgrade pip

## run server 
    
    ./manage.py runserver $IP:$PORT
    
## database
db.sqlite3 可以簡單複製過來

## 確認git push -u origin master 是自動的
儘管有這段字 Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
實際上還是完成 push 的動作


   
    