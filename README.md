# JavaMethodOverloading
メソッドのオーバーロード

## 処理
attackメソッドをオーバーロードする。

## コード
```
public class Sample35 {

	public static void main(String[] args) {
		attack();
		attack("スライム");
		attack(10);
		attack("ドラゴン", 3);

	}

	public static void attack() {
		System.out.println("勇者は、敵を攻撃した。");

	}

	public static void attack(String target) {
		System.out.println("勇者は、" + target + "を攻撃した。");

	}

	public static void attack(int number) {
		System.out.println("勇者は、" + number + "匹の敵を攻撃した。");

	}

	public static void attack(String target, int number) {
		System.out.println("勇者は、" + number + "匹の" + target + "を攻撃した。");

	}

}
```

## 出力結果  
```
勇者は、敵を攻撃した。
勇者は、スライムを攻撃した。
勇者は、10匹の敵を攻撃した。
勇者は、3匹のドラゴンを攻撃した。
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| 統合開発環境(IDE) | Eclipse 4.7.0 Oxygen |
| 開発言語 | Java8 |
