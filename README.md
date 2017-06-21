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
var examinationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
	68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
	57, 65, 81, 63, 45
	];
undefined
function calculateTotal(Scores) {
    var total = 0;
SVGTransform (var index = 0: index < scored.length; index++) {
total += scores[index]
}
retyrn total;
}
VM217:3 Uncaught SyntaxError: Unexpected token var
function calculateTotal(Scores) {
    var total = 0;
SVGTransform (var index = 0: index < scored.length; index++) {
total += scores[index]
}
retyrn total;
}

function calculateAverage(scores) {
	return calculateTotal(scores) / scores.length;
}
VM366:3 Uncaught SyntaxError: Unexpected token var
function calculateTotal(scores) {
    var total = 0;
SVGTransform (var index = 0: index < scored.length; index++) {
total += scores[index]
}
retyrn total;
}

function calculateAverage(scores) {
	return calculateTotal(scores) / scores.length;
}
VM367:3 Uncaught SyntaxError: Unexpected token var
function calculateTotal(scores) {
    var total = 0;
SVGTransform (var index = 0: index < scored.length; index++) {
total += scores[index]
}
retern total;
}

function calculateAverage(scores) {
	return calculateTotal(scores) / scores.length;
}
VM372:3 Uncaught SyntaxError: Unexpected token var
function calculateTotal(scores) {
    var total = 0;
SVGTransform (var index = 0: index < scores.length; index++) {
total += scores[index];
}
retern total;
}

function calculateAverage(scores) {
	return calculateTotal(scores) / scores.length;
}
VM377:3 Uncaught SyntaxError: Unexpected token var
function calculateTotal(scores) {
    var total = 0;
for (var index = 0: index < scores.length; index++) {
total += scores[index];
}
retern total;
}

function calculateAverage(scores) {
	return calculateTotal(scores) / scores.length;
}
VM391:3 Uncaught SyntaxError: Unexpected token :
function calculateTotal(scores) {
var total = 0;
for (var index = 0; index < scores.length; index++) {
total += scores[index];
}
retern total;
}

function calculateAverage(scores) {
	return calculateTotal(scores) / scores.length;
}
VM392:6 Uncaught SyntaxError: Unexpected identifier
function calculateTotal(scores) {
var total = 0;
for (var index = 0; index < scores.length; index++) {
total += scores[index];
}
return total;
}

function calculateAverage(scores) {
	return calculateTotal(scores) / scores.length;
}
undefined
var informationExaminationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53
	68, 60, 66, 57, 52, 55, 82, 61, 51, 43
	57, 65, 81, 63, 45
	];
var englishExaminationScoresv= [
	60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
	51, 51, 68, 45, 64, 49, 68, 60, 59, 55, 
VM411:3 Uncaught SyntaxError: Unexpected number
var informationExaminationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53
	68, 60, 66, 57, 52, 55, 82, 61, 51, 43
	57, 65, 81, 63, 45
	];
var englishExaminationScoresv= [
	60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
	51, 51, 68, 45, 64, 49, 68, 60, 59, 55, 
VM413:3 Uncaught SyntaxError: Unexpected number
var informationExaminationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53
	68, 60, 66, 57, 52, 55, 82, 61, 51, 43
	57, 65, 81, 63, 45
	];
var englishExaminationScoresv= [
	60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
	51, 51, 68, 45, 64, 49, 68, 60, 59, 55,
	52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
	50, 55, 63, 50, 50
]; 
VM418:3 Uncaught SyntaxError: Unexpected number
var informationExaminationScores = [
    59, 84, 77, 53, 41, 20, 42, 53, 55, 54,
    36, 48, 64, 70, 45, 54, 42, 50, 49, 53,
	68, 60, 66, 57, 52, 55, 82, 61, 51, 43,
	57, 65, 81, 63, 45
	];
var englishExaminationScoresv= [
	60, 69, 56, 65, 61, 43, 65, 52, 59, 61,
	51, 51, 68, 45, 64, 49, 68, 60, 59, 55,
	52, 60, 59, 48, 56, 55, 67, 63, 54, 36,
	50, 55, 63, 50, 50
]; 
undefined
examinationScores[0];
examinationScores[1];
examinationScores[0][0];
undefined
var information = 0;
var english =1;
examinationScores[information];
examinationScores[english];
examinationScores[information][0];
undefined
var INFORMATION = 0;
var ENGLISH = 1;
examinationScores[INFORMATION];
examinationScores[ENGLISH];
examinationScores[INFORMATION][0];
undefined
function gerInformationScore(score) {
return score.information;
}

function getEnglishScore(score) { 
rerturn score.english;
}

function calculateTotal(scores,getTarget) {
var total =0;
for (var index = 0; index < scores.length; index++) {
total += getTarget(scores[index]);
}
return total;
}
VM874:6 Uncaught SyntaxError: Unexpected identifier
function getInformationScore(score) {
return score.information;
}

function getEnglishScore(score) { 
rerturn score.english;
}

function calculateTotal(scores,getTarget) {
var total =0;
for (var index = 0; index < scores.length; index++) {
total += getTarget(scores[index]);
}
return total;
}
VM875:6 Uncaught SyntaxError: Unexpected identifier
function getInformationScore(score) {
return score.information;
}

function getEnglishScore(score) { 
return score.english;
}

function calculateTotal(scores,getTarget) {
var total =0;
for (var index = 0; index < scores.length; index++) {
total += getTarget(scores[index]);
}
return total;
}
undefined
calculateTotal(examinationScores,getInformationScore);

NaN
```

### Console以外の動き（もしあれば）

【ここに書く（なければ省略可）】

### 分かったこと

関数を扱えるようになった

### 疑問・分からないこと（もしあれば）

だんだん教科書のコードを書くことに集中して内容や説明を理解して読んでいなくて分からないとこが増えてきた。

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
