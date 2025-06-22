# Programação de Funcionalidades

<span style="color:red">Pré-requisitos:</span>
<a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2025-1-e1-proj-web-t1-pmv-ads-2025-1-e1-proj-eservice/blob/main/documentos/02-Especifica%C3%A7%C3%A3o%20do%20Projeto.md">Especificação do Projeto</a>,
<a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2025-1-e1-proj-web-t1-pmv-ads-2025-1-e1-proj-eservice/blob/main/documentos/03-Metodologia.md">Metodologia</a>,
<a href="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2025-1-e1-proj-web-t1-pmv-ads-2025-1-e1-proj-eservice/blob/main/documentos/04-Projeto%20de%20Interface.md">Projeto de Interface</a>



Home Page (RF-002)


Responsável: Djulio

O acesso a tela inicial poderá ser feita assim que a aplicação for aberta. As estruturas de dados foram baseadas em HTML e CSS.

Tela inicial:

![Image](https://github.com/user-attachments/assets/1586e936-4137-44ef-a737-72643a5f3d34)

### Requisitos atendidos
- RF-02	A aplicação deve disponibilizar um sistema de busca de prestadores.
- RF-06	A aplicação deve permitir um sistema de categorias para classificar os prestadores (ex: serviços domésticos, reparos, designer etc).

Artefatos da funcionalidade

●home.html

●estiloHome.css


<hr>


### Tela Cadastro Usuário (RF-001)

Responsável: João

O acesso a tela de cadastro de usuário/cliente poderá ser feita após a interação do usuário com o botão de cadastro na tela inicial. As estruturas de dados foram baseadas em HTML, CSS e JS.



Exemplo Tela de Cadastro Cliente:


![image](https://github.com/user-attachments/assets/7957c9c9-1d8b-456f-9e1c-fce7f940c246)



### Requisitos atendidos
RF-01 A aplicação deve permitir cadastro de clientes e prestadores.



### Artefatos da funcionalidade

●usuario.html

●cadastroUsuario.css

### Tela de Calendário de Serviços (RF-004, RF-007)

**Responsável:** Gabriel Roani

A tela exibe um calendário com navegação por mês, onde é possível visualizar serviços agendados e passados. Datas com tarefas mostram um tooltip ao passar o mouse. O layout tem duas colunas: cards de pedidos à esquerda e o calendário à direita.

**Exemplo de Tela de Calendário de Serviços:**

![Image](https://github.com/user-attachments/assets/fb7de715-7aad-4c11-baa5-677da1c81489)

---

### Requisitos atendidos  
**RF-04** Agendamento de serviços conforme disponibilidade  
**RF-07** Histórico de serviços contratados

---

### Artefatos da funcionalidade

● `calendario.html`  
● `calendario.css`  
● `calendario.js`

### Tela Cadastro Prestador (RF-001)

Responsável: Fabiano

O acesso à tela de cadastro de prestador será realizado após o usuário interagir com o botão de cadastro disponível na tela inicial. A implementação dessa funcionalidade utiliza HTML, CSS e JavaScript.


Exemplo Tela de Cadastro Prestador:


![image](img/Cadastro%20Prestador.png)



### Requisitos atendidos
RF-01 A aplicação deve permitir cadastro de clientes e prestadores.



### Artefatos da funcionalidade

prestador.html

prestador.css

### Instruções de acesso
Abra um navegador de Internet e informe a seguinte URL: 

<hr>

### Tela de Login (Prestador/Cliente) (RF-003)

**Responsável:** Poliana Maia

A tela exibe dois input (Email e Senha) para a realização do login na plataforma. Tendo a possibilidade de no mesmo ambiente ser alterado para um dos dois perfis caso tenha acessado o login incorreto e um atalho para as telas de cadastro caso ainda não possua.

**Exemplos de Telas de Login Cliente:**

![Image](img/Login%20Cliente.png)

**Exemplos de Telas de Login Prestador:**

![Image](img/Login%20Prestador.png)

---

### Requisitos atendidos  
**RF-03** A aplicação deve permitir login de clientes e prestadores. 

---

### Artefatos da funcionalidade

● `cliente.html`  
● `prestador.html`  
● `login.css`  
● `login.js`

<hr>

> **Links Úteis**:
> - [Trabalhando com HTML5 Local Storage e JSON](https://www.devmedia.com.br/trabalhando-com-html5-local-storage-e-json/29045)
> - [JSON Tutorial](https://www.w3resource.com/JSON)
> - [JSON - Introduction (W3Schools)](https://www.w3schools.com/js/js_json_intro.asp)
> - [JSON Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/json/index.htm)

