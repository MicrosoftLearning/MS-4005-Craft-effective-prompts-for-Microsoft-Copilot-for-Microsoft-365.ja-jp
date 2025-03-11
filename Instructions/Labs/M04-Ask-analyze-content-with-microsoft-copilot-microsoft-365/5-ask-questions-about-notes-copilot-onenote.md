# OneNote で Microsoft 365 Copilot を使用して、ノートに関する質問をする

OneNote の Copilot はメモ作成を強化するものであり、情報を理解したり、作成したり、思い出したりするのに役立ちます。 OneNote の Copilot では、事前に定義された一連のプロンプトによって制限されることはありません。 Copilot と自由にチャットして、さまざまな複雑なタスクを完了して、OneNote を貴重なアシスタントに変換できます。

Copilot とチャットすると、次のことに役立ちます。

- ノート内の情報を検索します。

- ノートを改善するためのヒントと推奨事項を取得します。

- ノートに追加する新しい情報について説明します。

OneNote の Copilot とチャットするには、次の手順に従います。

1. リボンで **[Copilot]** を選択し、[Copilot] ペインを開きます。

1. **Copilot の作成ボックス**で、Copilot にタスクの完了を求めるプロンプト、または Copilot に質問を求めるプロンプトを入力します。

1. **[送信]** 矢印を選択します。

## 作成方法を見てみましょう

まず、次のテキストをコピーして新しい OneNote ページに貼り付けます。

```text
    Q1 Webinars
        1. AI in Business
    
            Date: January 15, 2024
            Total Attendees: 450
            Engagement Rate: 72% (Active participation in Q&A, polls, and chat)
            Key Takeaways:
            - AI is reshaping customer service with automated chatbots.
            - Predictive analytics help businesses forecast trends.
            - Ethical AI considerations are becoming a priority.
        
        2. Cloud Security Best Practices
        
            Date: February 10, 2024
            Total Attendees: 385
            Engagement Rate: 65%
            Key Takeaways:
            - Zero Trust security models are on the rise.
            - Multi-factor authentication reduces data breaches.
            - Compliance requirements for cloud security continue to evolve.
        
        3. Future of Remote Work
    
            Date: March 5, 2024
            Total Attendees: 500
            Engagement Rate: 80%
            Key Takeaways:
            - Hybrid work models are now the standard for many companies.
            - Virtual collaboration tools are improving productivity.
            - Employees expect flexibility but still value in-person interaction.
```

> [!NOTE]
> 開始プロンプト:
>
> _どのウェビナーに最も多くの参加者が集まりましたか？_

この簡単なプロンプトで、_どのウェビナーに最も多くの参加者が集まったかを見つける_という基本的な**目標**から開始します。 ただし、さらに多くの情報を提供して、Copilot が有用な応答を生成できるようにすることもできます。

| 要素 | 例 |
| :------ | :------- |
| **基本的なプロンプト:** **目標**から開始 | **_どのウェビナーに最も多くの参加者が集まりましたか？_** |
| **適切なプロンプト:** **コンテキスト**の追加 | **コンテキスト**を追加すると、必要な情報を Copilot が把握できるようになります。 _「...四半期ごとのビジネス レビューのため。」_ |
| **プロンプトの改善:** **ソースの指定** | このプロンプトの**ソース**は OneNote のノートブックと見なされますが、特定のページやトピックを参照することでさらに具体的な情報を得ることができます。 _「前四半期のメモの出席データを参照してください。」_ |
| **最適なプロンプト:** 明確な**期待**の設定 | 最後に、**期待**を追加すると、結果を微調整する方法を Copilot が理解できるようになります。 _「各ウェビナーの参加者の合計数と平均参加率を計算してください。出席参加率が最も高かったウェビナーを特定し、そのトピックと重要なポイントの簡単な概要を提供してください。」_ |

> [!NOTE]
> **作成されたプロンプト**:
>
> _四半期ごとのビジネス レビューへの参加者数と参加者数が最も多かったウェビナーはどれですか? 前四半期のノートの出席データを参照してください。各ウェビナーの参加者の合計数と平均参加率を計算してください。出席参加率が最も高かったウェビナーを特定し、そのトピックと重要なポイントの簡単な概要を提供してください。_

このプロンプトには**目標**、**コンテキスト**、**ソース**、**期待**があるため、Copilot が確かな回答を提供するのに必要なすべての情報が提供されます。

> [!IMPORTANT]
> この機能は、Microsoft 365 Copilot ライセンスまたは Copilot Pro ライセンスをお持ちのお客様が利用できます。 詳細については、「[メモや研究の質問について Copilot とチャットする](https://support.microsoft.com/office/chat-with-copilot-about-your-notes-and-research-questions-8be75b91-d4d3-461e-af9a-fadfe208b589)」を参照してください。
