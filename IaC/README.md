<h1>Fundamentos da IaC</h1>

<h3>Parte teorica:</h3>

[O que é IaC](O%20que%20é%20IaC.txt)

<h3>Parte pratica:</h3>

<ul>
  <li>Instalado o Terraform</li>
  <li>Instalado o Instalado Ansible</li>
  <li>Instalado o Instalado Paramiko</li>
  <li>Criado um Usuário na AWS (terraform-user)</li>
  <li>Criado um Grupo de Usuários na AWS (terraform-admins) com Políticas anexadas para nossa aplicação.</li>

  <h3 align="center">Configuração Terraform</h3>

```bash
export AWS_ACCESS_KEY_ID=MINHAKEY
export AWS_SECRET_ACCESS_KEY=MINHAKEY
terraform init
terraform plan
terraform apply
```

</ul>

<div align="left">
  <h3>Instância na AWS:</h3>
  <img height="320" src="https://raw.githubusercontent.com/GustavoVieiraa/Infraestrutura-como-Codigo-Preparando-Maquinas-na-AWS-com-Ansible-e-Terraform/refs/heads/main/IaC/archives/instanciaTerraform.png">
</div>

<div align="left">
  <h3>IAM User na AWS:</h3>
  <img height="300" src="https://raw.githubusercontent.com/GustavoVieiraa/Infraestrutura-como-Codigo-Preparando-Maquinas-na-AWS-com-Ansible-e-Terraform/refs/heads/main/IaC/archives/terraform%20user.png">
</div>

<div align="center">
  <h3>Ferramentas:</h3>
  <img height="400" src="https://raw.githubusercontent.com/GustavoVieiraa/Infraestrutura-como-Codigo-Preparando-Maquinas-na-AWS-com-Ansible-e-Terraform/refs/heads/main/IaC/archives/Ferramentas.png">
</div>
