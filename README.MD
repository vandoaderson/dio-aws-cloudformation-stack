# Implementando sua Primeira Stack com AWS CloudFormation

## 📚 Descrição do Projeto

Este repositório foi desenvolvido como parte do desafio **"Implementando sua Primeira Stack com AWS CloudFormation"**, proposto pela DIO.

O objetivo deste laboratório foi colocar em prática os conceitos de **Infrastructure as Code (IaC)** utilizando o **AWS CloudFormation**, automatizando o provisionamento de recursos na AWS através de templates declarativos escritos em YAML.

Durante a prática, foram criadas diferentes stacks para explorar cenários comuns de infraestrutura em nuvem, incluindo instâncias EC2, configuração de servidores Apache, regras de firewall e gerenciamento de usuários e grupos com integração ao Amazon S3.

---

## 🎯 Objetivos de Aprendizagem

Ao concluir este desafio, foram desenvolvidas as seguintes competências:

* Aplicar os conceitos de Infrastructure as Code (IaC);
* Criar e gerenciar recursos utilizando AWS CloudFormation;
* Automatizar a configuração de ambientes na AWS;
* Organizar templates reutilizáveis utilizando YAML;
* Documentar processos técnicos utilizando GitHub e Markdown.

---

## ☁️ Sobre o AWS CloudFormation

O AWS CloudFormation é um serviço que permite modelar, provisionar e gerenciar recursos da AWS por meio de código.

Com ele, é possível definir toda a infraestrutura necessária para uma aplicação utilizando arquivos YAML ou JSON, proporcionando maior padronização, repetibilidade e facilidade de manutenção dos ambientes.

### Benefícios do CloudFormation

* Infraestrutura como código;
* Automação do provisionamento;
* Reutilização de templates;
* Controle de versão da infraestrutura;
* Redução de erros manuais;
* Facilidade para replicar ambientes.

---

## 📂 Estrutura do Repositório

```text
.
├── 01-EC2.yaml
├── 02-Apache.yaml
├── 03-Firewall.yaml
├── 04-EC2_S3_UserGroup.yaml
└── README.md
```

---

## 📄 Templates Desenvolvidos

### 01 - EC2

Template responsável pela criação de uma instância EC2 básica utilizando o AWS CloudFormation.

**Conceitos praticados:**

* Criação de instâncias EC2;
* Definição de propriedades da instância;
* Provisionamento automatizado de recursos.

---

### 02 - Apache

Template utilizado para automatizar a instalação e configuração do servidor web Apache em uma instância EC2.

**Conceitos praticados:**

* Uso de User Data;
* Inicialização automática de serviços;
* Configuração de servidores web via CloudFormation.

---

### 03 - Firewall

Template responsável pela configuração das regras de acesso à infraestrutura.

**Conceitos praticados:**

* Criação de Security Groups;
* Definição de portas liberadas;
* Controle de tráfego de entrada e saída.

---

### 04 - EC2, S3, Usuários e Grupos

Template mais completo do laboratório, envolvendo múltiplos recursos da AWS.

**Conceitos praticados:**

* Provisionamento de instâncias EC2;
* Criação de buckets S3;
* Gerenciamento de usuários IAM;
* Criação e associação de grupos IAM;
* Definição de permissões de acesso.

---

## 🚀 Como executar os templates

1. Acesse o console da AWS;
2. Navegue até o serviço **CloudFormation**;
3. Clique em **Create Stack**;
4. Escolha **With new resources (standard)**;
5. Faça o upload do template desejado (`.yaml`);
6. Informe o nome da Stack;
7. Configure os parâmetros necessários;
8. Revise as configurações;
9. Clique em **Submit**;
10. Aguarde até que o status seja exibido como **CREATE_COMPLETE**.

---

## 🧠 Aprendizados Obtidos

Durante este desafio, foi possível compreender como o CloudFormation simplifica o gerenciamento de infraestrutura através da automação.

A criação de diferentes templates permitiu visualizar, na prática, como diversos serviços da AWS podem ser provisionados e configurados de forma padronizada e reproduzível.

Além disso, o laboratório reforçou a importância da documentação técnica e do versionamento utilizando GitHub.

---

## 📸 Evidências

Caso deseje complementar este repositório, recomenda-se adicionar capturas de tela demonstrando:

* Criação das stacks;
* Eventos de execução do CloudFormation;
* Recursos provisionados;
* Status `CREATE_COMPLETE`.

As imagens podem ser organizadas em uma pasta `/images`.

---

## 📚 Referências

* Documentação Oficial do AWS CloudFormation;
* Materiais disponibilizados pela DIO;
* Documentação oficial do GitHub Markdown.

---

## 👨‍💻 Autor

**Vando Alves**

Desafio desenvolvido durante a formação **Fundamentos de Cloud com AWS**, oferecida pela **DIO (Digital Innovation One)**.

GitHub: https://github.com/vandoaderson
