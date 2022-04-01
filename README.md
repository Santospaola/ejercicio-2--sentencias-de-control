# ejercicio-2--sentencias-de-control
--parte 1--
package com.company;

public class Main {

    public static void main(String[] args) {
    int numeroif= 10;
    if (numeroif >0){
        System.out.println("numeroif es positivo");
    } else if (numeroif<0){
        System.out.println("numeroif es negativo");
    } else {
        System.out.println("numeroif es 0");
    }
    }
}
-- parte 2, while--

package com.company;

public class Main {

    public static void main(String[] args) {
        int numeroWhile= 0;
        while (numeroWhile <3){
            System.out.println(numeroWhile);
            numeroWhile= numeroWhile + 1;
        }

    }

}

-- parte 3, do while --

package com.company;

public class Main {

    public static void main(String[] args) {
	int numeroWhile= 0;
    do{
        System.out.println(numeroWhile);
        numeroWhile= numeroWhile +1;
    } while (numeroWhile <3);
    }

-- parte 4, FOR --
package com.company;

public class Main {

    public static void main(String[] args) {
        for (int numeroFor = 0; numeroFor<= 3; numeroFor= numeroFor +1){
            System.out.println(numeroFor);
        }
    }
}

-- parte 5, switch--
package com.company;

public class Main {

    public static void main(String[] args) {
        var estacion = "primavera";
        switch(estacion) {
            case "verano":
                System.out.println("Es verano");
                break;
            case "invierno":
                System.out.println("Es invierno");
                break;
            case "primavera":
                System.out.println("Es primavera");
                break;
            case "otoño":
                System.out.println("Es otoño");
                break;
            default:
                System.out.println("No es una estación");
        }
    }
    }
