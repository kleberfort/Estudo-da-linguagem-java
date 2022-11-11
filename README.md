# Estudo-da-linguagem-java
Principais trechos do conteúdo estudado de cada capitulo.



CAPITULO 3: INTRODUÇÃO A CLASSES, OBJETOS, MÉTODOS E STRINGS.


- Cada nova classe que você desenvolve tornar-se um novo tipo que pode ser utilizado para declarar variáveis e delinear objetos.

- Váriáveis de instância de uma classe armazenam dados para cada objeto(isto é, cada instância) da classe.

- Nomes de classes, de método e de variáveis são identificadores, todos usam o mesmo esquema de nomeação com a notação camelo. 
- Nomes de classes começam com letra maiúsculas.
- Nomes de métodos e variáveis iniciam com uma letra minúsculas.
- Um Objeto tem atributos, implementados como variáveis de instância que o acompanham ao longo da sua vida.
- Cada objeto (instância) da classe tem sua própria cópia das variáveis de instância da classe.
- variáveis de isntância são declaradas dentro de uma declaração de classe.

- As variáveis ou método declarados com o modificador de acesso private só são acessíveis a métodos da classe em que isso ocorre.

- O tipo de retorno void, indica que executará uma tarefa, mas não retornará nenhuma informação ao seu chamador.

- Os parâmetros são declarados em uma LISTA DE PARÂMETROS que está localizada entre os parênteses que seguem o nome do método no título dele. quando existem múltiplos parâmetros, cada um é separado por vírgula.

- Variáveis declaradas no corpo de um método específico são VARIÁVEIS LOCAIS que somente podem ser utilizados nele. Cada método só pode acessar suas próprias variáveis locais. Quando esse método terminar, os valores de sua variáveis locais são perdidos.
- Os parâmetros de um método também são variáveis locais dele.

- Se um método contiver uma variável local com o mesmo nome de uma variável de instância, o corpo do método irá referenciar a variável local em vez da variável de instância. O corpo do método pode usar a palavra-chave THIS  para referenciar a variável de instância simulada explicitamente. 

- Uma classe que contém um método main inicia uma execução de um aplicativo java.

- Diferente das variáveis locais, que não são inicializadas de forma automática, toda VARIÁVEL DE INSTÂNCIA tem um VALOR INICIAL PADRÃO - Fornecida pelo Java quando você não especifica o valor de variável de instância. 

- Uma chamada de método pode fornecer argumentos cujos valores são atribuídos aos parâmetros de método correspondente. 

- O número de argumentos na chamada de método deve CORRESPONDER ao de itens na lista de PARÂMETROS da declaração do método. Os tipos de argumentos na chamada de método precisam ser consistente com os tipos de parâmetro correspondentes na declaração de método. 

- Classes no mesmo pacote são importadas implicitamente para os arquivos de código-fonte de outras classes nesse pacote. Assim uma declaração import não é necessária quando uma classe adota outra no mesmo pacote. 

- Os método set podem ser programados para validar seus argumentos e rejeitar qualquer tentativa de definir os dados como valores ruins. e um método get pode apresentar os dados de uma forma diferente.

- A declaração de variáveis de instância com o modificador de acesso private é conhecida como ocultamento de dados. quando um programa cria um objeto da classe, a variável é encapsulada no objeto e pode ser acessada apenas por métodos da classe do objeto. 

> TIPOS PRIMITIVOS VERSUS TIPOS POR REFERENCIA

- Os tipos de dados são dividios em tipos primitivos e por referência.
- Os tipos primitivos são: int, boolean, byte, char, short, long, float e double. Todos os tipos não primitivos são por referência, assim as classes que especificam o objeto são por referência. 
- OS PROGRAMAS UTILIZAM AS VARIÁVEIS DE TIPO POR REFERÊNCIA PARA ARMAZENAR AS LOCALIZAÇÕES DE OBJETOS NA MEMÓRIA DO COMPUTADOR. DIZEMOS QUE ESSA VARIÁVEL REFERENCIA UM OBJETO NO PROGRAMA. OBJETOS QUE SÃO REFERÊNCIADOS PODEM CONTER MUITAS VARIÁVEIS DE INSTÂNCIA. 

- Para chamar métodos em um objeto, é preciso de uma referência a ele.
- Variáveis de tipo primitivo não fazem referência a objetos, assim elas não podem ser usadas para chamar métodos.
- 
