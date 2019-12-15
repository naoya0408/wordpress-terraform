# wordpress-terraform

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
