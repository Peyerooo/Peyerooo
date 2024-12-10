class Main {
    public static void main(String[] args) {
        
        // Program 1
        String str1 = "Music";
        String str2 = "Therapy";
        
        int totalLength = str1.length() + str2.length();
        System.out.println(totalLength - 6);
        
        // Program 2
        String str3 = "Oro Plata Mata";
        System.out.println("-" + str3.indexOf("r"));
        
        // Program 3
        String str4 = "Out";
        String str5 = "Inside";
        //Inside Out
        String result1 = str5.concat(" ").concat(str4);
        System.out.println(result1);
        //Out Inside
        String result2 = str4.concat(" ").concat(str5);
        System.out.println(result2);
        
        // Program 4
        String str6 = "Programming";
        String str7 = "Coding";
        String str8 = "Writing";
        
        System.out.println("-" + str6.compareTo(str7));
        System.out.println(str8.compareTo(str6));
        System.out.println(str7.compareTo(str8));
    }
}
