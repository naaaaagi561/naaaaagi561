- 👋 Hi, I’m @naaaaagi561
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
naaaaagi561/naaaaagi561 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

//
import java.util.*;  //読み込み

public class Main {    

    public static void main(String... args) {    //...!? []と同じ意味らしい
        Scanner sc = new Scanner(System.in);    //標準入力

        int N = sc.nextInt();    //intに変換

        for (int i = 0; i < N; i++) {    
            String s = sc.next();    //入力1=s
            System.out.println(s);   //sを出力
        }
    }
}
