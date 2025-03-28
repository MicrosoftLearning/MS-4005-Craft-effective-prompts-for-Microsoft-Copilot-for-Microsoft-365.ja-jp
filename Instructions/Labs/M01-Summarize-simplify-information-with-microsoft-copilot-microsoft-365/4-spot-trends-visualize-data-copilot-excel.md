# Excel で Copilot を使用して傾向を特定し、データを視覚化する

Excel の Microsoft 365 Copilot は、数式列の提案を生成し、チャートやピボットテーブルに分析情報を表示し、データの興味深い部分を強調表示することで、Excel テーブルのデータをさらに活用するのに役立ちます。

Excel で、リボンの **[Copilot]** を選択してチャット ペインを開きます。

![Excel リボンの Copilot アイコンのスクリーンショット。](../media/summarize_copilot-ribbon-excel.png)

Copilot in Excel を使用するには、次のいずれかの方法でデータを書式設定する必要があります。

- Excel の表として
- サポート範囲として

次の手順に従うことで、表を作成することも、データ範囲がある場合はセル範囲を表に変換することもできます。

1. データ内のセルまたは範囲を選択します。

1.  **[ホーム]、[テーブルとして書式設定]** の順に選択します。

1. 範囲の最初の行をヘッダー行にする場合は、 **[テーブルとして書式設定]** ダイアログ ボックスで、 **[先頭行をテーブルの見出しとして使用する]** の横にあるチェックボックスをオンにします。

1.  **[OK]** を選択します。

データを範囲内に保持し、表に変換しない場合は、次のすべての要件を満たす必要があります。

- ヘッダー行は 1 行のみ
- ヘッダーは列にのみ存在し、行には含まれない
- ヘッダーは一意で、重複するヘッダーがない
- 空白のヘッダーがない
- データは一貫した方法で書式設定されている
- 小計がない
- 空の行または列がない
- 結合されたセルがない

次の例では、まず、表を分析し、プロンプトをより堅牢にするために要素を追加する基本的な要求から始めます。

![初めて開いたときの Excel の [Copilot] パネルのスクリーンショット。](../media/summarize_copilot-pane-excel.png)

## 作成方法を見てみましょう

まず、まだ行っていない場合は、**_[Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)_** をダウンロードし、ファイルを **OneDriveフォルダー**に保存します。

Excel でスプレッドシートを開き、リボンの **[ホーム]** タブで Copilot アイコンを選択して **[Copilot]** ペインを開きます。以下のプロンプトを入力し、操作を進めます。

> [!NOTE]
> 開始プロンプト:
>
> _Excel でこの表を分析します。_

この簡単なプロンプトで、_"Excel テーブルを分析する"_ という基本的な**目標**から開始します。 しかし、表を要約する必要がある理由や、要約が必要な理由に関する情報はありません。

| 要素 | 例 |
| :------ | :------- |
| **基本的なプロンプト:** **目標**から開始 | **Excel でこの表を分析します。** |
| **適切なプロンプト:** **コンテキスト**の追加 | **コンテキスト**を追加すると、Copilot が分析の目的を理解し、それに応じて応答を調整できるようになります。 _「手作りのチャイの売上または作り置きのチャイの売上で 5 月から 8 月までのトップセラー製品を探しています。」_ |
| **プロンプトの改善:** **ソースの指定** | **ソース**を追加すると、特定の情報または範囲を使用するように指示することで、Copilot がスコープを絞り込めるようになります。 _「...5 月から 8 月までの手作りのチャイの売上または作り置きのチャイの売上...」_ |
| **最適なプロンプト:** 明確な**期待**の設定 | 最後に、 **期待される回答** を追加すると、概要の書式設定方法と必要な詳細レベルをCopilotが理解するのに役立ちます。 _「各月のトップセラー製品を要約してください。」_ |

> [!NOTE]
> **作成されたプロンプト**:
>
> _Excel でこの表を分析してください。手作りのチャイの売上または作り置きのチャイの売上で 5 月から 8 月までのトップセラー製品を探しています。各月のトップセラー製品を要約してください。_

このプロンプトでは、**目標**、**コンテキスト**、**ソース**、**期待**など、適切な回答を出すのに必要なすべての情報が Copilot に提供されます。

## さらに探索

自分の Excel テーブルを使用して、作成したプロンプトの最終版やその他を試してみてください。 試すプロンプトに関するいくつかの提案を次に示します。 それらをコピーし、**コンテキスト**、**ソース**、および**期待**を追加します。  

- カテゴリ別で売上の経時変化をプロットします。

- 各製品の総売上を表示します。

- 昨年の各リージョンの広告売上の合計を表示します。

> [!IMPORTANT]
> この機能は、Microsoft 365 Copilot ライセンスまたは Copilot Pro ライセンスをお持ちのお客様が利用できます。 Excel テーブルとその作成方法の詳細については、「[Excel でテーブルを作成する](https://support.microsoft.com/office/bf0ce08b-d012-42ec-8ecf-a2259c9faf3f)」をご覧ください。
