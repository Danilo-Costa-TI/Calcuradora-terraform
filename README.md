Procedimentos

1 - Baixei do github (https://github.com/ahfarmer/calculator) para pasta temp do meu linux vm
2 - Enviei para meu github 
3 - Instalei o node 
4 - instalei yarn
4 - Alterei os links citados com o github baixados e alterei direcionando para meu github
5 - Alterei o arquivo package.json para meu s3 bucket
6 - Apliquei o comando sudo npm install
8 - Apliquei o comando sudo npm run build 
9 - Apliquei comando yarn global add serve
10 - Criei um bucket no AWS S3, via codigo, criando politicas, para permissões de acesso
11 - Código pronto, comandos executados
     terraform init
     terraform plan
     terraform apply
14 - Importei os arquivos do build para o bucket    
15 - Calculadora funcionando via bucket
