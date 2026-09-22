# Snowflake資格・試験バージョン・日本語対応の変遷

> 最終調査日：2026年9月22日  
> 調査目的：Snowflake認定資格の全体像、英語版・日本語版の公開時期、試験バージョンの変遷を整理し、SnowPro Specialty: Gen AIの日本語対応時期を検討する。

## 1. 結論

2026年9月22日時点で、Snowflake公式カタログに掲載されている試験のうち、日本語で受験できることを確認できるのは次の3系列である。

- SnowPro Core（COF-C03）
- SnowPro Advanced: Architect（ARA-C01）
- SnowPro Advanced: Data Engineer（DEA-C02）

SnowPro Specialtyは、Gen AIを含め、現時点ではすべて英語のみである。

SnowPro Specialty: Gen AI（GES-C02）について、日本語版の公式発表や公開予定日は確認できない。

公式カタログ：  
https://learn.snowflake.com/en/

## 2. 日付の読み方

Snowflakeが過去のリリース告知を残していない試験もあるため、本資料では日付を次のように区別する。

- `2026/2/16`：公式資料で公開日を確認できたもの
- `2025/8までに`：その時点で受験可能だった公開記録を確認できたもの
- `2023/10～2024/3`：前者では未対応、後者では対応済みだったため、その期間内に公開されたと判断したもの

## 3. 全資格の一覧

| 区分 | 資格・現行コード | 英語版の変遷 | 日本語版の変遷 | 主な対象範囲 |
|---|---|---|---|---|
| Associate | Platform（SOL-C01） | C01：2025/2/3 | 2025/5までに提供確認 | Snowflakeの基本操作、オブジェクト、データロード、権限、UI・Notebook、Cortexの基礎 |
| Core | Core（COF-C03） | C01：2019/9 → C02：2022/9/6 → C03：2026/2/16 | C01：2021/1～9の間 → C02：2022年後半 → C03：2026/4/15 | アーキテクチャ、ウェアハウス、データロード、SQL、性能、セキュリティ、共有 |
| Specialty | Snowpark（SPS-C01） | C01 Beta：2024/10～11、2025年初頭に本格提供 | なし | Snowpark API、Python等による処理、UDF、パイプライン、最適化 |
| Specialty | Native Apps（NAS-C02） | C01 Beta：2024/10～11 → C02：2026/7/8 | なし | Native Appの設計、構築、配布、Marketplace、セキュリティ、運用 |
| Specialty | Gen AI（GES-C02） | C01：遅くとも2025/8 → C02：2026/5 | なし | Cortex AI、LLM、RAG、Search、Analyst、文書処理、AIの権限・コスト管理 |
| Advanced | Architect（ARA-C01） | C01：遅くとも2020/10 | 2023/10～2024/3の間に追加 | エンドツーエンド設計、セキュリティ、データ基盤、性能、共有、BCP・DR |
| Advanced | Data Engineer（DEA-C02） | C01：遅くとも2021/6 → C02：2025/2/18 | C01：2024/2～2025/1の間 → C02：遅くとも2025/7 | 取り込み、変換、Stream・Task、パイプライン、性能、ガバナンス |
| Advanced | Data Scientist（DSA-C03） | C01：2021/10 → C02：2023/5/23 → C03：2026/1までに | なし | データ準備、特徴量、学習・評価、Snowpark ML、Gen AI |
| Advanced | Administrator（ADA-C02） | C01：2022/6/10 → C02：2025/12/2 | なし | RBAC、組織・アカウント管理、ガバナンス、コスト、共有、複製・DR |
| Advanced | Data Analyst（DAA-C01） | C01：2023/4 | なし | データ準備、変換・モデリング、分析、可視化、ビジネス要件 |
| Advanced | Security Engineer（SEA-C01） | C01：2026/2/2 | なし | エンタープライズセキュリティ、データ保護、プライバシー、監査・コンプライアンス |
| Advanced | MLOps Engineer（MLA-C01） | C01：2026/9/9 | なし | Feature Store、Model Registry、デプロイ、CI/CD、監視、ドリフト・コスト管理 |

### Associate Platformについて

Associate Platformは2026年春ごろまで、日本語版を含めて掲載されていたことを確認できた。ただし、2026年9月22日時点の公式資格トップページには表示されていない。

廃止を明示する公式告知も確認できないため、受験する場合はCertMetricsの予約画面で提供状況を確認する必要がある。

## 4. SnowPro Coreの変遷

### C01

- 英語版：2019年9月に一般提供開始
- 日本語版：2021年1月時点では準備中
- 2021年9月には日本語版の受験記録あり
- したがって、日本語版は2021年1月から9月の間に公開されたと推定される

### C02

- 英語版：2022年9月6日公開
- 日本語版：2022年後半に公開
- Snowflake公式ブログでは、英語版の「shortly thereafter」に日本語版を更新すると説明されていた
- 英語版C02終了：2026年5月14日
- 日本語等のローカライズ版C02終了：2026年7月31日

### C03

- 英語版：2026年2月16日公開
- 日本語版：2026年4月15日公開
- 英語版から日本語版までの差：58日

### Core関連資料

- [SnowPro Core C03公式FAQ](https://publish-p93462-e887935.adobeaemcloud.com/content/dam/SnowPro-Core-FAQS.pdf)
- [C01からC02への公式告知](https://www.snowflake.com/en/blog/updated-snowpro-core-exam-certification-announcement/)
- [2021年1月時点の日本語版準備状況](https://snaga.github.io/2021/01/16/snowflake-snowpro-core.html)
- [2021年9月の日本語版受験記録](https://qiita.com/shigeb/items/d795117174439033155a)

## 5. SnowPro Specialtyの変遷

### Snowpark（SPS-C01）

- 2024年10～11月：Beta試験の提供を発表
- 2025年初頭：本格提供開始
- 現行バージョン：SPS-C01
- 日本語版：なし

主な対象は、Snowpark API、Python・Java・Scalaを利用した処理、UDF、データパイプライン、アプリケーション開発、性能最適化など。

### Native Apps（NAS-C01、NAS-C02）

- 2024年10～11月：NAS-C01 Betaを発表
- 2026年7月7日：NAS-C01終了
- 2026年7月8日：NAS-C02公開
- C01とC02の並行提供期間はなし
- 日本語版：なし

NAS-C02では、Native Appの設計・構築・配布・運用というライフサイクル構成、実行権限、リリースチャネル、Snowpark Container Services、脆弱性スキャン、課金管理などが強化された。

### Gen AI（GES-C01、GES-C02）

- GES-C01：遅くとも2025年8月までに提供開始
- GES-C02：2026年5月15日に発表・登録案内
- GES-C01とGES-C02の並行提供：2026年7月20日まで
- 2026年9月時点の現行版：GES-C02
- 日本語版：C01、C02ともになし

GES-C02で追加・強化された主な領域は次のとおり。

- Snowflake Intelligence
- Cortex Code
- Model Context Protocol（MCP）
- AI Studio
- `AI_`プレフィックスの関数群
- Cortex Search、Cortex Analyst
- RAG、Embedding、Semantic Reranking
- 音声・画像を含むマルチモーダル処理
- Cortex専用RBAC
- AIのセキュリティ、ガードレール、コスト管理
- `AI_PARSE_DOCUMENT`、`AI_EXTRACT`等による文書処理

### Specialty関連資料

- [SnowflakeによるSpecialty資格の発表](https://www.linkedin.com/posts/snowflake-computing_snowflake-launches-snowpro-specialty-certifications-activity-7258160944923463680-hRnb)
- [Native Apps NAS-C02公式告知](https://www.linkedin.com/pulse/building-future-announcing-new-snowpro-msmic)
- [Gen AI GES-C02公式告知](https://www.linkedin.com/pulse/future-snowflake-ai-preparing-new-snowpro-91dpc)

## 6. SnowPro Advancedの変遷

### Architect（ARA-C01）

- 英語版：遅くとも2020年10月までに提供開始
- 2023年10月時点：英語のみ
- 2024年3月時点：日本語版あり
- 日本語版は2023年10月から2024年3月の間に追加されたと判断できる
- 現行バージョン：ARA-C01

対象は、Snowflake全体のアーキテクチャ、アカウント・セキュリティ設計、データ取り込み、データエンジニアリング、性能、共有、可用性、災害対策など。

### Data Engineer（DEA-C01、DEA-C02）

- DEA-C01英語版：遅くとも2021年6月までに提供開始
- 2024年2月時点：英語のみ
- 2025年1月時点：DEA-C01日本語版あり
- DEA-C02英語版：2025年2月18日公開
- DEA-C01英語版：2025年3月31日終了
- DEA-C02日本語版：遅くとも2025年7月までに提供開始
- 現行バージョン：DEA-C02

対象は、データ取り込み、変換、Stream、Task、Dynamic Table、パイプライン、共有・複製、性能最適化、ガバナンスなど。

### Data Scientist（DSA-C01、DSA-C02、DSA-C03）

- DSA-C01：2021年10月公開
- DSA-C02：2023年5月23日公開
- DSA-C03：2026年1月までに公開
- 日本語版：なし

対象は、データ準備、特徴量エンジニアリング、モデル学習・評価、Snowpark ML、生成AI・LLMなど。

### Administrator（ADA-C01、ADA-C02）

- ADA-C01：2022年6月10日公開
- ADA-C02：2025年12月2日発表・提供
- C01とC02の並行提供：2026年2月27日まで
- 日本語版：なし

ADA-C02では、Snowflake Horizon、Iceberg Tables、Polaris Catalog、AI・MLアクセス管理、パスワードレス認証、サーバーレスコスト、Data Clean Roomsなどが追加・強化された。

### Data Analyst（DAA-C01）

- 2023年4月公開
- 現行バージョン：DAA-C01
- 日本語版：なし

対象は、データ取り込み・準備、変換、モデリング、データ分析、可視化、ビジネス要件への適用など。

### Security Engineer（SEA-C01）

- 2026年2月2日公開
- 現行バージョン：SEA-C01
- 日本語版：なし

対象は、エンタープライズセキュリティ、認証・認可、データ保護、プライバシー、ガバナンス、監査、コンプライアンスなど。

### MLOps Engineer（MLA-C01）

- 2026年9月9日公開
- 現行バージョン：MLA-C01
- 日本語版：なし

対象は、機械学習アーキテクチャ、Feature Store、Model Registry、モデルのデプロイ、CI/CD、監視、モデルドリフト、性能・コスト管理など。

### Advanced関連資料

- [2023年10月時点のArchitect英語版受験記録](https://blog.flinters.co.jp/entry/2023/10/21/120000)
- [2024年3月のArchitect日本語版受験記録](https://blog.truestar.co.jp/snowflake/20240308/58777/)
- [2024年2月時点のData Engineer英語版受験記録](https://zenn.dev/dataheroes/articles/443f8b6cc959d2)
- [DEA-C01日本語版受験記録](https://dev.classmethod.jp/articles/snowflake-dea-c01-snowpro-advanced-data-engineer-exam-202501/)
- [DEA-C02日本語版の確認記録](https://qiita.com/fkdfkdfkd/items/0ab06b20c00f7b35ef72)
- [Data Scientist C02公式告知](https://www.snowflake.com/en/blog/updated-snowpro-advanced-data-scientist-certification/)
- [Administrator C01公式告知](https://www.snowflake.com/en/blog/new-advanced-snowpro-certification-added/)
- [Administrator C02公式告知](https://www.linkedin.com/pulse/elevating-excellence-announcing-new-snowpro-fkedc)
- [Security Engineer公式告知](https://www.linkedin.com/pulse/new-certification-launch-snowpro-advanced-juquc)
- [MLOps Engineer公式告知](https://www.linkedin.com/pulse/snowflake-certification-launch-snowpro-h4dvc)

## 7. 日本語化にかかった期間

| 系列 | 初めて日本語化されるまで | 日本語化後の新版追随 | 傾向 |
|---|---:|---:|---|
| Core | 約1.5～2年 | C03は58日 | 日本語の優先度が最も高い |
| Architect | 約3年以上 | まだC01のみ | 初回日本語化には長期間を要した |
| Data Engineer | 約3.5年 | C02は英語版から5か月以内 | 日本語化後の新版追随は速い |
| Associate | 4か月以内 | 改訂実績なし | 初級者向けのため早期対応された可能性あり |
| Specialty | 2024年のカテゴリ開始後も日本語版なし | 実績なし | 日本語化の優先度は現状低い |

確認できる傾向は次のとおり。

1. 一度日本語対応した資格系列は、次のバージョンも比較的早く日本語化される。
2. 新しい資格系列を初めて日本語化するまでには、おおむね1.5～3.5年程度かかっている。
3. 日本語化は、Core、Architect、Data Engineerという汎用性と受験需要の高い資格に集中している。
4. Specialtyは、SnowparkやNative Appsを含め、日本語化実績がまだ一つもない。
5. Gen AIはC01からC02まで1年未満で更新されており、翻訳中に試験内容が古くなるリスクが高い。

## 8. Gen AI日本語版の見通し

2026年9月22日時点で、GES-C02日本語版の公式発表はない。

公式Practice Examでも、日本語対応が確認できるのはCore、Architect、Data Engineerのみである。

Practice Exam一覧：  
https://learn.snowflake.com/en/certifications/snowpro-practice-exams/

### 時期別の見立て

| 時期 | 日本語化の可能性 | 判断 |
|---|---|---|
| 2026年末まで | かなり低い | 公式予告がなく、残り期間も短い |
| 2027年前半 | 低い | GES-C02の安定性と受験需要を確認する期間になる可能性が高い |
| 2027年後半～2028年 | あり得る | 他系列の初回日本語化に要した期間と整合する |
| GES-C02を日本語化せず、C03から対応 | 十分あり得る | Gen AI試験の更新速度が非常に速いため |

### 基本予測

GES-C02の日本語版は、早くても2027年後半になる可能性が高い。

ただし、GES-C02を日本語化せず、将来のGES-C03から日本語対応するシナリオも考えられる。そのため、日本語版の公開だけを待つ前提で学習計画を立てるのはリスクがある。

## 9. 取得計画

現在の候補を前提とした推奨順序は次のとおり。

1. 2026年：SnowPro Core C03日本語版
2. 2026年：SnowPro Advanced: Data Engineer C02日本語版
3. 2027年前半：SnowPro Advanced: Architect C01日本語版
4. その後：Gen AIを英語で受験、または次バージョン・日本語版の動向を確認

### Architectを先に取得する理由

- Core、Data Engineerとの知識重複が大きい
- 日本語版がすでに存在する
- Data Engineer学習後の知識を流用しやすい
- ARA-C01は長期間継続しており、将来C02へ更新される可能性がある
- Gen AIの日本語版を待つと、1～2年以上停滞する可能性がある

### Gen AIを先にしてもよいケース

業務で次の技術を直ちに使用する場合は、英語版Gen AIをArchitectより先に取得する価値がある。

- Cortex Search
- Cortex Analyst
- Snowflake Intelligence
- Cortex AI Functions
- RAG・Embedding
- 文書・画像・音声処理
- AIアプリケーションの権限・ガバナンス設計

現時点での堅実な取得順序は、次のとおり。

```text
Core → Data Engineer → Architect → Gen AI
```

SnowPro資格は原則として取得から2年間有効である。Advanced資格の受験や更新も考慮し、CoreがActiveな期間内に進める。

公式ポリシー：  
https://learn.snowflake.com/en/pages/snowpro-policies/

## 10. 現行試験ページ

- [SnowPro Core C03](https://learn.snowflake.com/en/certifications/snowpro-core-c03/)
- [SnowPro Core C03 日本語版](https://learn.snowflake.com/en/certifications/snowpro-core-jpn-C03/)
- [SnowPro Specialty: Gen AI C02](https://learn.snowflake.com/en/certifications/snowpro-GenAI-C02/)
- [SnowPro Advanced: Data Engineer C02](https://learn.snowflake.com/en/certifications/snowpro-advanced-dataengineer-C02/)
- [SnowPro Advanced: Data Engineer C02 日本語版](https://learn.snowflake.com/en/certifications/snowpro-adv-dea-jpn-C02/)

## 11. 更新時の確認ポイント

今後この資料を更新する際は、次の項目を確認する。

- 公式カタログに`GES-C02-JPN`または後継の`GES-C03-JPN`が追加されたか
- 日本語版Gen AI Study Guideが公開されたか
- 日本語版Gen AI Practice Examが追加されたか
- ArchitectがARA-C02へ更新されたか
- ARA-C02公開時に日本語版が同時または数か月以内に公開されるか
- Data EngineerがDEA-C03へ更新されたか
- Associate Platformが再掲載または正式終了したか
- Specialty SnowparkにSPS-C02または日本語版が追加されたか

---

この資料における将来予測は、公式発表ではなく、過去の英語版・日本語版の公開間隔および試験更新頻度からの推定である。
