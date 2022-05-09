## Cadastro de Pessoa Física e Jurídica
---
### Troppo Desenvolvimento de Software
### ClientLab Gestão de Clientes
### André Moura Pedroso
### SENAI / 2022
---
👨‍💻️
Sistema de cadastro de pessoa física e jurídica que permite o cadastro, consulta, listagem e geração de cópias em .txt e .csv.

---
👨‍💻️
Descrição: Geração de listas de pessoas físicas e jurídicas.

---
## 🔮 Features:
```bash
❯ Cadastrar Clientes

O sistema apresentará a opção de cadastrar clientes inserindo informações para pessoa física e jurídica.

❯ Gerar Lista dos Clientes Cadastrados

O sistema armazenará as informações em listas separadas para pessoa física e jurídica e poderão ser consultadas.

❯ Criar Arquivo .txt

O sistema oferecerá a opção de guardar as informações cadastradas em um arquivo .txt para pessoa física e jurídica.

❯ Criar Arquivo .csv

O sistema oferecerá a opção de guardar as informações cadastradas em um arquivo .csv para pessoa física e jurídica.
```
---
## 👨‍💻️ Tecnologias Utilizadas
Esse projeto foi criado utilizando as tecnologias:
### Back-End
- [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
- [.NET](https://dotnet.microsoft.com/download)
### Editor
- [Visual Studio Code](https://code.visualstudio.com/)
---
## 📦️ Como rodar o projeto
Clone o projeto com o comando abaixo:
```bash
  # Clone o repositório
  ❯ git clone https://github.com/[usuario]/[nome-projeto].git
	# Entre no diretório
  ❯ cd [nome-projeto]
	# Execute o projeto
  ❯ dotnet run
```
## Objetivo :
### O C# vai possibiltar o armazenamento e gerenciamento de dados.
### O .NET vai facilitar o desenvolvimento do sistema.
### O Vsual Studio Code vai possibilitar o desenho do sistema.
---
## Justificativa :
### O C# através da programação orientada a objeto permite o desenvolvimento de sistemas para Banco de Dados de forma eficaz e prática.
### O .NET é um framework para a criação de sistemas com bibliotecas específicas.
### O Vsual Studio Code é uma IDE adaptada para várias ferramentas.
---
## 👨‍💻️ Organização do Projeto
```bash
❯ Interfaces

    > IPessoa
        Métodos: PagarImposto.

    > IPessoaFisica
        Métodos: ValidarDataNascimento.

    > IPessoaJuridica
        Métodos: validarCnpj.

❯ Classes

    > Pessoa
        Atributos: nome, endereco e rendimento.
        Métodos: PagarImposto.

    > PessoaFisica
        Atributos: nome, endereco, rendimento, cpf e dataNascimento.
        Métodos: ValidarDataNascimento e PagarImposto.
  
    > PessoaJuridica
        Atributos: nome, endereco, rendimento, cnpj e razaoSocial.
        Métodos: validarCnpj e PagarImposto.

    > Endereco
        Atributos: logradouro, numero, complemento e endComercial.

❯ Arquivo Main

    > Program.cs
        Contém toda a lógica para a interface e aplicações no sistema.
```
---
## 👨‍💻️ Pré-requisitos de instalação
Ter um computador com o sistema operacional Windows 10 e as seguintes ferramentas instaladas:
### Instalar:
- [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
- [.NET](https://dotnet.microsoft.com/download)
- [Git](https://git-scm.com/)
- [GitHub](https://github.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
### Passo a passo:
- Instalar dotnet
https://dotnet.microsoft.com/en-us/download
- Instalar sdk e runtime
- Baixar extensões no vscode : 
C# - Microsoft,
C# Extensions – jchannon,
C# Snippets – Jorge Serrano,
C# XML – Keisuke Kato,
Rainbow Brackets – 2qua,
Material Icon Theme – Philipp kief.
---
## 📦️ Execução da aplicação
Clone o projeto com o comando abaixo:
```bash
  # Clone o repositório
  ❯ git clone https://github.com/[usuario]/[nome-projeto].git
	# Entre no diretório
  ❯ cd [nome-projeto]
	# Execute o projeto
  ❯ dotnet run
  ```
---
## 👨‍💻️ Erros comuns
É extremamente recomendado que o sistema operacional seja o Windows 10, as versões das ferramentas devem estar atualizadas e compatíveis. Todas as extensões do VSCode que estão no descritivo da instalação devem ser baixadas.

---
## 👨‍💻️ Contribuidores
- [SENAI](https://senaiead.senai.br/sp)
- André Moura Pedroso
ankpedroso@gmail.com
- [Andpedroso](https://github.com/)
---
