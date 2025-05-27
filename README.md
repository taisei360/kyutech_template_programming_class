# template_programming_class

プログラミングの授業で毎回入力する必要がある
/* 123C456 九工大太郎 演習課題00 〇月〇日 */ 
を含めたファイルを作成するスクリプトです。日付も自動で入力されます。
 
# DEMO
 
![image](https://github.com/user-attachments/assets/67e97329-38dd-4570-841b-cef190852c98)
![image](https://github.com/user-attachments/assets/f419b724-19c8-41db-bc62-c18a610e6285)

# Features
 
 | オプション           | 意味                         | 使用例                         |
| --------------- | -------------------------- | --------------------------- |
| `-e`, `--emacs` | Emacs でファイルを開く             | `tpl-code -e sample.c` |
| `-v`, `--vsc`   | VSCode（`code`コマンド）でファイルを開く | `tpl-code -v sample.c` |
| （省略可能）          | オプションを省略すると Emacs が使われる    | `tpl-code sample.c`    |
| `ファイル名`         | 作成する C ファイル名（例：`main.c`）   | `tpl-code main.c`      |

 
# Usage
 
ubuntuにtpl-codeをインストール後、tpl-code中の

```
student_nameとstudent_number
```
を変更し、パスを通すと
```
tpl-code
```
 で実行できる。


# Output
```

/* your_number your_name レポート課題01 05月27日 */
#include <stdio.h>

int main(void){
    return 0;
}
```
