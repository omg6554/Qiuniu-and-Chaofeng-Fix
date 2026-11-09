囚牛・朝風 バグ修正DLL（個別版）
バージョン: 1.0.4

このZIPには修正DLLが2つ入っています。

- QiuNiu-Fix\QiuNiuFix.dll
  囚牛のステージ終了時に死亡通知の購読を解除します。
- ChaoFeng-Fix\ChaoFengFix.dll
  逆風時の負の移動倍率を正の倍率にし、速度低下を保ちながら移動不能になる問題を防ぎます。

導入方法：
1. ゲームを終了します。
2. 既存の修正フォルダーにある同名DLLを、このZIP内のDLLで上書きします。古いDLLを残して複数配置しないでください。
3. QiuNiu-Fix と ChaoFeng-Fix の各フォルダーを LobotomyCorp_Data\BaseMods に置きます。
4. Lobotomy Mod Managerで、使う修正フォルダーを有効にします。
5. 元の Qiuniu と Chaofeng のMODは有効のままにしてください。
6. 片方だけを修正したい場合は、対応するフォルダーだけ有効にします。

今回のDLLはゲーム本体・Unity・Harmonyをコンパイル時に参照しない形式で作り直しています。専用の確認用ログファイルや成功メッセージは出しません。初期化やパッチ適用に失敗した場合は、ゲーム／BaseMod標準のログにエラーが出力されます。
