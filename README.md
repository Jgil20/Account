# Account
Simple java Account program
public class Main {

    public static void main(String[] args) {
	 Account JhonsAccount = new Account("Jhon");
	 JhonsAccount.deposit(1000);
	 JhonsAccount.withdraw(500);
	 JhonsAccount.withdraw(-200);
	 JhonsAccount.deposit(-20);
	 JhonsAccount.calculateBalance();
	 JhonsAccount.balance = 5000;

        System.out.println("Balance on account is "+ JhonsAccount.getBalance());
        JhonsAccount.transactions.add(4500);
        JhonsAccount.calculateBalance();
    }
}
