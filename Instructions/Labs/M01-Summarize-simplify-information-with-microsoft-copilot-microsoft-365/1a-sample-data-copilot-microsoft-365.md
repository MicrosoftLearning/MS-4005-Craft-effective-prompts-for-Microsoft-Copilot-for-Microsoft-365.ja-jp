このモジュールでは、次のファイルを参照する Microsoft 365 Copilot のプロンプトを作成します。

- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea Market Trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)
- [Contoso Chai Tea Market Trends 2023.docx](https://go.microsoft.com/fwlink/?linkid=2269122)
- [Market Trend Report - Protein Shake.docx](https://go.microsoft.com/fwlink/?linkid=2268827)
- [Mystic Spice Premium Chai Market Analysis Presentation.pptx](https://go.microsoft.com/fwlink/?linkid=2268768)

**注**: モジュール全体で参照するファイルを次に示します。 ただし、このラボでは、すべてのファイルを **OneDrive** にアップロードして、後で Copilot プロンプトにアクセスできることを確認します。

### OneDrive にファイルをアップロードする

**OneDrive**に必要なすべてのファイルをアップロードするには、次の手順を実行します。

1. テナント プロバイダーによって提供される仮想マシンに、パスワード `Pa55w.rd` を使用してローカルの**管理者**アカウントとしてログインします。
2. Windows タスクバーで、**Microsoft Edge** を選択します。
3. アドレス バーに「`https://www.office.com`」と入力します。
4. **Microsoft 365 へようこそ**の下で、**[サインイン]** を選択します。
5. **サインイン プロンプト**で、`userx@yourtenant.onmicrosoft.com` (指定したテナントから提供されたユーザー名とテナント) を入力し、**[次へ]** を選択します。

    [![Skillable の [リソース] ペインのスクリーンショット](../media/lab_resources_password.png)](../media/lab_resources_password.png#lightbox)

6. **[パスワードの入力]** 画面で、ユーザー アカウントのパスワード (テナント プロバイダーから提供された) を入力し、**[サインイン]** を選択します。
7. **サインインの状態を維持しますか?** というプロンプトが表示されたら、**[今後、このメッセージを表示しない]** を選択して、**[はい]** を選択します。

    **注:** ログイン後に Web ページがぼやけて表示される場合は、ページを更新します。

8. **Microsoft 365** で、**[アプリ]** を選択します。
9. **[アプリ]** 内で、**[OneDrive]** を選択します。
10. **[OneDrive]** の左上隅で、**+** (新規追加)、**[ファイルのアップロード]** の順に選択します。
11. **ファイル エクスプローラー**で、**この PC** > **ローカル ディスク (C:)** の順に選択し、**ResourceFiles** フォルダーを開きます。
12. **ResourceFiles** フォルダー内のすべてのファイルを選択し、**[開く]** を選択して、**OneDrive** にアップロードします。
13. アップロードが完了すると、画面の下部中央に **マイ ファイルに 29 個のアイテムがアップロードされました** と表示されます。
14. **Edge** を開いたままにして、次のタスクに進みます。

### Copilot でのファイルの参照

Copilot を使用する場合、一部のファイルが提案ですぐに使用できないことがあります。 これは、一部の Copilot では、**最近使用したファイル (MRU)** リストの参照ファイルしか表示されませんが、他のユーザーは **OneDrive** を直接参照できるために発生します。 **MRU** リストにファイルが表示されるようにするには、関連する Microsoft 365 アプリでファイルを開くだけで、自動的に追加されます。

> [!IMPORTANT]
> Microsoft 365 Copilot は、**OneDrive** に保存されたファイルでのみ機能します。 PC にローカルに保存されているファイルにアクセスするには、ファイルを Copilot 用に **OneDrive** に移動する必要があります。

モジュールを進めるにつれて、これらのファイルに対してさまざまなプロンプトを試す機会があります。 Copilotでスキルを向上させるために、さまざまなアプローチを自由に試してみてください。
