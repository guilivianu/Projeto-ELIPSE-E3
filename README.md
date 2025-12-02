# Projeto ELIPSE E3 – TreinamentoE3

Projeto desenvolvido como parte das entregas do curso **“Elipse E3 Desenvolvedores – Versão 6.8”**.

Este repositório contém um exemplo completo de aplicação em Elipse E3, incluindo telas gráficas, biblioteca de objetos, comunicação Modbus e banco de dados para registro de informações.

---

## 🎯 Objetivo do projeto

- Exercitar os conceitos básicos e intermediários de desenvolvimento no **Elipse E3 6.8**
- Demonstrar:
  - Criação de telas (sinóticos, telas de operação, etc.)
  - Uso de **bibliotecas (.lib)** com objetos reutilizáveis
  - Comunicação com dispositivos via **Modbus**
  - Registro de dados em **banco de dados (.mdb)**

---

## 📂 Estrutura do projeto

Na pasta principal `TreinamentoE3` você encontrará:

- `TreinamentoE3.prj`  
  Arquivo principal do projeto Elipse E3 (projeto do supervisório).

- `TreinamentoE3.dom`  
  Domínio do projeto, com as configurações de comunicação, tags, scripts, etc.

- `BibliotecaTreinamento.lib`  
  Biblioteca com objetos e componentes reutilizáveis usados no projeto (telas, símbolos, etc.).

- `dados.mdb`  
  Banco de dados **Microsoft Access**, utilizado para armazenamento de históricos, logs ou demais registros do projeto.

- `Figuras/`  
  Imagens e ícones utilizados nas telas do supervisório.

- `Modbus/`  
  Arquivos relacionados à comunicação **Modbus** (configurações, drivers ou exemplos de mapeamento).

- `LICENSE`  
  Arquivo de licença do projeto.

- `README.md`  
  Arquivo de documentação (este documento).

---

## 🛠️ Tecnologias Utilizadas

- **Software:** Elipse E3
- **Versão:** 6.8

---

## 🚀 Como abrir o projeto

1. **Copie** a pasta `TreinamentoE3` para um diretório de sua preferência no computador.
2. Abra o **E3 Studio**.
3. No menu do E3 Studio, vá em **File > Open Project** (Arquivo > Abrir Projeto).
4. Selecione o arquivo:
   - `TreinamentoE3.prj`
5. Aguarde o carregamento do projeto e verifique:
   - Se a biblioteca `BibliotecaTreinamento.lib` foi carregada corretamente.
   - Se os drivers de comunicação (ex.: Modbus) estão disponíveis.
6. Inicie o **E3Server** e execute a aplicação para testes.

> **Observação:** dependendo da configuração original, pode ser necessário ajustar caminhos de banco de dados, drivers ou endereços IP/porta dos equipamentos Modbus.

---

## 🔐 Credenciais de Acesso

Abaixo estão os usuários e senhas configurados no sistema para testes de níveis de acesso e operação:

| Usuário   | Senha      | Nível de Acesso (Estimado)   |
| :-------- | :--------- | :--------------------------- |
| **admin** | `admin123` | Administrador / Acesso Total |
| **user1** | `user1`    | Administrador / Acesso Total |
| **user2** | `user2`    | Operador / Usuário 2         |
| **user3** | `user3`    | Operador / Usuário 3         |

---

## 📝 Notas finais

- Este projeto foi criado para fins de **treinamento** e pode servir como base para estudos ou como modelo para novos desenvolvimentos.
- Antes de usar em ambiente real de produção, recomenda-se:
  - Revisar scripts, limites, alarmes e configurações de comunicação;
  - Alterar **usuários e senhas**, adequando às políticas de segurança da empresa;
  - Testar cuidadosamente todas as funcionalidades em ambiente controlado.
