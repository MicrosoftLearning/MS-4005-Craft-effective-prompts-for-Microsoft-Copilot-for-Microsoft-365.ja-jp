# 演習 - Microsoft 365 Copilot を使用して、サンプル データを確認する

このモジュールでは、次のファイルを参照する Microsoft 365 Copilot のプロンプトを作成します。

- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Mystic Spice Premium Chai Market Analysis Presentation.pptx](https://go.microsoft.com/fwlink/?linkid=2268768)
- [Mystic Spice Premium Chai Tea product description.docx](https://go.microsoft.com/fwlink/?linkid=2268929)
- [Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)

**注**: モジュール全体で参照するファイルを次に示します。 ただし、このラボでは、すべてのファイルを **OneDrive** にアップロードして、後で Copilot プロンプトにアクセスできることを確認します。

## OneDrive にファイルをアップロードする

**OneDrive**に必要なすべてのファイルをアップロードするには、次の手順を実行します。

1. テナント プロバイダーによって提供される仮想マシンに、パスワード `Pa55w.rd` を使用してローカルの**管理者**アカウントとしてログインします。
2. Windows タスクバーで、**Microsoft Edge** を選択します。
3. アドレス バーに「`https://www.office.com`」と入力します。
4. **Microsoft 365 へようこそ**の下で、**[サインイン]** を選択します。
5. **サインイン プロンプト**で、`userx@yourtenant.onmicrosoft.com` (指定したテナントから提供されたユーザー名とテナント) を入力し、**[次へ]** を選択します。

    [![リソース ペインのスクリーンショット](../media/lab_resources_password.png)](../media/lab_resources_password.png#lightbox)

6. **[パスワードの入力]** 画面で、ユーザー アカウントのパスワード (テナント プロバイダーから提供された) を入力し、**[サインイン]** を選択します。
7. **サインインの状態を維持しますか?** というプロンプトが表示されたら、**[今後、このメッセージを表示しない]** を選択して、**[はい]** を選択します。
8. **Microsoft 365** で、**[アプリ]** を選択します。
9. **[アプリ]** 内で、**[OneDrive]** を選択します。
10. **[OneDrive]** の左上隅で、**+** (新規追加)、**[ファイルのアップロード]** の順に選択します。
11. **ファイル エクスプローラー**で、**この PC** > **ローカル ディスク (C:)** の順に選択し、**ResourceFiles** フォルダーを開きます。
12. **ResourceFiles** フォルダー内のすべてのファイルを選択し、**[開く]** を選択して、**OneDrive** にアップロードします。
13. アップロードが完了すると、画面の下部中央に **マイ ファイルに 29 個のアイテムがアップロードされました** と表示されます。
14. **Edge** を開いたままにして、次のタスクに進みます。

### 参照するフィールド

Copilot からファイルを参照すると、提供された提案からファイルが見つからない場合があります。 これは、Copilot を使用する一部のエクスペリエンスでは、最近使用した (MRU) リストのファイルしか参照しませんが、他のエクスペリエンスでは、OneDrive を参照してファイルを見つけることができるために発生することがあります。 そのリストに追加するのは、適切な Microsoft 365 アプリで開くのと同じくらい簡単です。  ファイルが開かれると、MRU リストに表示されます。

> [!IMPORTANT]
> Microsoft 365 Copilot は、OneDrive に保存されたファイルでのみ機能します。 ファイルが PC のローカル フォルダーに保存されている場合は、ファイルを OneDrive に移動して Copilot をアクティブにする必要があります。

モジュールを進めるにつれて、これらのファイルに対して他のプロンプトを試す機会が得られます。自分のプロンプトのスキルを確認して強化するために実際に試してみることをお勧めします。
