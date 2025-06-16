# CRMPro-MVC

**Sistema de CRM desenvolvido em ADVPL com arquitetura MVC, totalmente integrado ao ERP TOTVS Protheus.**

## 📋 Descrição

O **CRMPro-MVC** é uma aplicação de gerenciamento de clientes e oportunidades criada com foco no ecossistema TOTVS Protheus. Utiliza o padrão MVC (Model-View-Controller) para organização do código, oferecendo flexibilidade, manutenção facilitada e escalabilidade para o ambiente ADVPL.

## ⚙️ Funcionalidades

- 🧾 Cadastro de múltiplas entidades: clientes, contatos, oportunidades, tarefas, notas e histórico de negociações  
- 🔐 Controle de acesso por permissões de usuário  
- 📊 Tela interativa para edição e visualização de dados de clientes  
- 🔄 Integração com API de terceiros para enriquecimento de dados  
- 🕵️‍♂️ Tabela de log com rastreamento detalhado de alterações  
- 📤 Possibilidade de envio de e-mails automáticos (simulado com mock de envio)

## 🏗️ Estrutura Tecnológica

- **ADVPL**: Linguagem principal
- **MVC Protheus**: Organização das camadas de dados, regra de negócio e interface
- **APIs externas**: Para enriquecimento de dados
- **Tabelas customizadas**: Armazenamento próprio dos dados do CRM

## 🧪 Como testar

> Este projeto depende de ambiente Protheus configurado. Requisitos básicos:

- Protheus 12.1.33 ou superior  
- Appserver configurado com acesso ao dicionário customizado  
- Tabelas customizadas importadas via SX2/SX3  
- Usuário com permissões de administrador

**Execução:**
1. Faça deploy dos fontes `.PRW` nas pastas corretas do Protheus
2. Compile os arquivos via `Appserver` ou `TDS`
3. Acesse o menu customizado via `SIGACRM` (exemplo)
4. Teste os cadastros e funcionalidades a partir da tela inicial

## 📸 Demonstrações

*(adicione prints aqui para mostrar os cadastros, tela principal e visualização de logs)*

## 🔒 Licença

Distribuído sob a [Apache License 2.0](./LICENSE).

## 📬 Contato

Desenvolvido por [Bruno Lebar](https://github.com/Bruno-Lebar-DEV)  
Entre em contato para sugestões ou contribuições!
