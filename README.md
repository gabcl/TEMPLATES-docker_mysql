# Mysql


## Quick Start  

    [Up] docker-compose --env-file .env -f docker-compose.yml up -d --build
    [Down] docker-compose --env-file .env -f docker-compose.yml down


----------------------------------------------
## Env vars  

    MYSQL_TCP_PORT= Default 3307
    MYSQL_ROOT_PASSWORD= Default 0000
    MYSQL_USER= Default dbmanager
    MYSQL_PASSWORD= Default 0000


----------------------------------------------
## GIT

    git init  
    git add .  
    git commit -m "initial"  
    git branch -M main  
    git remote add origin https://github.com/gabcl/template_mysql.git  
    git push -u origin main  
