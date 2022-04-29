1. A JVM é uma máquina virtual que permite o transporte do
código Java, fazendo com que ao escrever o código,
o mesmo poderá ser executado em qualquer lugar. A JVM fará a comunicação do bytecode java para o sistema operacional onde o código-fonte atuará, implicando na ausência de preocupações em relação a execução.

2. JRE(Java Runtime Environment): Contém os elementos necessários para o usuário ser capaz de executar uma aplicação java, ou seja, contém a JVM e as bibliotecas.
JDK(Java Development Kit): Como o próprio nome indica, é um kit, composto pelo JRE e um amontoado de ferramentas que podem ser usadas pelo desenvolvedor Java. As principais ferramentas que o compõe são: javac, Java, jdb, Java-prof, javadoc, jar, appletviewer javap e extcheck.

Portanto, conclui-se que enquanto o JRE traz elementos necessários para o usuário,já o JDK é composto pelo JRE e traz ferramentas voltadas para o desenvolvedor.

3.  class Main {
  public static void main(String[] args) {
    System.out.println("Terminei a primeira aula com um programa Java!");
  }
}

Nome do arquivo: Main.java

4. O programa não executa, pois sem o class, o arquivo bytecode não é gerado e, por consequência, não tem como ser interpretado pela máquina.
