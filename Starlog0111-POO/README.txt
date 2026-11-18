PROJETO STARLOG-ZERO

Estrutura:
src/
  br/com/starlog/model/
    Carga.java
    ModuloCarga.java
    BaseLancamento.java
  br/com/starlog/exception/
    CapacidadeExcedidaException.java
  br/com/starlog/main/
    MainResgate.java

Como compilar:
Abra o terminal na pasta raiz do projeto e execute:

javac -d bin src/br/com/starlog/model/*.java src/br/com/starlog/exception/*.java src/br/com/starlog/main/*.java

Como executar:

java -cp bin br.com.starlog.main.MainResgate

Resultado esperado:
- Ataque 1: identificador vazio rejeitado.
- Ataque 2: HashSet mantém apenas uma carga com o mesmo código.
- Ataque 3: terceira carga é rejeitada por exceder a capacidade.
- Ataque 4: seguro total calculado em R$ 100.0.

Observacao:
O projeto segue os requisitos descritos no arquivo da atividade StarLog-Zero.
