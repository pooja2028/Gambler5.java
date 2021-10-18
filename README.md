# Gambler5.java
public class Gambler {
	static int stakePerDay = 100; //stake is in dollar
	static int betPerGame =  1 ; 
	static int totalStake = 100;
        static int totalChance = 150;
		public static void main(String[] args)
        	{
                     for(int i=1; i<=1; i++)
			for (int j = 1; j <= totalChance; j++) {
                                Random random= new Random();
                                int bet = random.nextInt(2);

                                if (bet==1)
                                        System.out.println("Win game");
                                else
                                        System.out.println("Loose game");


                                totalStake+=1;
                        }
                }
                       System.out.println("Total Amount  one  days "+totalStake);
}
