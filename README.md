# devops-netology
for test

Благодоря файлику .gitingnore
Из системы контроля версий будут исключены все файлы с раширением .tfstate либо такого плана файлы name.tfstate.old

Так же будут исключены все файлы имеюшие расширение: 
- tfvars
- tfvars.json 

Так же будут исключены конкретные файлы:
- override.tf
- override.tf.json
- .terraformrc
- terraform.rc
- crash.log
- А так же файлы которые начинаются на crash. и заканчиваются на .log

Так же будет исключена любая директория .terraform и любые файлы начинающиеся на crash. и заканчивающиеся на .log

Будут исключены любые файлы заканчивающиеся на: 
- _override.tf
- _override.tf.json

