# devops-netology
line

**/.terraform/*
игнорируются все файлы в каталогах .terraform во всех вышестоящих каталогах

*.tfstate
*.tfstate.*
все файлы .tfstate и файлы .tfstate с любым расширением

crash.log
файлы crash.log

*.tfvars
все файлы .tfvars

override.tf
override.tf.json
*_override.tf
*_override.tf.json
игнорировать файлы override.tf override.tf.json и файлы с окончанием override.tf и override.tf.json

.terraformrc
terraform.rc
игнорировать данные файлы