CARLA on CAVE
=========================================
Steps for virtual enviroment
 C:\Users\AUC\AppData\Local\Programs\Python\Python37\python -m venv venv

 cd "C:\Farahat\P3.7_ENV\venv”

 Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

 Scripts\activate

 .. figure:: imagesim/w39.png
   :width: 400px
   :align: center
 .. raw:: html

   <div style="margin-bottom: 30px;"></div>

Start carla engine
 cd C:\Farahat\CARLA\Newfolder\WindowsNoEditor

 .\CarlaUE4.exe

Start Client with your customization
 cd “C:\Farahat\P3.7_ENV\PythonAPI\examples”  or cd “C:\Farahat\P3.7_ENV\CAVE_Dev”

 python `CAVE.py <http://CAVE.py>`_ or any other name !

Steps for the  CAVE
 - open powershell (blue background)
 - C:\Users\admin\AppData\Local\Programs\Python\Python37\python -m venv venv
 - cd "D:\CarlaServer\CARLA_ENV”
 - Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
 - myenv\Scripts\activate
 - cd "D:\CarlaServer\WindowsNoEditor”
 - .\CarlaUE4.exe
 - cd “D:\CarlaServer\CARLA_ENV”
 - python CAVE.py