# 練習課題: Github Classroomでの提出結果の確認 

### 課題の説明
現在のプログラムは出力結果が期待される文字列に一致しないためテストにパスしない。
そこで `System.out.println` で出力する文字列を修正し、テストがグリーンになることを確認しなさい。


### 修正前のプログラム（src/main/java/Hello.java）
```
public class Hello {

	public static void main(final String[] args) {
		System.out.println("Not the right string, tests will fail!");
	}

}
```

### 修正前の実行結果
```
Not the right string, tests will fail!
```


### 期待される実行結果 (大文字・小文字・感嘆符に注意しましょう)
```
Hello world!
```
