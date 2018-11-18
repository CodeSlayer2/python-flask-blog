# python-flask-blog

### Setup

Run following comands in windows terminal(For Windows 7 and above).

    ```PowerShell
    
    Set-ExecutionPolicy -ExecutionPolicy RemoteSigned
    
    python -m venv venv
    
    venv/Scripts/activate
    
    pip install -r requirements.txt
    
    python project.py setup
    
    ```

###Run Project

    ```PowerShell

    venv/Scripts/activate

    python -m smtpd -n -c DebuggingServer localhost:8025

    ```

    In other PowerShell Terminal
    ```PowerShell

    venv/Scripts/activate

    python project.py run

    ```