# Jupyter Notebook Default Path 변경

**Anaconda Prompt 실행**


(base) D:\googledrive\bitnine\DQM\DEV_PARSER>jupyter notebook --generate-config
Writing default config to: C:\Users\BB\.jupyter\jupyter_notebook_config.py

(base) D:\googledrive\bitnine\DQM\DEV_PARSER>notepad C:\Users\BB\.jupyter\jupyter_notebook_config.py

(base) D:\googledrive\bitnine\DQM\DEV_PARSER>


**jupyter_notebook_config.py 편집**

c.NotebookApp.notebook_dir = 'D:\\googledrive\\0.Dev\\JupyterNB_root'


**jupyter Notebook (Anaconda3) 바로가기(시작위치 열기 > 속성) **
"%USERPROFILE%/" , HOMEPATH% 삭제

대상(T): D:\ProgramData\Anaconda3\python.exe D:\ProgramData\Anaconda3\cwp.py D:\ProgramData\Anaconda3 D:\ProgramData\Anaconda3\python.exe 
D:\ProgramData\Anaconda3\Scripts\jupyter-notebook-script.py "%USERPROFILE%/"

시작 위치(S): %HOMEPATH%

