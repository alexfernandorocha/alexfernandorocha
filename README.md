```java
package me.alexfrocha;
import me.alexfrocha.Desenvolvedor;

class SobreMim extends Desenvolvedor {
  public SobreMim() {
    super.nome = "Álex Fernando Rocha de Almeida";
    super.area = "Estudante";
  }
}

class Tecnologias extends Desenvolvedor {
  public Tecnologias() {
    List<String> tecnologias = new ArrayList<String>();
    tecnologias.add("Java");
    tecnologias.add("Spring Boot");
    tecnologias.add("Git");
  }
}
```
