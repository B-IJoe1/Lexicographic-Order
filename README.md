# Lexicographic-Order
# Using String parameter you are making sure that the two phrases are lexicographic order.


    public static void main (String[] args)
     {
      Scanner input= new Scanner(System.in);
      System.out.println("Enter phrase1: ");
       String phrase1 =input.nextLine();
       
       System.out.println("Please Enter phrase2: ");
       String phrase2 = input.nextLine();
       
       if (phrase1.compareTo(phrase2)<0)
		  System.out.println (phrase1.equals(phrase2));
       
       
       else
    	   System.out.println(phrase1 + " " + "and" + " " + phrase2 + " " + "are not equal");
       }

    }
