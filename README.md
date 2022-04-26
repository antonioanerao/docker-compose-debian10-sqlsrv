#### Docker-compose with Debian10 + PHP7.4.21 + Drivers sqlsrv + SQL Server 2017 Express (updated at 26/04/2022)


First of all, go to your project folder and create a new volume

      docker volume create --driver local --opt type=none --opt device=$(pwd) --opt o=bind debian10
      
Create a folder named <b>html</b> inside of your project. You can put all public content inside the <b>html</b> folder and let <b>vendors</b> folder in the root directory of your project
