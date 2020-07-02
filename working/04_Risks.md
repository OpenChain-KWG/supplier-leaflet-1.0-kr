
# Risks caused by failure to comply

Litigation by an OSS copyright holder against a company for failure to comply with the license has occurred.

# OSS 配布時に注意を怠ったときのリスク 
実際に著作権者から訴訟を受けた事案もあります。

> # OSS 배포 시 주의해야 할 위험성들
> 실제 저작권자로부터 소송을 받은 상황도 있었습니다.

Unfortunately, it has occurred that failure to comply with the OSS license resulted in litigation against the user (and distributor) by the OSS copyright holders. In at least one case, a judgement required the defendant to suspend the shipment of their products containing OSS.

In December of 2009 there was a lawsuit related to Open Source software called “Busybox”. The Busybox program is widely incorporated into embedded systems and is licensed under the GPL version 2 license. In this case, 14 companies were the subject of the lawsuit, including some in the consumer electronics industry. The remarkable thing about this case was that companies suffered litigation on products that had been made by an ODM manufacturer.

残念ながら、過去に OSS を配布する際の条件に従わなかったために、OSS の著作権者が 不適切な配布をした人を訴えたことがあります。その結果、対象となった製品の出荷禁止 の判決が下されたこともあります。

たとえば、2009年12月には組み込みシステム構築で頻繁に使われるOSSであり、GPL バージョン2で利用許諾されている「BusyBox」の不適切な利用を著作権者側が訴えた 訴訟がありました。この訴訟では、一般消費者向け製品を提供する代表的な会社も含めた 1 4 社 が 被 告 と な り ま し た 。 ラ イ セ ン ス の 規 定 で は ソ ー ス コ ード の 開 示 が 義 務 づ け ら れ て い るのにもかかわらず、開示がされていないなどの不備があったというのです。多くの会社 は和解したようです。中には判決が下されて、対象となった製品の出荷の差し止めを命じ ら れ た 会 社 も あ り ま し た 。 こ の 1 4 社 の 中 に は O D M に よ っ て 開 発 し た 自 社 ブ ラ ンド の 製 品 に含まれる不備を指摘された例も含まれています。仮に ODM によって開発された製品で も、その製品にブランド名を冠して販売した事業者は当事者になるという点にも注目すべ きです。

> OSS 라이선스를 배포할 때 요구 조건을 따르지 않은 상황에서 불행히도 OSS 저작권자가 배포한 사람을 고소하는 상황이 있었고, 그 결과, 대상 제품의 출하금지 판결이 내려지게 되었습니다.
> 
> 예를 들어, 2009 년 12 월에는 임베디드 시스템 구축에 자주 사용되는 OSS이며, GPL2.0 라이스인 「BusyBox」을 부적절하게 사용한 사용자에게 저작권자가 고소한 소송이 있었습니다. 이 소송에서 소비자에게 제품을 판매하는 대표적인 회사를 포함한 총 14개 회사가 피고가 되었습니다. 라이센스 규정은 소스 코드 공개가 의무화 되어 있음에도 불구하고 공개가 되지 않는 등의 문제가 있었다는 것입니다. 소송 건에 대해 많은 회사는 저작권자와 합의를 한 것 같습니다. 판결이 내려져 대상이 된 일부 제품은 출하금지를 명령 받기도 하였습니다. 특히 이 14개 회사 중에 ODM업체가 개발한 제품에 자사 브랜드 제품으로 소송에 포함되어 문제를 지적 받은 사례도 포함되어 있습니다. 만일 ODM업체에 의해 개발된 제품일지라도 제품에 자사 브랜드 이름을 사용할 경우 판매한 회사는 문제의 당사자가 된다는 점에 주목하여야 할 것입니다.

In every case, it was the distributor’s failure to comply with the OSS license that resulted in the litigation. To avoid litigation, an entity working with OSS should:

-   Identify every piece of OSS in the software to be distributed
-   Understand the obligations defined by the OSS license, and comply with them.

いずれの場合も、OSS の配布に伴って配布をする人が OSS ライセンスを介して著作権者 から求められたことを適切に実施していなかったことが疑われて訴訟に至りました。訴訟を 受けるような事態はなんとしても避けるべきです。訴訟を避けるために心がけることは、次 の2点につきます。

-   配布するソフトウェアの中にどのような OSS が含まれているのかを的確に把握する こと
-   それぞれの OSS に付されたライセンスが配布時に、どのような事柄を求めているの かを的確に理解し、確実に実施すること

> 모든 경우에, OSS의 배포와 함께 배포하는 사람이 OSS 라이선스를 통해 저작권 소유자로부터 요구한 사항을 제대로 실행하지 않은 것으로 의심되어 결국 소송에 이르렀습니다. 소송을 당하는 상황은 어떻게 해서도 피해야 합니다. 소송을 피하기 위해서는 다음 두 가지 항목에 힘써야 합니다.
> - 배포하는 소프트웨어에 어떤 OSS가 포함되어 있는지 정확하게 파악하는 것
> - 각각의 OSS에 첨부된 라이선스가 배포시에 어떤 사항을 요구하는지 정확하게 이해하고 확실히 수행하는 것

## What is lost in litigation

When a company is litigated, one of the largest damages to the company is to its reputation (reputational risk). A bad reputation of not complying with software licenses may cause a company to lose the trust of other companies. The more that a company understands the importance of its trust relationships, and endeavors to build trust throughout its industry, the more serious that company is about avoiding risks to its reputation.

To respond to litigation requires a lot of work and expense. In the absence of litigation, the human resources involved in legal, procurement, engineering, and compliance could be used in more constructive tasks. This means that a company spending time responding to litigation might miss out on other business opportunities that those human resources could be working on. In particular, employing a competent lawyer for OSS litigation is very expensive.

A settlement or a legal judgement may require payment of money or a fine. In the extreme, a judgement could result in the suspension of shipment of a product, which could be quite damaging and costly.

## 訴訟で失うものは何か

訴訟を起こされて受ける最も大きなダメージは、おそらく世の中 からの信頼(reputation)が傷つくことでしょう。著作権法で守ら れているソフトウェアの利用を適切に行えていないとの悪評は他 社から受けている信頼感を損ねます。企業活動に伴う信頼関係の 重要性に気づき、信頼関係構築に腐心している企業であればある ほど、「評判を落とすリスク」(reputation risk)は深刻であるに違 いありません。

もちろん訴訟に対応するには手間もかかります。費用もかかりま す。本来だったらもっと建設的な事業や製品開発にあてられる人 的リソースを訴訟対応に割くことはビジネスチャンスに対する機 会損失になるため、是が非でも避けたいところです。また、OSS ライセンス違反に伴う訴訟に対応できる技量や経験の豊かな弁護 士に対応を依頼する費用もかさむでしょう。

和解や判決に伴い、賠償金の支払いを求められるかもしれません。 せっかくの 製 品 の 出 荷 を 差し 止 めら れ てしまうような ダ メ ー ジ を 受ける可能性も排除できません。

> ## 소송에서 잃는 것은 무엇인가?
> 소송으로 받는 가장 큰 피해는 아마도 세상의 명예(reputation)가 손상된 것입니다. 저작권법으로 보호되는 소프트웨어를 제대로 사용하지 않는다는 악명은 기존의 다른 회사에서 받고 있는 신뢰감을 훼손할 수 있습니다. 기업 활동에 따른 신뢰의 중요성을 인식하고 신뢰관계 구축에 부심하고 있는 기업일수록 '명예훼손 위험"(reputation risk)은 심각한 문제임에 틀림 없습니다.
> 물론 소송에 대응하는 노력도 필요하며, 비용도 소요됩니다. 원래라면 더 건설적인 사업과 제품 개발에 충당해야 할 인적자원을 소송 대응에 할애하는 것은 비즈니스적인 기회 손실이 발생하므로 절실하게 피하고 싶은 상황입니다. 또한 OSS 라이선스 위반에 따른 소송에 대응할 수 있는 적절한 기량과 경험이 있는 변호사에 지원을 요청하기 위한 비용도 늘어날 것입니다.
> 합의와 판결에 따라 배상금의 지불이 요구될지도 모릅니다. 모처럼에 대한 제품의 출하를 금지되어 버릴 것 같은 타격을받을 가능성도 배제 할 수 없습니다. 극단적인 경우, 제품 출하금지 되어버리는 타격을 받을 가능성도 배제할 수 없습니다.

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

> ## OSS 커뮤니티와의 좋은 관계 구축
> 소송을 받게 되는 사태를 피하려면, 배포하는 소프트웨어에 있는 OSS를 정확하게 파악하고 라이선스에 요구되는 사항을 우선 제대로 실행하는 것이 기본입니다. 이 외에도, OSS 개발자 커뮤니티에 기여하며 커뮤니티와 좋은 관계를 구축하는 것도 효과적인 방법입니다.
> OSS의 개발을 진행하는 커뮤니티가 왜 OSS 라이선스를 선택했는지, 그 배경에는 커뮤니티의 어떤 생각이 담겨 있는지를 이해하는 것이 단지 라이선스 문서의 표면적 의미에서 얻을 수 있는 내용보다 더 많은 지식과 견문을 얻을 수 있을 것입니다. 개발자 커뮤니티와의 상호신뢰관계는 다른 것으로도 대체하기 힘든 중요한 가치 중 하나가 될 것입니다.
> OSS 개발자 커뮤니티와의 신뢰관계를 구축할 수 있다면, 여러분은 자신이 가지고 있는 OSS에 대한 개선사항에 대해 커뮤니티에서 함께 검토해 줄 가능성도 생길 수 있습니다. 이외에도 커뮤니티와 교류를 가진 개발자는 관련 기술 분야에 대해 세계 최고 수준의 기량을 가진 사람과의 커뮤니케이션이 가능합니다. 같은 뜻을 가진 개발자들끼리의 스터디를 통한 기량 향상 기회도 있습니다. 커뮤니티와의 연계는 기업도 인재육성의 관점에서도 놓칠 수없는 것입니다.
> 오늘날의 소프트웨어 시스템은 대형화 고도화되어 복잡하게 얽혀 있습니다. 따라서 아무리 제대로 OSS에 대한 대응하더라도 실수를 할 가능성은 존재합니다. 이 상황에 대해 OSS 개발자 커뮤니티에 일정한 이해를 표시하는 경우도 생길 수 있습니다. 당신이 커뮤니티 사람들로부터 신뢰를 얻고있다면 만일 실수가 발생해도 먼저 그 사실을 커뮤니티에서 자비롭게 지적해 줄지도 모릅니다.

## Contributing to OSS communities

There are many ways to contribute to OSS communities: proposing bugfixes and new features, translating documents, providing places and forums where community members can communicate, and sponsoring and participating in projects and trade associations that support OSS, such as the Linux Foundation.

## コミュニティーに貢献する

コミュニティーに貢献する方法は多彩です。OSS の障害を対 応したり機能追加をするような技術的な貢献は誰でも思いつく で しょう 。 ほ か に も コ ミ ュ ニ テ ィ ー の 持 つド キ ュ メ ント を 翻 訳 す る、コミュニティーの人々が互いに出会える場所をしつらえるな ども貢献として受け取っていただけるでしょう。また The Linux Foundation など OSS コミュニティーと関係が深い団体に参加 することも選択肢のひとつとして挙げることができます。

> ## 커뮤니티에 기여하는 일
> 커뮤니티에 기여하는 방법은 다양합니다. OSS의 버그 수정이나 기능을 추가하는 행위를 통해 누구나 생각할 수 있는 기술적인 기여를 할수도 있습니다. 이외에도 커뮤니티에 있는 문서를 번역하거나 커뮤니티의 사람들이 서로 만날 장소를 제공하는 방법도 기여로 인정할 것입니다. 또한 The Linux Foundation 등의 OSS 커뮤니티와 관계가 깊은 단체에 참여하는 방법도 대안 중 하나로 꼽을 수 있습니다.
