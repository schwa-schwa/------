# ウィジェット

画面表示はウィジェットを階層的に組み合わせて作成する仕組み

```
void main() {
    runApp(ウィジェット);
}

```

scaffoldインスタンスを指定して足場を作成する

appBar アプリ上部に表示されるバー

body アプリケーションの表示

StatelessWidget は静的な表示
StatefulWidget は動的な表示

stateクラスで生成したwidgetをcreatestateで表示する
