# remove_character

package elclipse;

public class remove_character {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		String s="harsh is the best coder";          
		String x="";
		char r='r';
		for(int i=0;i<s.length();i++) {
			if(s.charAt(i)==r) {                       

			}
			else {
				x=x+s.charAt(i);
			}
		}
		System.out.print(x);
	}

}


/////// time complexity is O(N)
