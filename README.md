# 練習課題: Github Classroomでの提出結果の確認 

### 課題の説明
以下の「修正前のプログラム」を実行すると、その下の「修正前の実行結果」が得られるが、さらに下の「期待される実行結果」は得られない。そのため、GitHubの自動採点の結果は"未完成"となる。  
そこで `System.out.println` で出力する文字列を修正し、GitHubの自動採点の結果が完了となるようにプログラムを修正しなさい。ただし、ここでの"修正"とは、BlueJ上で「期待される実行結果」が得られることと、GitHubの自動採点の結果が完了することの両方が行われることを意味する。


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
