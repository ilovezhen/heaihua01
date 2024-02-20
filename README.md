public class Demo01 {
    public static void main(String[] args) {
        //求1-100之间的数据和，并把求和结果在控制台输出
        int num = 0;
        for (int i = 1; i <= 100 ; i++) {
            num += i;
        }
        System.out.println(num);
    }
}
