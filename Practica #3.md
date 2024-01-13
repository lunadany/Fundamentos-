import  java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int numint;
        double numdbl,res1,res2,res3,res4,res5,res6;
        //Vamos a realizar una mini calcualdora, sigan viendo.
        System.out.println("Bienvenidos por favor sigue las instrucciones");
        //El System.out.println, sirve para imprimir un argumento en la pantalla.
        Scanner scanner = new Scanner(System.in);
        //scanner: Se utiliza para obtener la entrada de información
        //del usuario desde el teclado.
        System.out.println("\n Digite un número entero");
        numint = scanner.nextInt();
        //El número escrito desde el teclado se guarda en numint
        //y el nextInt se encarga de leer el nuevo dato.
        System.out.println("dijite un numero decimal");
        numdbl = scanner.nextDouble();
        /*
        los números escritos desde el teclado ya guardados en las
        variables pasan a las operaciones asignadas tales como: 
        res1, res2, res3 donde se encargan de realizar las operaciones
        posteriormente utilizamos la funcion para imprimir el resultado 
        en su respectiva operacion.
        */

        res1 = numdbl + numint;
        res2 = (double) numint / (int)numdbl;
        res3 = numint / numdbl;
        res4 = numdbl / numint;
        res5 = (double) (int) numdbl / numint;
        res6 = (int)numdbl + numint;

        System.out.println("\n El valor de la operacion =" + res1);
        System.out.println("\n El valor de la operacion =" + res2);
        System.out.println("\n El valor de la operacion =" + res3);
        System.out.println("\n El valor de la operacion =" + res4);
        System.out.println("\n El valor de la operacion =" + res5);
        System.out.println("\n El valor de la operacion =" + res6);
    }
}
//Daniel Luna Perez
//Rubi Cuatecontzi Cuatecontzi
//Miriam Jimenez Hernandez 
//janely Cuamatzi Tlilayatzi
//Nely Pichon Rivera
// 5ºi
