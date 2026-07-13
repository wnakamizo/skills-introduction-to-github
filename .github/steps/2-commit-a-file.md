## ステップ 2: ファイルをコミットする

_ブランチを作成できました！ :tada:_

ブランチを作成すると、`main` ブランチを変更せずにプロジェクトを編集できます。ブランチができたので、次はファイルを作成して最初のコミットをしましょう！

**コミットとは？**: _[コミット](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ はプロジェクト内のファイルやフォルダに対する変更のセットです。コミットはブランチの中に存在します。詳しくは「[コミットについて](https://docs.github.com/ja/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)」をご覧ください。

### :keyboard: やってみよう: 最初のコミット

以下の手順で、GitHub上で変更をコミットする方法を学びます。コミットとは、ファイルの追加・削除・名前変更やファイル内容の変更など、プロジェクトへの変更を記録することです。今回は、新しいブランチに新しいファイルを追加します。

> [!NOTE]
> `.md` はMarkdownファイルを作成するファイル拡張子です。Markdownについて詳しくは「[基本的な書き方とフォーマットの構文](https://docs.github.com/ja/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)」をご覧ください。また、「[Markdownでコミュニケーションする](https://github.com/skills/communicate-using-markdown)」のSkillsコースもあります。

1. リポジトリのヘッダーメニューにある **< > Code** タブで、新しいブランチ `my-first-branch` にいることを確認してください。

2. **Add file** ドロップダウンを選択し、**Create new file** をクリックしてください。

   <img width="300" alt="新しいファイル作成オプションのスクリーンショット" src="../images/create-new-file-option.png">

3. **Name your file...** フィールドに `PROFILE.md` と入力してください。

4. **Enter file contents here** エリアに、以下の内容をコピーして貼り付けてください：

   ```
   Welcome to my GitHub profile!
   ```

   ![PROFILE.mdファイルを追加するスクリーンショット](../images/add-profile-file.png)

5. コンテンツボックスの右上にある **Commit changes...** をクリックしてください。ダイアログが表示されます。

6. GitHubがシンプルなデフォルトメッセージを提案しますが、練習のために少し変更しましょう。**Commit message** フィールドに `Add PROFILE.md` と入力してください。

   - **コミットメッセージ** とオプションの **拡張説明** は、変更内容を明確にするのに役立ちます。特にコミットに複数のファイルが含まれる場合に便利です。

   <img width="400" alt="コミットメッセージ付きで新しいファイルを追加するスクリーンショット" src="../images/commit-message-dialog.png">

6. このレッスンでは、他のフィールドは無視して **Commit changes** をクリックしてください。

7. ファイルを変更したので、Monaがあなたの作業をチェックしているはずです。少し待って、コメントを確認してください。進捗情報と次のレッスンが表示されます。


<details>
<summary>うまくいかない場合 🤷</summary><br/>

フィードバックが表示されない場合は、以下を確認してください：
- `my-first-branch` ブランチにいることを確認してください。
- `PROFILE.md` ファイルがルートフォルダに作成されていることを確認してください。

</details>
