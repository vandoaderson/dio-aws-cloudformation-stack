# Implementando sua Primeira Stack com AWS CloudFormation

## 📚 Descrição do Projeto

Este repositório foi desenvolvido como parte do desafio **"Implementando sua Primeira Stack com AWS CloudFormation"**, proposto pela DIO.

O objetivo deste laboratório é aplicar os conceitos fundamentais do **AWS CloudFormation**, utilizando infraestrutura como código (Infrastructure as Code - IaC) para automatizar o provisionamento de recursos na AWS por meio de templates declarativos.

Além da implementação prática, este projeto busca documentar os conhecimentos adquiridos durante as aulas, servindo como material de consulta para estudos futuros e novas implementações em ambientes reais.

---

## 🎯 Objetivos de Aprendizagem

Ao concluir este desafio, foram desenvolvidas as seguintes competências:

* Aplicação prática dos conceitos de **Infrastructure as Code (IaC)**;
* Criação e gerenciamento de recursos utilizando **AWS CloudFormation**;
* Organização e documentação de processos técnicos;
* Utilização do **GitHub** para versionamento e compartilhamento de conhecimento;
* Consolidação dos conhecimentos adquiridos ao longo do laboratório.

---

## ☁️ O que é o AWS CloudFormation?

O **AWS CloudFormation** é um serviço da AWS que permite modelar, provisionar e gerenciar recursos da nuvem por meio de arquivos de configuração escritos em **YAML** ou **JSON**.

Com ele, é possível definir toda a infraestrutura necessária para uma aplicação de forma automatizada, garantindo maior padronização, repetibilidade e redução de erros manuais.

### Principais benefícios

* Infraestrutura como código;
* Automação do provisionamento de recursos;
* Versionamento da infraestrutura;
* Reutilização de templates;
* Facilidade na replicação de ambientes.

---

## 🏗️ Etapas Realizadas

Durante a execução do laboratório, foram realizadas as seguintes atividades:

1. Estudo dos conceitos fundamentais do AWS CloudFormation;
2. Análise da estrutura de um template CloudFormation;
3. Criação da primeira Stack na AWS;
4. Provisionamento automatizado dos recursos definidos no template;
5. Acompanhamento dos eventos de criação da Stack;
6. Validação dos recursos implantados;
7. Registro das evidências e documentação do processo.

---

## 📁 Estrutura do Repositório

```text
.
├── README.md
├── templates/
│   └── stack.yaml
├── images/
│   ├── stack-creation.png
│   ├── resources-created.png
│   └── cloudformation-console.png
└── notes/
    └── aprendizados.md
```

---

## 🚀 Como executar uma Stack utilizando CloudFormation

1. Acesse o console da AWS;
2. Navegue até o serviço **CloudFormation**;
3. Clique em **Create Stack**;
4. Escolha a opção **With new resources (standard)**;
5. Faça o upload do template YAML/JSON;
6. Informe o nome da Stack;
7. Configure os parâmetros necessários;
8. Revise as configurações;
9. Clique em **Submit** para iniciar a criação;
10. Acompanhe os eventos até que o status seja exibido como **CREATE_COMPLETE**.

---

## 🧠 Aprendizados Obtidos

Durante este desafio, foi possível compreender a importância da automação da infraestrutura em ambientes de nuvem.

A utilização do CloudFormation demonstra como a infraestrutura pode ser tratada como código, permitindo maior controle sobre mudanças, padronização entre ambientes e facilidade na reprodução de arquiteturas.

Além disso, o laboratório reforçou boas práticas relacionadas à documentação técnica e ao uso do GitHub como ferramenta de compartilhamento de conhecimento.

---

## 📸 Evidências

As capturas de tela utilizadas para documentar a execução do laboratório podem ser encontradas na pasta:

```text
/images
```

Sugestões de evidências:

* Tela de criação da Stack;
* Eventos de execução;
* Recursos provisionados;
* Status final `CREATE_COMPLETE`.

---

## 📚 Referências

* Documentação Oficial da AWS CloudFormation;
* Materiais disponibilizados pela DIO durante o laboratório;
* Documentação oficial do GitHub sobre Markdown.

---

## 👨‍💻 Autor

Desenvolvido por **Vando Alves** durante os estudos da formação **Fundamentos de Cloud com AWS**, promovida pela **DIO (Digital Innovation One)**.

GitHub: https://github.com/vandoaderson
