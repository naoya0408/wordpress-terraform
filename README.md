# wordpress-terraform
![Untitled-2](https://user-images.githubusercontent.com/40429887/70862664-693c7200-1f82-11ea-8e9c-27c43d89a360.png)


## terraformの実行
* terraform
```
% terraform init
% terraform apply
```
## hostsに作成されたEC2のパブリックIPを指定する
```
[wordpress]
3.112.222.233
52.198.31.60
```
## ansibleの実行
```
% ansible-playbook -i hosts playbook.yml
```
