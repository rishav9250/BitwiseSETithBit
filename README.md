# BitwiseSETithBit
here is a code of BitwiseSETithBit in java.



public class BitwiseSETithBit {
    public static int SetBit(int n, int i){
        int bitmask =i<<i;
        return n|bitmask;

    }
public static void main(String[] args) {
    System.out.println(SetBit(5, 1));
}
}

