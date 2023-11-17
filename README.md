# ProjetoJPAHibernateBootcampJava
### Visão Geral

O Projeto JPA e Hibernate com MySQL (Eclipse) fornece uma visão geral que utiliza JPA (Java Persistence API) e Hibernate para interação com um banco de dados MySQL. O projeto foi gerenciado pelo Maven. Foi criado um banco de dados de uma empresa com as entidades funcionários e departamento e que relacionam entre si.

### Classes 

**Main**

A classe `Main` é a classe principal do projeto e contém o método `main`. No método `main`, demonstramos o seguinte:

* **Criação do EntityManagerFactory:** Utilizar``Persistence.createEntityManagerFactory("teste")`para criar o EntityManagerFactory baseado`persistence.xml`.

* **Criação do EntityManager:**

  EUA`emf.createEntityManager()`para obter um EntityManager a partir do EntityManagerFactory. 

* **Consulta ou Criação de Departamentos:**

  Utilize o EntityManager para pesquisar.

* **Criação de um Novo Funcionário**.

* **Persistência do Funcionário no Banco de Dados:**

  Utilize-os`em.persist(funcionario)`para persistir

* **Comprometimento da Transação:**

  Comita as alterações no banco de dados usando `em.getTransaction().`em.getTransaction().commit()`.

* **Fechamento dos EntityManagers:**

  Data dos EntityManagers (``em`e `em`emf`)

**Funcionário**

A classe `funcionario` representa um funcionário de uma empresa e possui atributos como `id`identidade, `nome`nome do funcionário, `email`e-mail do funcionário.

**Departamento**

A classe `departamento` define o serviço do `funcionario` com o identificador único de departamento `id`, `nome`do departamento, `usuarios`lista de funcionários associados. 

**Classpath**

A `classpath` é um conjunto de locais no sistema de arquivos JARs (Java Archive) que define onde o compilador Java e o tempo de execução procuram classes durante a compilação e a execução de um programa Java.

* Pasta de origem.
* Excluir recursos da pasta de origem.
* Pasta de saída. 

**Pom**

O arquivo `pom.xml`é uma parte importante no projeto Maven, fornece informações sobre o projeto e suas dependências. 

**Persistence**

O arquivo `persistence.xml`fornece configurações para a persistência de objetos Java em um banco de dados. 

#### **Como Rodar o Aplicativo**

Para rodar o aplicativo: 

1 - Certifique-se de ter o Java instalado em seu sistema.

2 - Certifique-se de que o MySQL Server esteja instalado em sua máquina. 

3 - Após a execução do projeto, verifique se os dados foram persistidos corretamente no Banco de Dados MySQL.
