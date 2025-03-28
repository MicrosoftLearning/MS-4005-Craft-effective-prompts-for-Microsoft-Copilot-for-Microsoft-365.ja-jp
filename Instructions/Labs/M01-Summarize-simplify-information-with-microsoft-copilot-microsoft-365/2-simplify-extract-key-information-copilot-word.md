# Word で Copilot を使用して重要な情報を簡略化して抽出する

Word で Microsoft 365 Copilot の使用を開始するには、リボンの **[ホーム]** タブで Copilot アイコンを選択して **[Copilot]** ペインを開きます。

![Word リボンの Copilot アイコンのスクリーンショット。](../media/summarize_copilot-ribbon-word.png)

この便利な機能は、ドキュメントに関する幅広い質問や特定の質問に対する回答を提供します。 繰り返しディスカッションを行い、結果を反復処理して絞り込んだり、ドキュメントの内容に関する概要や特定の情報を取得したり、ドキュメントにコピーして挿入できるアイデア、テーブル、リストを生成するように依頼したりします。

![初めて開いたときの Word の [Copilot] パネルのスクリーンショット。](../media/summarize_copilot-pane-word.png)

次の例では、Word の Copilot に対する基本的なプロンプトを、必要なものだけを必要な方法で提供する、適切に構築されたコンテキスト プロンプトに変換します。

## 作成方法を見てみましょう

まず、まだ行っていない場合は、**_[Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)_** をダウンロードし、**OneDrive フォルダー**にファイルを保存します。

Word で文書を開き、リボンの **[ホーム]** タブで **Copilot** アイコンを選択して [Copilot] ウィンドウを開きます。以下のプロンプトを入力し、操作を進めます。

> [!NOTE]
> 開始プロンプト:
>
> _この Word ドキュメントを要約してください。_

この簡単なプロンプトで、_Word ドキュメントを要約する_という基本的な**目標**から開始します。 しかし、ドキュメントを要約する必要がある理由や、要約が何に必要なのかに関する情報はありません。

| 要素 | 例 |
| :------ | :------- |
| **基本的なプロンプト:** **目標**から開始 | **この Word ドキュメントを要約してください。** |
| **適切なプロンプト:** **コンテキスト**の追加 | **コンテキスト** を追加すると、Copilot が概要の目的を理解し、それに応じて応答を調整するのに役立ちます。 _「明日の営業会議中にチームと話し合うための要点の概要。」_ |
| **プロンプトの改善:** **ソースの指定** | **ソース**を追加すると、要約する必要があるドキュメントまたは部分を Copilot が把握し、より正確な応答ができるようになります。 _「...競合分析に関するセクション…」_ |
| **最適なプロンプト:** 明確な**期待**の設定 | 最後に、 **期待される回答** を追加すると、概要の書式設定方法と必要な詳細レベルをCopilotが理解するのに役立ちます。 _「要約は 5 つの重要な点を挙げるに留めて、簡単な言葉を使用してください。」_ |

> [!NOTE]
> **作成されたプロンプト**:
>
> _この Word ドキュメントの競合分析に関するセクションを、明日の営業会議でチームと話し合う要点の概要を入れて要約してください。要約は重要なポイントを 5 つに収め、シンプルな表現を使用してください。_

このプロンプトには、必要なすべての詳細 (**目標**、**コンテキスト**、**ソース**、**期待**) があるため、Copilot は求められた回答を提供できます。

## さらに探索

作成したプロンプトの最終版を試しますが、自分の Word ドキュメントを使用してください。 **コンテキスト**、**ソース**、および**期待**をカスタマイズして、ドキュメントから必要なものを取得し、余計なものを追加しないようにします。

プロンプトにコンテキスト、ソース、または期待を追加する方法で、他に考え付くものは何ですか? 求める応答を生成するために利用できる他のプロンプト戦略を考え出せますか?

> [!IMPORTANT]
> この機能は、Microsoft 365 Copilot ライセンスまたは Copilot Pro ライセンスをお持ちのお客様が利用できます。 詳細については、「[Word の Copilot へようこそ](https://support.microsoft.com/office/welcome-to-copilot-in-word-2135e85f-a467-463b-b2f0-c51a46d625d1)」をご覧ください。

次のユニットでは、PowerPoint での Copilot に対して同様のプロンプトを作成する方法について説明します。
