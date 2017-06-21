# 6/21 課題 学んだ記録

自身が学んだ記録を作りましょう。

- 関数(`function` で始まるコード)は全て function.js に書きます
- その他をREADME.md（このファイル）に書いていきます
    - 書き方は README-example.md (同じフォルダに同梱) を参考にしてください
- 書き方は自身でアレンジしてもかまいません


--------------------------------------

## 授業スライドの説明（4時間目～5時間目）

説明の中で実行したログ、分かったこと、疑問などがあればここに書く。

### Consoleの実行ログ

```
【function sumInformationScore(scores){

	var total = 0;
	for (var index = 0; index < scores.length; index++){
	   total += scores[index].information;
    }
return total;

}

function sumEnglishScore(scores){
	var total = 0;
	for (var index = 0; index < scores.length; index++){
		total += scores[index].english;

    }

	return total;

}
undefined
 callTarget(target) { return target(); };
VM461:1 Uncaught SyntaxError: Unexpected token {
function callTarget(target) { return target(); };
undefined
function returnSomeString() {return 'Samplw'}
undefined
function returnSomeString() {return 'Sample'; }
undefined
 callTarget (returnSomeFunction);
VM617:1 Uncaught ReferenceError: returnSomeFunction is not defined
    at <anonymous>:1:14
(anonymous) @ VM617:1
 callTarget(returnSomeString);
"Sample"
returnSomeFunction();
VM712:1 Uncaught ReferenceError: returnSomeFunction is not defined
    at <anonymous>:1:1
(anonymous) @ VM712:1
function returnSomeString() {return 'Sample'; };
undefined
function returnSomeString() {return returnSomeString; };
undefined
returnSomeFunction();
VM755:1 Uncaught ReferenceError: returnSomeFunction is not defined
    at <anonymous>:1:1
(anonymous) @ VM755:1
returnSomeFunction()();
VM758:1 Uncaught ReferenceError: returnSomeFunction is not defined
    at <anonymous>:1:1
(anonymous) @ VM758:1
calculateTotal(examinationScores, getInformationScore);
VM874:1 Uncaught ReferenceError: calculateTotal is not defined
    at <anonymous>:1:1
(anonymous) @ VM874:1
var functionVar1 = () => '1st';
undefined
functionVar1();
"1st"
functionVar1 = () => '2nd';
() => '2nd'
functionVar1();
"2nd"
var functionVar1 = function function1() { console.log(function1);};
undefined
var total = 0
undefined
examinationScores.forEach(score => total += score.information);
VM1201:1 Uncaught ReferenceError: examinationScores is not defined
    at <anonymous>:1:】
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【ここに書く】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】

--------------------------------------

以下、教科書の自分で読んだ・実行した箇所について書く。

## 5-x ○○ (p.xx)

### Consoleの実行ログ

```
【ここに書く】
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

【ここに書く】

### 疑問・分からないこと（もしあれば）

【ここに書く（なければ省略可）】
