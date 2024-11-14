PowerPoint のMicrosoft 365 Copilot は、スライドの作成、デザイン、書式設定に役立つ AI を利用した機能です。  プレゼンテーションで伝える内容を入力すると、Copilot がプレゼンテーションを完了するのに役立ちます。 

Copilot は、最初の空白のスライドを越えて移動し、正しい方向に移動するのに役立ちます。 PowerPoint で Copilot の使用を開始するには、リボンの **[ホーム]** タブの Copilot アイコンを使用して **[Copilot]** ペインを開きます。

![PowerPoint リボンの Copilot アイコンのスクリーンショット。](../media/copilot-ribbon-powerpoint.png)

[Copilot] ウィンドウから、Word 文書または目的のトピックに関する新しいプレゼンテーションの作成を開始できます。 この例では、まず、トピックに関するプレゼンテーションを作成し、プロンプトをより堅牢にするために他の要素を追加する基本的な要求から始めます。

![最初に開いたときの PowerPoint の [Copilot] パネルのスクリーンショット。](../media/copilot-pane-powerpoint.png)

> [!TIP]
> 現在、PowerPoint で Copilot を使用すると、Word 文書からのみプレゼンテーションを作成できます。

## 作成方法を見てみましょう

まだ行っていない場合は、次のファイルをダウンロードし、そのファイルを **OneDrive フォルダー**に保存して、ファイルが MRU リストに表示されるようにします。

- **_[市場動向レポート- Protein shake.docx](https://go.microsoft.com/fwlink/?linkid=2268827)_**

> [!NOTE]
> 開始プロンプト:
>
> _新しい PowerPoint プレゼンテーションを作成する。_

この簡単なプロンプトで、_新しい PowerPoint プレゼンテーションを作成する_という基本的な**目標**から開始します。 ただし、プレゼンテーションの内容や外観に関する情報はありません。

| 要素 | 例 |
| :------ | :------- |
| 基本プロンプト: <br>**目標**から開始 | **_新しい PowerPoint プレゼンテーションを作成する。_** |
| 適切なプロンプト: <br>**コンテキスト**の追加 | **コンテキスト**を追加すると、作成するドキュメントの種類と使用対象を Copilot が把握できるようになります。<br><br>「_製品の機能と利点を潜在的なクライアントに提示する必要があります。_」 |
| 改善したプロンプト: <br>**ソース**の指定 | **ソース**を追加すると、Copilot が特定の情報を探すのに役立ちます。<br><br>「_...**/市場動向レポート - Protein shake.docx** から最新のものを使用しています。_」 |
| 最適なプロンプト: <br>明確な**期待**を設定する | 最後に、**期待**を追加すると、ドキュメントがどのような書式でどのように書かれるのが望まれるのかを Copilot が把握できるようになります。<br><br>「_製品の概要、その主な機能と利点、市場での類似製品との比較を含めてください。簡単な言語を使用してください。_」 |

> [!NOTE]
> **作成されたプロンプト**:
>
> _最新の **/市場動向レポート- Protein shake.docx** を使用して、新しい PowerPoint プレゼンテーションを作成します。製品の機能と利点を潜在的なクライアントに提示する必要があります。製品の概要、その主な機能と利点、市場での類似製品との比較を含めてください。簡単な言語を使用してください。簡単な言語を使用してください。_

[![PowerPoint で Copilot を使用してサンプル ドキュメントに対して作成されたプロンプトの結果のスクリーンショット。](../media/copilot-draft-results-powerpoint.png)](../media/copilot-draft-results-powerpoint.png#lightbox)

**目標**、**コンテキスト**、**ソース**、**期待される回答**がすべて提示され、Copilot が適切な応答を生成するのに必要なすべてが揃いました。

### ソースの参照

例のように、Copilot に既に持っているファイルからの新しいプレゼンテーションを基にさせる場合は、そうするように指示できます。 プロンプト ウィンドウで、**[ファイルからプレゼンテーションを作成]** を選択して、新しいドキュメントの作成時に Copilot が調べる**_ファイルを 3 つまで_** 選択します。

作成ボックスに「/」と参照するファイルの名前を入力して、選択対象のメニューに表示されるファイル オプションを更新することもできます。

> [!IMPORTANT]
> 参照しているファイルにアクセスするには、組織の SharePoint と OneDrive のいずれにあっても、そして Word ファイルと PowerPoint ファイルのいずれであっても、アクセス許可が必要です。

### Word 文書からプレゼンテーションを作成するときのベスト プラクティス

**Word スタイル**を活用すると、Copilot がドキュメントの構造を把握するのに役立ちます。 Word の **スタイル** を使用して文書を整理することで、Copilot は文書の構造とプレゼンテーションのスライドに分割する方法をよりよく理解できます。 必要に応じて **[タイトル]** と **[ヘッダー]** の下でコンテンツを構成すれば、Copilot は最適なプレゼンテーションを生成できます。

### プレゼンテーションに関連する画像を含める

プレゼンテーションを作成するときに、Copilot は Word 文書への画像の組み込みを試みます。 プレゼンテーションに取り入れる画像がある場合は、必ず Word 文書に画像を含めます。

### 組織のテンプレートから開始する

組織で標準テンプレートを使用している場合は、Copilot でプレゼンテーションを作成する前に、このファイルから開始します。 テンプレートから開始すると、プレゼンテーションのテーマとデザインを保持したい旨が Copilot に通知されます。 Copilot は既存のレイアウトを使用してプレゼンテーションを作成します。

> [!IMPORTANT]
> この機能は、Copilot for Microsoft 365 ライセンスまたは Copilot Pro ライセンスをお持ちのお客様が利用できます。 詳細については、「[Copilot を使用してファイルからプレゼンテーションを作成する](https://support.microsoft.com/office/create-a-new-presentation-3222ee03-f5a4-4d27-8642-9c387ab4854d)」を参照してください。