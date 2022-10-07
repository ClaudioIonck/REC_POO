# REC_POO

# Questões:



# 1. Crie um código que apresente uma herança.


'''
public class Animal
{
    public String Terrestres;
    public String Tipo;
}public class QuatroPatas extends Mamifero
{
    public String Canis;
}public class Mamifero extends Carnivoros
{
    public int ComPelo;
}
'''


# 2. Crie um código que apresente uma implementação de interface.



'''
public interface Animal {

    public String Tipo();
    public String getId();
}


public interface Terrestres {

    public String QuatroPatas();
    public String Dieta();
}


public class Animal implements Animal,Terrestres {

    @Override
    public String getId() {

    }

    @Override
    public String getTipo() {

    }

    @Override
    public String getDieta() {

    }

    @Override
    public String getQuatroPatas() {

    }

}
'''


# 3. Crie um código que apresente uma sobrecarga de método.



'''
public class calculadora {
    public int soma(int a, int b) {
        return a + b;
    }

    public double soma(double a, double b) {
        return a + b;
    }

    public String soma(String a, String b) {
        return a + b;
    }
} 
'''



# 4. Crie um código que apresente uma relação de composição.



'''
public class Sistema {

    Pessoa pessoa = new Pessoa();

}

public class Pessoa {

}
'''

5. Apresente os códigos dos exercícios anteriores em um diagrama de classes da UML.
