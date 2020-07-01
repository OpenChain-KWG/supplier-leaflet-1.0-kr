
# Risks caused by failure to comply

Litigation by an OSS copyright holder against a company for failure to comply with the license has occurred.

# OSS 配布時に注意を怠ったときのリスク 
実際に著作権者から訴訟を受けた事案もあります。

> # OSS 배포 시 주의해야 할 위험성들
> 실제 저작권자로부터 소송을 받은 사안도 있습니다.

Unfortunately, it has occurred that failure to comply with the OSS license resulted in litigation against the user (and distributor) by the OSS copyright holders. In at least one case, a judgement required the defendant to suspend the shipment of their products containing OSS.

In December of 2009 there was a lawsuit related to Open Source software called “Busybox”. The Busybox program is widely incorporated into embedded systems and is licensed under the GPL version 2 license. In this case, 14 companies were the subject of the lawsuit, including some in the consumer electronics industry. The remarkable thing about this case was that companies suffered litigation on products that had been made by an ODM manufacturer.

残念ながら、過去に OSS を配布する際の条件に従わなかったために、OSS の著作権者が 不適切な配布をした人を訴えたことがあります。その結果、対象となった製品の出荷禁止 の判決が下されたこともあります。

たとえば、2009年12月には組み込みシステム構築で頻繁に使われるOSSであり、GPL バージョン2で利用許諾されている「BusyBox」の不適切な利用を著作権者側が訴えた 訴訟がありました。この訴訟では、一般消費者向け製品を提供する代表的な会社も含めた 1 4 社 が 被 告 と な り ま し た 。 ラ イ セ ン ス の 規 定 で は ソ ー ス コ ード の 開 示 が 義 務 づ け ら れ て い るのにもかかわらず、開示がされていないなどの不備があったというのです。多くの会社 は和解したようです。中には判決が下されて、対象となった製品の出荷の差し止めを命じ ら れ た 会 社 も あ り ま し た 。 こ の 1 4 社 の 中 に は O D M に よ っ て 開 発 し た 自 社 ブ ラ ンド の 製 品 に含まれる不備を指摘された例も含まれています。仮に ODM によって開発された製品で も、その製品にブランド名を冠して販売した事業者は当事者になるという点にも注目すべ きです。

> OSS 라이선스를 배포할 때 요구 조건을 따르지 않은 상황에서 불행히도 OSS 저작권자가 배포한 사람을 고소하는 상황이 있었고, 그 결과, 대상 제품의 출하금지 판결이 내려지게 되었습니다.
> 
> 예를 들어, 2009 년 12 월에는 임베디드 시스템 구축에 자주 사용되는 OSS이며, GPL2.0 라이센스인 「BusyBox」을 부적절하게 사용한 사용자에게 저작권자가 고소한 소송이 있었습니다. 이 소송에서 소비자에게 제품을 판매하는 대표적인 회사를 포함한 총 14개 회사가 피고가 되었습니다. 라이센스 규정은 소스 코드 공개가 의무화 되어 있음에도 불구하고 공개가 되지 않는 등의 문제가 있었다는 것입니다. 소송 건에 대해 많은 회사는 저작권자와 합의를 한 것 같습니다. 판결이 내려져 대상이 된 일부 제품은 출하금지를 명령 받기도 하였습니다. 특히 이 14개 회사 중에 ODM업체가 개발한 제품에 자사 브랜드 제품으로 소송에 포함되어 문제를 지적 받은 사례도 포함되어 있습니다. 만일 ODM업체에 의해 개발된 제품일지라도 제품에 자사 브랜드 이름을 사용할 경우 판매한 회사는 문제의 당사자가 된다는 점에 주목하여야 할 것입니다.

In every case, it was the distributor’s failure to comply with the OSS license that resulted in the litigation. To avoid litigation, an entity working with OSS should:

-   Identify every piece of OSS in the software to be distributed
-   Understand the obligations defined by the OSS license, and comply with them.

いずれの場合も、OSS の配布に伴って配布をする人が OSS ライセンスを介して著作権者 から求められたことを適切に実施していなかったことが疑われて訴訟に至りました。訴訟を 受けるような事態はなんとしても避けるべきです。訴訟を避けるために心がけることは、次 の2点につきます。

-   配布するソフトウェアの中にどのような OSS が含まれているのかを的確に把握する こと
-   それぞれの OSS に付されたライセンスが配布時に、どのような事柄を求めているの かを的確に理解し、確実に実施すること

> 모든 경우에, OSS의 배포와 함께 배포하는 사람이 OSS 라이선스를 통해 저작권 소유자로부터 요구한 사항을 제대로 실행하지 않은 것으로 의심되어 결국 소송에 이르렀습니다. 소송을 당하는 상황은 어떻게 해서도 피해야 합니다. 소송을 피하기 위해서는 다음 두 가지 항목에 힘써야 합니다.
> - 배포하는 소프트웨어에 어떤 OSS가 포함되어 있는지 정확하게 파악하는 것
  - 각각의 OSS에 첨부된 라이센스가 배포시에 어떤 사항을 요구하는지 정확하게 이해하고 확실히 수행하는 것

## What is lost in litigation

When a company is litigated, one of the largest damages to the company is to its reputation (reputational risk). A bad reputation of not complying with software licenses may cause a company to lose the trust of other companies. The more that a company understands the importance of its trust relationships, and endeavors to build trust throughout its industry, the more serious that company is about avoiding risks to its reputation.

To respond to litigation requires a lot of work and expense. In the absence of litigation, the human resources involved in legal, procurement, engineering, and compliance could be used in more constructive tasks. This means that a company spending time responding to litigation might miss out on other business opportunities that those human resources could be working on. In particular, employing a competent lawyer for OSS litigation is very expensive.

A settlement or a legal judgement may require payment of money or a fine. In the extreme, a judgement could result in the suspension of shipment of a product, which could be quite damaging and costly.

## 訴訟で失うものは何か

訴訟を起こされて受ける最も大きなダメージは、おそらく世の中 からの信頼(reputation)が傷つくことでしょう。著作権法で守ら れているソフトウェアの利用を適切に行えていないとの悪評は他 社から受けている信頼感を損ねます。企業活動に伴う信頼関係の 重要性に気づき、信頼関係構築に腐心している企業であればある ほど、「評判を落とすリスク」(reputation risk)は深刻であるに違 いありません。

もちろん訴訟に対応するには手間もかかります。費用もかかりま す。本来だったらもっと建設的な事業や製品開発にあてられる人 的リソースを訴訟対応に割くことはビジネスチャンスに対する機 会損失になるため、是が非でも避けたいところです。また、OSS ライセンス違反に伴う訴訟に対応できる技量や経験の豊かな弁護 士に対応を依頼する費用もかさむでしょう。

和解や判決に伴い、賠償金の支払いを求められるかもしれません。 せっかくの 製 品 の 出 荷 を 差し 止 めら れ てしまうような ダ メ ー ジ を 受ける可能性も排除できません。

> 번역 필요
> 
> 담당자 : 

## Building a good relationship with the OSS community

To reduce the risk of litigation, it is essential to understand OSS principles and to comply with the obligations of the OSS licenses. In addition, it is highly recommended to contribute to the OSS community and to build good relationships with the developers of the OSS that you use.

If you understand why the authors selected a specific Open Source license for their software, and the intent of the OSS community that supports an OSS project, it will help you move beyond just fulfilling the letter of the OSS license. Understanding the intent of the developers is one of the most important benefits of having a good relation- ship with the OSS community.

A good relationship with the OSS community may enable a company to have its own new ideas adopted into the OSS. The OSS community may improve software based on your ideas and requirements. Also, engineers in your company may have the opportunity to collaborate with highly skilled OSS developers, and this could result in more satisfaction and skill for your engineers.

As the system software increases in size and functionality, it becomes more and more complex. It is harder and harder to produce software without bugs. However, if a company has a good relationship with OSS developers, the community may help your engineers find and resolve bugs, as the software is developed.


## OSS コミュニティーと良好な関係を構築する 

訴訟を受けてしまうような事態を避けるには、配布するソフトウェ アの中にある OSS を的確に把握し、ライセンスで求められてい る事柄をしっかりと実施するのがまずは基本です。これに加えて、 OSS 開発者コミュニティーに貢献し、良好な関係を構築するのも 有効な方法です。

OSS の開発を進めているコミュニティーがなぜその OSS ライセ ンスを選択したのか。その背景にはどのようなコミュニティーの 思いが込められているのかが理解できると、ただ単にライセンス 文書の字面から得られるものを超えた知見が得られるでしょう。 開発者コミュニティーとの相互信頼関係は、ほかと代えがたい重 要な価値のひとつとなるでしょう。

OSS 開発者コミュニティーと信頼関係を築くことができれば、あ なた自身が持っている OSS に対する改善事項をコミュニティー が一緒に検討してくれる可能性も生まれます。ほかにも、コミュニ ティーと交流を持つエンジニアは関係する技術領域に関して世界 最高レベルの技量を持つ人と出会える可能性があります。同じ志 を持つエンジニア同士の切磋琢磨による技量アップのチャンスも あります。コミュニティーとの連携は企業にとっても人材育成の 観点からも見逃せないことです。

昨今のソフトウェアシステムは大規模化・高度化の一途をたどり、 実に複雑に絡み合っています。このため、いくらしっかりと OSS に対する対応を進めていてもどうしてもミスをしてしまう可能性 はゼロではありません。このことに対して、OSS 開発者コミュニ ティーによっては一定の理解を示しているケースも見受けられま す。あなたがそのような人々から信頼を得ているのであれば、万 が一ミスをしてしまっても、まずは温和にその旨をコミュニティー が指摘してくれるかもしれません。

> 번역 필요
> 
> 담당자 : 

## Contributing to OSS communities

There are many ways to contribute to OSS communities: proposing bugfixes and new features, translating documents, providing places and forums where community members can communicate, and sponsoring and participating in projects and trade associations that support OSS, such as the Linux Foundation.

## コミュニティーに貢献する

コミュニティーに貢献する方法は多彩です。OSS の障害を対 応したり機能追加をするような技術的な貢献は誰でも思いつく で しょう 。 ほ か に も コ ミ ュ ニ テ ィ ー の 持 つド キ ュ メ ント を 翻 訳 す る、コミュニティーの人々が互いに出会える場所をしつらえるな ども貢献として受け取っていただけるでしょう。また The Linux Foundation など OSS コミュニティーと関係が深い団体に参加 することも選択肢のひとつとして挙げることができます。

> 번역 필요
> 
> 담당자 : 
