create env

conda create -n wineq python=3.7 -y
activate env

conda activate wineq
created a req file

install the req

pip install -r requirements.txt

git init

dvc init

dvc add data_given/

winequality.csv

git add .

git commit -m "first commit"

git add . && git commit -m "update Readme.md"

git remote add origin https://github.com/Aj-AB/Mlops_winequality.git
git branch -M main
git push origin main

________________________________________________
create an artifcats folder

mlflow server command -

mlflow server \
    --backend-store-uri sqlite:///mlflow.db \
    --default-artifact-root ./artifacts \
    --host 0.0.0.0 -p 1234