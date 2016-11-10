[![Stories in Ready](https://badge.waffle.io/ajunior/petshop.png?label=ready&title=Ready)](https://waffle.io/ajunior/petshop)
# PET Shop

Aplicação Web para a lojinha de componentes eletrônicos do [Programa de Educação Tutorial](http://www.ifpb.edu.br/pre/programas/pet/pet) do Curso Superior de [Engenharia Elétrica](https://estudante.ifpb.edu.br/cursos/42) do [Instituto Federal de Educação, Ciência e Tecnologia da Paraíba](http://ifpb.edu.br) (__PET-EE__).

### Funcionalidades da Aplicação

- Listagem dos componentes, com suas respectivas quantidades e preço. 
- Consulta de componentes por nome

### Ferramentas utilizadas no desenvolvimento

- Ruby on Rails 5
- MySQL 5.7

### Instalação

```shell
git clone https://github.com/ajunior/petshop.git
```

Certifique-se de ter um servidor MySQL instalado e funcionando. Também tenha certeza de ter um usuário com permissão para criar uma base de dados. Então, utilize os scripts sql que estão na pasta ```db``` para criar a base de dados, as tabelas e insira as informações necessárias para o funcionamento da aplicação. 

```shell
$ mysql -u user -p < db.sql
```

### Documentação

Em breve.

## Versão

__Estável: ```none```__<br>
__Em desenvolvimento: ```0.1.0a```__

### Sistema de versionamento

As versões desta aplicação serão padronizadas com base no sistema [Semantic Versioning](http://semver.org/lang/pt-BR/).

## Como contribuir?

Toda contribuição é bem vinda. Se deseja contribuir com o desenvolvimento do ```PET Shop```, fork o repositório, clone, faça as devidas alterações e envie um Pull Request, que nós avaliaremos e aceitaremos se suas alterações estiverem em conformidade com o objetivo do projeto. 

## Reportando erros e solicitando novas funcionalidades

__Utilize o sistema de [issues](https://github.com/ajunior/petshop/issues)__:

- Se você deseja que uma nova funcionalidade seja implementada;
- Se você encontrou algum erro ou acha que algo não está funcionando como deveria;

### Informando erros

Ao informar um erro é importante relatar em que momento, na execução da aplicação, o erro aconteceu e qual procedimento você estava executando, além de informações básicas como sistema operacional e navegador utilizado.

### Solicitando novas funcionalidades

É importante descrever a funcionalidade e qual a utilidade dela no sistema.

## Copyright

Copyright (c) 2016, Adjamilton Junior, Talita Valéria e Weslley Santos.<br>
Esta aplicação é licenciada sob a [GPLv3](https://www.gnu.org/licenses/gpl.html).

### Contatos

Nome | E-mail | GitHub | LinkedIn |
:---------: | :----------: | :----------: | :------------:
Adjamilton Junior | jr@ieee.org | [ajunior](http://github.com/ajunior) | [junioralmeida](https://br.linkedin.com/in/junioralmeida)
Talita Valéria | talita.v.matta@gmail.com | [talitav](http://github.com/ajunior) | [talitavaleria](https://br.linkedin.com/in/talitavaleria/)
Weslley Santos | weslley.c.santos@ieee.org | [wcsantos](https://github.com/wcsantos) | [weslley-santos-961847117](https://br.linkedin.com/in/weslley-santos-961847117)

### Licença

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

__Tradução não-oficial:__

    Este programa é um software livre; você pode redistribuí-lo e/ou 
    modificá-lo dentro dos termos da Licença Pública Geral GNU como 
    publicada pela Fundação do Software Livre (FSF); na versão 3 da 
    Licença, ou (na sua opinião) qualquer versão.

    Este programa é distribuído na esperança de que possa ser útil, 
    mas SEM NENHUMA GARANTIA; sem uma garantia implícita de ADEQUAÇÃO
    a qualquer MERCADO ou APLICAÇÃO EM PARTICULAR. Veja a
    Licença Pública Geral GNU para maiores detalhes.

    Você deve ter recebido uma cópia da Licença Pública Geral GNU junto
    com este programa. Se não, veja <http://www.gnu.org/licenses/>.
