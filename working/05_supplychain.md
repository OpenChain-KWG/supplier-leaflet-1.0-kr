
# Supply chain issues

OSS compliance cannot be achieved by one person acting alone.

As software becomes larger and more complex, the supply chain for software also tends to become larger and more complex. A modern software supply chain may include an OSS community, a software supplier, a semiconductor vendor that provides an SDK, and a final product vendor. If any member of a large and complex software supply chain fails to comply with license obligations or fails to provide the appropriate license information, it will cause a large impact to a vendor who is obligated to comply with the license (Figure 1). Compliance failure could result in product shipment being suspended. If the vendor does not know about the failure before shipping, the vendor may receive an inquiry regarding the failure from a copyright holder or a third party, which it cannot respond to.

# ソフトウェアサプライチェーンがもたらす災厄

OSS は、あなた一人が注意しただけでは、正しく活用できません。

ソフトウェアの高度化、複雑化が進むに伴い、ソフトウェアのサプライチェーンも複雑化す る傾向があります。ソフトウェアサプライチェーンを構成する企業・団体としては、OSS 開 発コミュニティー、ソフトウェア開発業者、OSS パッケージ構築事業者(OSS ディストリ ビュータ)、SDK などを提供する半導体事業者、最終製品開発事業者などが挙げられます。

複雑化したソフトウェアサプライチェーンの中の一部で OSS の不適切な利用があったり、 OSS の利用についての適切な情報、ライセンス遵守のために必要な材料の伝搬がされな い と 、 最 終 製 品 を 作 り 上 げ る 段 階 で 大 き な 問 題 に な り ま す ( 図 1 )。 お そ ら く 最 終 製 品 が 出 荷できなくなる事態は容易に想像できます。さらに不都合なことは最終製品を出荷する時 点で問題があることに気がつかず、製品を出荷したあとで問題点に気がついた第三者や問 題の対象となる OSS の著作権者から指摘を受けることです。

> 번역 필요
> 
> 담당자 : 

However, if software compliance is managed appropriately in the upstream supply chain, these problems can be avoided. To facilitate compliance with OSS licenses, all participants in the supply chain must do their duty, build trust throughout the supply chain, and communicate appropriate information regard- ing included software.

It is recommended that each company in the supply chain establish a team to ensure OSS compliance in the chain. The Linux Foundation’s OpenChain project provides a Self Certification program that companies can use for this purpose. The Self Certification helps a company check its compliance process. The certification test is available in several languages and anyone can use it for free.

https://certification.openchainproject.org/


仮に OSS の扱いに対して不適切な状況があったとしても、サプライチェーンの上流段階で 問題を把握して対策を講じることができれば、問題発生を未然に防げます。サプライチェー ン問題を回避するには、サプライチェーンを構成する企業・団体それぞれがすべきことを 的確に実施し、相互に信頼関係を構築し、互いに適切な情報や必要な素材(たとえばソー スコードなど)の受け渡しをしっかりと行うしかありません。

サプライチェーンを構成する企業・団体などは内部で OSS に対応する体制を構築するのが 望ましいでしょう。自社の OSS に対する準備がどの程度整っているのかを知るには、The Linux Foundation、OpenChainプロジェクトが作成したSelf Certification(自己チェッ クテスト)をすることをお勧めします。このテストは誰でも無料で使えます。以下のサイト にアクセスしてみてください。

https://certification.openchainproject.org/

> 번역 필요
> 
> 담당자 : 

## Requirements for participants in the supply chain

When a supplier distributes software, the supplier is required to provide to each recipient the information that is needed to comply with the OSS license. A recipient should review the data and files carefully and verify that they are accurate.

A software distributor may include software from multiple suppliers for a single product. In this case, the distributor is required to receive information about each OSS component it receives, along with the software.

If information about an OSS component is not received, such OSS should not be incorporated into a product.

## サプライチェーンを構成する企業・団体等に求め られること  

ソフトウェアを供給する場合は、供給先に対して OSS に関する情 報を提供します。また、供給先もOSSライセンス遵守できるよう にOSSに関するデータ、ファイルなどを精査し、OSS情報も十 分に確認するようにしてください。

ソフトウェアの供給を行う側も、別途ソフトウェアの供給を受ける こともあります。その場合は、あなたも供給を受けたソフトウェア に関わる OSS に関する適切な情報を入手しなければなりません。 ほかから入手するソフトウェアの中に含まれる OSS について適切 な情報(ファイル等含む)がない場合は、そのようなソフトウェア は利用すべきではありません。

サプライチェーンを構成する人に求められることを実現するには、 社内のさまざまな立場の人が適切な行動をする必要があります。

> 번역 필요
> 
> 담당자 : 

## Different roles in a company have different responsibilities for OSS compliance

### Software developers

Software developers should manage, record and store the configuration of the software. This includes the following:

-   OSS and its license
-   Linkage (e.g. libraries used by the software, dynamic or static linkage, etc.)
-   Modifications. That is, the technical details of any modifications made to the software.
    
These items must be identified and listed. Any time the software configuration changes, the list should be updated. The license may change from one release of software to the next, for a particular project. It is recommended to create and manage the list so that each OSS item is easily referenced and reviewed. Some licenses (for example, the GPL license) require a distributor to disclose the source code. It is highly recommended that source control management software is used to track the original source code and any changes to the source code.

### エンジニアが留意すべきこと

ソフトウェア開発にかかわるエンジニアは、ソフトウェアの構成を 的確に管理し、記録し、保管するようにします。この記録の中には、 以下のものなどが含まれます。

-  どのような OSS がどのような条件で使われたか
-  ライブラリのリンク方式  
-  改変の有無。改変をした場合は技術的な詳細

これらの事柄を正しく把握し、記録します。構成に変更事項があっ た場合は、こまめに加筆修正するようにします。特に OSS はバー ジョンによってライセンス条件が変わることも珍しくありません。 具体的にどの OSS を使ったのか、ピンポイントでわかるような記 録が求められます。また、ソフトウェアを外部にリリースする際に ソースコードの開示などを求められるライセンスもあります(GPL など)。このため、ソースコードなどを適切に維持管理することも 強くお勧めします。

> 번역 필요
> 
> 담당자 : 

### Software procurement personnel

Software procurement personnel must receive information about any OSS in the incoming software, for software engineers to record. OSS may be included in software like the SDK provided by a semiconductor vendor.

Procurement personnel are required to pay attention to the software in all the different kinds of deliverables that the company receives.

### 調達担当者が留意すべきこと

外部からもたらされるソフトウェアの中にどのような OSS が含ま れるのか、ソフトウェア開発者が的確に管理できるような情報など を確実に入手するべきです。半導体企業から半導体の付属物とし てもたらされる小規模なソフトウェア(SDK など)でも注意しなく てはなりません。

> 번역 필요
> 
> 담당자 : 

### Sales personnel

Sales personnel are required to communicate with customers regarding OSS. A customer may have special requirements related to the use of OSS. For example, a company may have an OSS policy that precludes it from using OSS with specific licenses.

It is important for sales personnel learn of customers’ requirements regarding OSS, and communicate this information to internal software developers.

###  営業担当者が留意すべきこと

自分の会社の成果物を受け取る人たちが、OSS にどのように対 応すべきか情報を求めていたら、真摯に傾聴してください。顧客 によってはOSSの利用について特別な注意を払っているかもし れません。たとえば、ポリシーとして特定の OSS ライセンスで利 用許諾された OSS の使用を禁止している場合があるかもしれま せん。このような顧客ごとの事情を把握し、自社の開発部門に伝 える営業担当者の役割はきわめて重要です。

> 번역 필요
> 
> 담당자 : 

### Legal / Intellectual property personnel

Cooperation with legal and intellectual property personnel is indispensable for understanding OSS licenses. Legal and intellectual property personnel should review the licenses that govern the OSS used by a company and advise developers as to its use:

-   What approvals are needed for using OSS? (In general, OSS licenses disclaim liability for the developer of the software.)
-   What is required in order to distribute the OSS?
-   Can the inclusion of OSS cause a problem when the software is used by downstream recipients?

### 法務・知財担当者が留意すべきこと

OSS ライセンスを適切に理解するには法務・知財担当者の協力 が不可欠です。扱うことになった OSS に付されているライセンス それぞれについて適切な助言をするようにお願いします。特に以 下の点について尋ねてみてください。

-   OSS を入手し、利用するにあたって、どのような事柄を承 諾することになるのか(一般的には、OSS の開発者には一 切の責任がないことを認めることになります)
-   OSS を顧客、ビジネスパートナーなど社外に配布するとき に、配布をする者に求められている事柄は何か
-   (こちらから提供する)ソフトウェア成果物を入手する顧客に とって、成果物に含まれる OSS が支障となる可能性はない のか

> 번역 필요
> 
> 담당자 : 

### Executives and Managers
    
To use OSS effectively and appropriately requires the cooperation of different staff inside a company.
    
Executives and managers may need to facilitate coordination between internal organizations and may decide to establish a dedicated team to manage OSS-related issues. This includes investments in human resources, training, and development environments.

### 経営者、管理職の方々が留意すべきこと
    
OSS の適切な対応には社内のさまざまな担当による協力関係が 必要です。スムースな協力関係の構築、さらには協力関係のコア となる組織作りなど、人的投資、人材育成、費用投資などが求め られることもあるでしょう。このような事柄に理解を深め、適切な 対応をするよう期待します。

> 번역 필요
> 
> 담당자 : 
