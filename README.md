# PALINDROME-or-NOT
String s="AMMA";
String ans="";//empty string to store the output
for (int i=s.length()-1;i>=0;i--){
ans = ans+s.charAt(i);
}
if(ans.equals(s)) {
		System.out.println("palindrome");
	}
	else {
		System.out.println("not");
	}
