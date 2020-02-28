# Jupyter lab 서버 설치

많은 삽질끝에 정리하는 Html에서 주피터랩/주피터 노트북 열기



1. 방화벽 열기
*꼭 시작할때 하자..

    sudo ufw allow <port>

2. jupyter_notebook_config.py 수정

    c = get_config()
c.NotebookApp.password ='sha1:7be578705064:e9c5f4f0697eaf188de29fa3b17b83364cb27c48'
# The IP address the notebook server will listen on. 
# c.NotebookApp.ip = 'localhost' 
c.NotebookApp.ip = '10.82.12.232' 
# c.NotebookApp.port_retries = 50 
c.NotebookApp.port_retries = 8893



3.
  
