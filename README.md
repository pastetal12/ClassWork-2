# ClassWork-2
public class BankManager {
    public static void main(String[] args) {
        int smallCreditValue = 50;
        int mediumCreditValue = 100;
        int bigCreditValue = 500;
        int currentDepositValue = 800;
        String smallCredit = "Small Credit";
        String bigCredit = "Big Credit";
        String mediumCredit = "Medium Credit";
        String currentDeposit = "Current Deposit";
        System.out.println(smallCreditValue + "/n");
        System.out.println(smallCredit + "/n");
        System.out.println(bigCreditValue + "/n");
        System.out.println(bigCredit + "/n");
        System.out.println(mediumCredit + "/n");
        System.out.println(mediumCreditValue + "/n");
        System.out.println(currentDeposit + "/n");
        System.out.println(currentDepositValue + "/n");
        String[] creditCollection = {
                "smallCredit", "bigCredit", "mediumCredit"
        };
        System.out.println(creditCollection.length);
        int lastCreditProduct = creditCollection.length - 1;
        System.out.println(creditCollection[lastCreditProduct]);
        int firstCreditProduct = creditCollection.length - 3;
        System.out.println(creditCollection[firstCreditProduct]);
    }
}
