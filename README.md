# float_to_int
float から int にしたいとき
※ `using UnityEngine;` が必要
```
var x = 10.5F;
Mathf.FloorToInt(x);
// (int) x; で明示的キャストしないこと
```

# git_practice
gitコマンドの練習用

エイリアス設定が便利です。

```
git config --global alias.s status

git config --global alias.l "log --decorate --all --graph"

git config --global alias.a add

git config --global alias.f fetch

git config --global alias.p push

git config --global alias.d diff
```
