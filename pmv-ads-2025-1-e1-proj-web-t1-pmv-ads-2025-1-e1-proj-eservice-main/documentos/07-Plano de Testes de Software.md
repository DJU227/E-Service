# Plano de Testes de Software

Os requisitos para realização dos testes de software são:
<ul><li>Site publicado na internet;</li>
<li>Navegador da internet: Chrome, Firefox ou Edge.</li>
</ul>

Os testes funcionais a serem realizados na aplicação são descritos a seguir.

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-01: Verificar o funcionamento dos links da página Home</td>
  <td>
   <ul>
    <li>RF-02: A aplicação deve disponibilizar um sistema de busca de prestadores</li>
   </ul>
  </td>
  <td>Verificar se os links da página Home estão encaminhando para as respectivas páginas corretamente</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a página Home.</li>
    <li>Clicar nos links da página Home.</li>
    <li>Clicar no campo de pesquisa para obter o serviço desejado.</li>
   </ol>
   </td>
  <td>Todos os links da página Home devem encaminhar os usuários para as páginas descritas.</td>
  <td>Djulio</td>
 </tr>
</table>
 
<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-02: Verificar o funcionamento do filtro de pesquisa</td>
  <td>
   <ul>
    <li>RF-06: A aplicação deve permitir um sistema de categorias para classificar os prestadores (ex.: serviços domésticos, reparos, designer etc).</li>
   </ul>
  </td>
  <td>Verificar se o filtro de pesquisa está recuperando os dados inseridos pelo usuário</td>
  <td>
   <ol>
    <li>Acessar o navegador.</li>
    <li>Informar o endereço do site.</li>
    <li>Visualizar a página Home.</li>
    <li>Clicar no campo de pesquisa</li>
    <li>Digitar no filtro de pesquisa o serviço desejado.</li>
   </ol>
   </td>
  <td>Os dados inseridos no filtro de pesquisa devem mostrar o que o cliente necessita.</td>
  <td>Djulio</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-03: Verificar o funcionamento do Cadastro de Informações de Clientes</td>
  <td>
   <ul>
    <li>RF-01: A aplicação deve permitir cadastro de clientes e prestadores.</li>
   </ul>
  </td>
  <td>Verificar se os campos de cadastro podem ser inseridos corretamente e cadastrados no LocalStorage.</td>
  <td>
   <ol>
    <li>Acessar a página de Cadastro de Clientes.</li>
    <li>Inserir todos os dados obrigatórios nos campos corretos.</li>
    <li>Clicar no botão "Cadastrar".</li>
   </ol>
   </td>
  <td>Os dados devem ser cadastrados e armazanados no LocalStorage. Caso algum camos esteja errado é necessário aparecer um aviso ao usuário indicando o que precisa ser modificado.</td>
  <td>João</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-04: Verificar a inserção de LOGRADOURO automático pela API ViaCEP</td>
  <td>
   <ul>
    <li>RF-01: A aplicação deve permitir cadastro de clientes e prestadores.</li>
    <li>RNF-03:	A interface deve ser intuitiva e acessível, atendendo às normas de Acessibilidade Digital (WCAG 2.1).</li>
   </ul>
  </td>
  <td>Verificar se após  o preenchimento do campo CEP, o campo LOGRADOURO será preenchido com o nome do enderaço correto.</td>
  <td>
   <ol>
    <li>Acessar a página de Cadastro de Clientes.</li>
    <li>Inserir o CEP da Rua desejada no campo correto (CEP)</li>
    <li>Clicar fora do campo CEP para parar a digitação</li>
   </ol>
   </td>
  <td>Após a inserção do número CEP desejado, no campo LOGRADOURO é necessário aparecer o nome da rua correto em relação ao CEP.</td>
  <td>João</td>
 </tr>
</table>

<table>
 <tr>
  <th>Caso de teste</th>
  <th>Requisitos associados</th>
  <th>Objetivo do teste</th>
  <th>Passos</th>
  <th>Critérios de êxito</th>
  <th>Responsável</th>
 </tr>
 <tr>
  <td>CT-05: Verificar o funcionamento das validações dos campos de input</td>
  <td>
   <ul>
    <li>RF-03: A aplicação deve permitir login de cliente e pretadores</li>
   </ul>
  </td>
  <td>Verificar se o sistema permite efetuar o login de forma correta de acordo com a requisição do usuario</td>
  <td>
   <ol>
    <li>Acessar a pagina de login</li>
    <li>Verificar se possui um cadastro registrado</li>
    <li>Verificar se a aplicação permite logar com os campos não preenchidos</li>
    <li>Verificar se a aplicação valida os dados salvos no localstorage corretamente.</li>
    <li>Verificar se a aplicação valida o perfil de usuario cadastrado (cliente/prestadores).</li>
   </ol>
   </td>
  <td>Após as validações a aplicação ao inserir os dados corretamente deve redirecionar para a Home Page.</td>
  <td>Poliana </td>
 </tr>
</table>

> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)
> - [Criação e Geração de Planos de Teste de Software](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)
