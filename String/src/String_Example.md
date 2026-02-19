public class String_Exe {

    public static void main(String[] args) {

        String s = new String(" Jawa ");

        String s1 = " jawa ";
        String s2 = " Jawa ".concat("Bobber");
        System.out.println( s1 == s2 );
        System.out.println( s == s1);
        System.out.println( s == s2);

        System.out.println(s1.equals(s2));

        System.out.println(s1.length());

        System.out.println(s2.charAt(3));

        System.out.println(s2);

        System.out.println(s1.equalsIgnoreCase(s));

        System.out.println(s1.compareTo(s2));

        String s4 = " HEllO " ;
        System.out.println(s4);
        System.out.println(s4.trim());
        System.out.println(s4.substring(0,8));
       // System.out.println(s1.split("Hello ","H));
    }
}