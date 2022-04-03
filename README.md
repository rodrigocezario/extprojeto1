# Extensão Projeto 1 - Loja Amazonas

## Projeto do curso de extensão em Desenvolvimento web com a plataforma Java
Documentação do Projeto 1 para o curso de extensão em Desenvolvimento web com a plataforma Java.

## Ferramentas
Para o acompanhamento das aulas, recomenda-se fortemente a utilização do IDE Eclipse na implementação do projeto. Pretende-se já no primeiro encontro iniciar o desenvolvimento do projeto, assim, faça previamente o download de todas as ferramentas. A configuração de todo ambiente de desenvolvimento será realizado no primeiro encontro.

- [Eclipse IDE for Enterprise Java and Web Developers *](https://www.eclipse.org/downloads/packages/release/2022-03/r/eclipse-ide-enterprise-java-and-web-developers/)
- [Apache Tomcat](https://dlcdn.apache.org/tomcat/tomcat-10/v10.0.20/bin/apache-tomcat-10.0.20.zip)
- [MySQL Community Server](https://dev.mysql.com/downloads/file/?id=510039)
- [MySQL Connector/J](https://dev.mysql.com/downloads/file/?id=509728)
- [MySQL Workbench](https://dev.mysql.com/downloads/file/?id=509428)

* Importante: A versão do IDE Eclipse adotada neste curso é diferente da versão utilizada nas disciplinas regulares de programação. Sendo assim, é necessário fazer o download desta versão.

## Apresentação do projeto
Neste repositório estão reunidos os arquivos de projeto (nível de design) da loja de e-commerce. Este projeto irá apresentar oportunidades para utilizarmos várias especificações de APIs da arquitetura Jakarta EE com um foco maior em uma abordagem utilizada em sistemas legados. O próximo projeto que será implementado neste curso irá utilizar uma abordagem mais moderna.

## O Projeto
### Escopo do projeto
O projeto consiste na construção de site de e-commerce para plataforma web para que a empresa Amazonas possa comercializar seus produtos através da internet, onde poderá disponibilizar sua lista de produtos, informações detalhadas de cada item, permitirá realizar o cálculo de frete e concluir a compra através de gateway de pagamento. A documentação inicial do projeto pode ser obtido [aqui](arquivos/Projeto.pdf).

### Modelo de classes
Para este projeto, iremos considerar o seguinte modelo de classe para representar o domínio do negócio:

![Modelo de classes do projeto](arquivos/modelo_classes.png?raw=true "Modelo de classes do projeto")

### Modelo de Dados
O MER (Modelo Entidade Relacionamento) descreve a representação conceitual para criação das tabelas (entidades) para nosso modelo de negócio. A figura a seguir apresenta o modelo de dados utilizado neste projeto.

![Modelo Entidade Relacionamento](arquivos/mer.png?raw=true "Modelo Entidade Relacionamento")

### Arquivos de Dados
Segue lista de arquivos para criação e utilização da base de dados do projeto. 
- [Script para criação e para popular a base de dados](arquivos/lojav2.sql)
- [Comandos para consultas](arquivos/Consultas.rtf)
- [Arquivo de dados SQLite](https://www.dropbox.com/s/85jtjcjwes9skhv/lojadbv2.db?dl=0)
- [Documentação do Drive de conexão com SQLite](https://github.com/xerial/sqlite-jdbc)

**Ao optar por utilizar SQLite com base de dados (para os que tiverem problemas com MySQL), é necessário alterar o nome da função RND nas consultas por RANDOM.* 

## Leituras complementares
Segue algumas leituras para auxiliar na configuração do ambiente:
- [Tutorial: Instalando, configurando e inicializando o Git no Windows](https://dev.to/womakerscode/tutorial-instalando-configurando-e-inicializando-o-git-no-windows-57cj)
- [How To Reset Your MySQL or MariaDB Root Password](https://www.digitalocean.com/community/tutorials/how-to-reset-your-mysql-or-mariadb-root-password)
- [Git de autenticação por token](https://www.alura.com.br/artigos/nova-exigencia-do-git-de-autenticacao-por-token-o-que-e-o-que-devo-fazer)


## Observações
Em breve irei disponibilizar o passo-a-passo do desenvolvimento do projeto.

## Contribuições
Todos são bem-vindos a contribuir com este projeto. Sinta-se a vontade em enviar suas sugestões e críticas para o e-mail [rodrigocezario@msn.com](rodrigocezario@msn.com). :)
