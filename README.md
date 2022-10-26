 public static void main(String[] args) {
        
      // IF
        
        int a = 1;
        
        if (a<0){
            System.out.println("Es un número negativo");
        }else if (a>0){
            System.out.println("Es un número positivo");
        }else{
            System.out.println("El número es 0");
        }
        
        
      //WHILE
        
        while (a<3){
            a = a+1;
            System.out.println(a);
        }
        
        
      //DO...WHILE
        
        do{
            a = a+1;
            System.out.println(a);
        }while (a<3);
        
        
      //FOR
        
        for (int i=0;i<=3;i=i+1){
            System.out.println(i);
        }
        
        
      //SWITCH
        
        String estacion = "Otoño";
        
        switch (estacion){
            case "Verano":
                System.out.println("Es verano.");
                break;
            case "Invierno":
                System.out.println("Es invierno.");
                break;
            case "Otoño":
                System.out.println("Es otoño.");
                break;
            case "Primavera":
                System.out.println("Es primavera.");
                break;
            default:
                System.out.println("Eso no es una estación del año.");
        }
        
        
    }
    

}
