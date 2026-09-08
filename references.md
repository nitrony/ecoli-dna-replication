---
date: 2026-09-08
version: 7
tags: [DNA-replication, references]
---

# 科学的な解説と参考文献

[アニメーションへ](index.html)

## 科学的な描写の判断

### 分子表面と概要の模式化

各タンパク質の単量体を、緩やかな凹凸を持つ一続きの表面として描く。
DnaAではDomain IIIとIVをつなぎ、柔軟なDomain IIを介してDomain Iを配置する。[20]
Abe et al. (2007) はDomain IIの柔軟性と、Domain Iの二量体化界面およびDnaBロードへの関与を調べた。
v7ではDomain IIを緩い曲線で描き、v6で示した揺れとDomain Iの反復接触は保留する。
リンカー長やドメインの向きは模式的な配置であり、測定座標ではない。
ドメインの色分けは機能の説明であり、別々のサブユニットを表さない。
原子球、PDB座標、cryo-EM密度、分子動力学計算の再現ではない。

一方、IHFのαβ、DnaBの6量体、装着複合体中の6分子のDnaC、SSBの4量体、βクランプの2量体、Topo IVのParC₂ParE₂は複数の単量体として示す。[3,21,22,25,29]
DnaGの模式形状を1分子示す場面でも、DnaBへの占有数が全条件で1に固定されるとはしない。
タンパク質の大きさとリンカー長は、役割を読み取るために調整している。

冒頭の環状DNAは、複製フォークの進行を説明するための概形である。
円形の描写だけで、開始鋳型の超らせん状態を定量的に指定しない。
両方向のフォークが進んだ後も同じ娘DNAを追い、左右へ移動して残る短い絡みを解くまでを示す。[13,19]
概要のタンパク質は脱連環因子の総称として描き、特定酵素のゲート構造を簡略化する。
後半の4反応で、基質と酵素ごとの切断と鎖通過を説明する。
閉環カテナンが全細胞で同じ量だけ蓄積するという意味ではない。
後半では複製完了の前後に存在する別の基質を比較するため、直前に封鎖された同一分子へgapを作り直す物語にはしない。

## oriC上のDnaAとIHF

### 採用した11分子モデル

Shimizu et al. (2016) のIHFを含む開始複合体モデルを描画の基準にした。[12]
DNA結合DnaAは左5分子、中央R2の1分子、右5分子の計11分子である。
これは実験と計算を組み合わせた構造モデルの分子数であり、全条件におけるoriCの固定総占有数を示さない。

| 領域 | DnaAの結合先 | 分子数 |
|---|---|---|
| 左 | R1、R5M、τ2、I1、I2 | 5 |
| 中央 | R2 | 1 |
| 右 | C3、C2、I3、C1、R4 | 5 |
| IHFと重なるτ1 | IHF結合モデルではDnaAを配置しない | 0 |

Sakiyama et al. (2017) の12個という値はτ1を含むDnaA boxの数であり、IHF結合後の同時占有数と区別する。[18]
同論文ではIHFがτ1の9 bp中7 bpを覆う。
添付されたOzaki et al. (2012) の図に含まれる旧表記R3/R5と、後年のサイト名の整理も区別した。[17,18]
DNA非結合DnaAによる橋渡しは原著で可能性として議論されているが、追加する分子数は確定していないため、11分子に足していない。[12]

### 協同的な集合からDUE融解へ

R1とR4は高親和性、R2は中程度の親和性として先行占有を示す。[18]
左側ではR5M結合ATP-DnaAが集合を主導し、R1結合DnaAが補助する。
右側ではR4から内向きの協同的集合を表す。[11,18]
認識とらせん集合の初期にはR1を離しておき、R5M、τ2、I1、I2のDomain IIIを密に並べる。
IHFがDNAを屈曲させるとR1が近づき、左側サブ複合体の接触を示す。

この段階化は最終モデルと機能実験を基にした説明用の補間であり、各中間状態の原子構造や結合時刻が確定したことを意味しない。
Domain IIIのArg fingerや左右の機能差の根拠を用いる一方、R2を含む全oriCを一様ならせんにしていない。[9,11,12,17]
Erzberger et al. (2006) の右巻きAAA+集合体はAquifex aeolicus由来であり、大腸菌oriC全体の直接構造とは区別する。[10]

IHFの屈曲後、DUEを左側サブ複合体へ近づけ、Domain IIIがT-rich ssDUEを保持する。[1,12,18]
R1とR5MのDnaAによるssDUE結合には機能実験の根拠がある。[18]
v7では開いた鎖の配向を保持して、局所的に左側Domain IIIへ触れさせる。
特定の4分子を順に巡る経路は描かず、接触位置を原子座標として確定した図ではない。
DUE融解は塩基対の解離で、糖リン酸骨格の切断ではない。
本図の環状oriCでDnaA依存的に開始する条件として、負のスーパーコイルが必要である旨を開始紹介の小字に示す。[1]
IHFのDNA屈曲自体に負のスーパーコイルが必須とはしていない。[21]
特定条件の線状oriCでもDUE融解が報告されており、基質と条件を限定して扱う。[18]

## ヘリカーゼ装着から伸長へ

複数のDnaA Domain IがDnaBを係留し、Domain IIIの接触が装着を助ける。[2,5,20]
特定のDnaA boxのDomain Iだけに左または右のDnaBを担当させる証拠は不足している。
Tsuruda et al. (2026) は左右のサブ複合体による異なる親鎖への装着を示すモデルの根拠とした。[5]
v6では、もう一方のDnaB-DnaCが周囲から到着する表示へ変更した。
特定の右側Domain Iからの移動軌跡を省略したもので、Domain Iの係留作用が不要という意味ではない。
DnaB-DnaCの装着からDnaG到着までの一本鎖領域は短く保ち、伸長前にフォークが大きく進んだような描写を避ける。
DnaGとの相互作用とprimingによるDnaC離脱は、ATPase状態変化を含む代表的な経路として示す。[3,4]

伸長の章扉ではPol IIIをαεθ core、β₂クランプ、(τ/γ)₃δδ′χψクランプローダーに分けて紹介する。[6,24,25]
αはDNA合成、εは校正、θはεの安定化に寄与する。[24]
τはPol IIIとDnaBの連結にも関わる。
伸長場面の2つのcoreはリーディング鎖とラギング鎖の機能配置を示し、全条件のcore数やτ/γ比率を固定しない。

右向きのフォークのラギング鎖鋳型は左5′、フォーク側3′、リーディング鎖鋳型は左3′、フォーク側5′とする。
両方の新生鎖が5′から3′へ伸び、各RNAプライマーを新生断片の5′側に置く。[6,7]
ラギング鎖の極性を読みやすくするため、DNAを広げた模式図を採用した。
実際のトロンボーンループは同場面の補足として説明し、独立したループ動画は削除した。
詳しいアニメーションは[30]の動画を参照する。

SSBは露出した一本鎖を保護し、再会合や二次構造を抑える。[22]
DnaG近傍の局所再配置と、Pol IIIが鋳型を二本鎖へ変える過程に伴うSSBの離脱と再利用を示す。
DnaG到着の瞬間に全SSBが一斉離脱する反応にはしていない。
Spenkelink et al. (2019) は再利用と交換を支持するが、SSBの接触位置や局所の揺らぎまで本動画と同じ運動として測定したわけではない。

## RNAプライマー除去とニック封鎖

| 表示経路 | RNAの処理 | DNAでの充填 | 最後の封鎖 |
|---|---|---|---|
| Pol I主導 | Pol Iのstrand displacementと5′ nucleaseがRNAを処理 | 同じPol Iが新生鎖を伸ばす | LigA |
| RNase HIが補助 | RNase HIがRNAを部分分解し、gapと接合部側の短い残存RNAを生じる | Pol Iが残存RNAを処理してgapを埋める | LigA |

この比較はRNase HIの寄与とPol Iの役割を分けて示すためのもので、2経路の頻度が等しいとはしない。[7,8,23]
RNase HIが必ず先行するとも、接合部の最後のrNMPまで無条件に除去するとも説明しない。
残存RNAの描画長は模式値である。

**ニック**は塩基を失わずに片側骨格の共有結合が1か所途切れた状態、**ギャップ**は片側のヌクレオチドが欠けて相補鎖が露出した状態として区別する。
RNAをDNAへ置換した後の3′-OHと5′-phosphateをLigAが封鎖する。[8]
末端数塩基の揺れとニック幅は視認のための強調であり、恒常的な数塩基の解離や実測された揺らぎを示さない。

## 脱連環の基質と4反応

### 基質S1-S4

| 基質 | 描く特徴 | 処理後に残りうるもの |
|---|---|---|
| S1 完全閉環dsカテナン | 2本の骨格が連続した娘二本鎖DNA環同士の連環 | Topo IVの反応後は分離した閉環DNA |
| S2 gapを含むカテナン | 欠損側と、その相補側に露出した連続ssDNA | 元からあるgapやnick |
| S3 precatenaneを持つ複製中間体 | 娘DNAの絡み、複製フォーク、未複製親duplex | 絡みが減っても未複製部を残すLRI |
| S4 収束直前のLRI | 近接したフォークの間の短い未複製部とss領域 | RecQ/Topo III処理後にも残るgap |

S3とS4は排他的な自然分類ではなく、注目する特徴の違いである。[14,27]
4反応を全DNAが順番に通る経路としては示さない。
S1の閉環産物へ、次場面のS2用のgapを新たに作ることもない。

### 触媒ゲートと生成物

| 反応系 | 採用した代表基質 | 切断と通過 | 生成物と残る工程 |
|---|---|---|---|
| Topo IV | S1 | ParC側でG duplexの両鎖を一時切断。ParE側でATPを利用して捕捉したT duplexを通す | Topo IVがGを再結合し、閉環DNAを分離。新たなgap充填は不要 |
| Topo III単独 | S2 | 既存gapの相補側に露出したss Gを切断。別環のds Tを通す | Gを再結合して分離。既存gapの充填とnick封鎖は別工程 |
| RecQ + Topo III + SSB | S4 | RecQがATP依存に残部をほどき、SSBがssDNAを保護。Topo IIIのss Gゲートをss Tが通る | 分離したgapped daughter DNA。DNA合成とnick封鎖が残る |
| Topo III + DnaX | S2とS3 | DNAの切断、通過、再結合はTopo IIIが担い、DnaXが反応を促進 | S2はgapを残す分離DNA。S3は未複製部を残すLRI |

Topo IIIが切るGは、既存gapの**欠損側ではなく相補側の連続一本鎖**である。[26]
酵素が切断端を保持し、T通過後はTopo III自身が再結合する。[15,16]
5′側を触媒Tyrとの共有結合で保持するType IA反応を、自由断片の飛散やLigAによる触媒切断の修復として示さない。
Topo IIIが作るGゲートは一本鎖だが、そこを通るTは基質に応じて一本鎖または二本鎖となる。

Topo IVのParC₂ParE₂を4つの滑らかな単量体として描く。[29]
Gの両鎖を開き、Tの両鎖を一緒に通してからGを再結合する。
Topo IVはS2やプレカテナンにも作用し得るため、表の代表基質を酵素の全基質範囲とはしない。[26,27]
大腸菌の主要な脱連環因子としてのTopo IVと、条件に応じたTopBの寄与を区別する。[19,28]

RecQは結合した鎖上を3′から5′へ進むヘリカーゼであり、DNA骨格を切る酵素ではない。
RecQで塩基対をほどいた後にも親鎖間の連環を残し、Topo IIIがそれを解く段階へつなぐ。[14]
RecQとTopo IIIの順番は説明用の段階化で、原著で示される機能的な協働を固定された直接相互作用二量体の構造とはしない。

DnaX全体とTopo IIIの物理的な相互作用、およびτの促進寄与はLee et al. (2019) に基づく。[27]
単離τとの相互作用は弱く、原子レベルのドッキング界面は確定していない。
DnaXは切断酵素でも、未複製duplexをほどく因子でもない。
βクランプ装着のATP依存性と、この脱連環促進実験でATP添加の有意効果がなかったことを分けて扱う。

## 実験条件と解釈の範囲

| 原著と確認箇所 | 条件または数値 | 本動画での扱い |
|---|---|---|
| Seol et al. (2013), Results/Fig. 5 [26] | 約5 kb DNAの37 nt gap。ResultsではTopo III 10 nM、Topo IV 2 nM。Topo IV条件にATP 1 mM。1回転条件のunlinking rateは5.9 ± 0.7と5.1 ± 0.5 s⁻¹、平均 ± SEM | 酵素濃度と基質が異なるため普遍的なkcat順位や映像速度へ換算しない。MethodsのTopo III 5 nM記載との相違も残す |
| Seol et al. (2013), Results [26] | 同条件のintact/multi-nicked基質ではTopo IIIの脱連環を認めず、gap基質で活性 | 利用可能なssDNA領域を示す。nickだけで常に十分とも、全条件でnick基質に絶対反応しないとも一般化しない |
| Suski and Marians (2008), Fig. 2/4/6/7 [14] | 再構成LRIの未複製部は約130 bp。代表条件RecQ 5 nM、Topo III 8 nM、SSB 400 nM。生成物はgapped form II | この条件ではTopo IVがTopo IIIを置換しない。130 bpを普遍的な終結距離にしない |
| Lee et al. (2019), Fig. 3 [27] | Topo III 1.2 nM、追加因子40 nM、10分。ATPなしのform II産物は15.8 ± 0.9%からDnaX追加で32.1 ± 1.1%。ATPありでは13.3 ± 1.3%と30.9 ± 0.6%、平均 ± SD、n=3 | 同じ測定時点の産物割合。ATP添加の有意効果なし。アニメーションを2倍速にする根拠にはしない |
| Lee et al. (2019), Fig. 3F [27] | プレカテナンから未複製領域約1 kbpを残すLRIを生成。τが主要な促進寄与 | Suski 2008の130 bp LRIと別の基質。脱連環だけで未複製部を消さない |
| Su’etsugu et al. (2017), Results/Fig. 2B [13] | 8 kb oriC環状DNA 150 pM、30°C、1時間。Topo IV系とTopo III/RecQ系の順で、総DNA合成は入力比最大約80倍と100倍、supercoiled産物は約7倍と25倍 | 入力DNAのヌクレオチド量で規格化した多段階RCRの産物収量。濃度µg/ml、脱連環速度、単独酵素の強さの順位と区別する |

RCRの数値は原著本文とFigure 2Bの説明を再確認した。
総DNA合成はdNTP取り込みから計算し、supercoiled産物はゲルの割合を使って入力鋳型量で規格化している。[13]
Topo III単独でもRCR産物ができ、RecQはそれを促進する一方、単離LRIの解消条件とは必要因子が異なる。[13,14]

岡崎フラグメント成熟では、Ogawa and Okazaki (1984) のAbstractでRNase HとPol Iの変異体解析、Kitani et al. (1985) のAbstractで約10-12 ntのRNAプライマーを確認した。[7,23]
Botto et al. (2023) はAbstractと公開Extended Data説明を確認した範囲で、Pol Iのstrand displacement、5′ nuclease、LigAへの受け渡しに用いた。[8]
未取得の本文図について番号を推測していない。

## RCRと最後のDNA成熟

RCRはSu’etsugu et al. (2017) の**replication-cycle reaction**を指す。[13]
oriCからのシータ型複製を反復する再構成系であり、rolling-circle replicationの略として用いていない。
Tus-terは同論文で追加検討された構成であり、ここで扱うRCRの絶対条件とはしない。

gapを残す脱連環産物には必要なDNA合成とLigAによるnick封鎖を続け、閉環後の負の超らせん化をGyraseとして示す。[8,13,19]
S1からTopo IVによって生じた閉環DNAへ不要なgap充填を追加する意味ではない。
DNA合成、成熟、脱連環、超らせん化は実際には時間的に重なり得るため、表示した順番を全細胞で固定された順番とはしない。

## 模式化と省略した内容

- DNA長、分子間距離、曲率、超らせん形状、カメラ移動、反応時間は説明用の値である。
- DNAの骨格を連続して描き、融解と酵素による一時切断を分ける。画面上の交差だけで骨格の切断や連結を意味しない。
- ゲート通過はG/Tの対応を保った3次元の模式幾何として実装する。切断前後のDNAや通過速度を原子分解能で再現したとはしない。
- oriCの配列間隔、全サイトの占有率、HU、Fis、DiaA、SeqA、DARS、datA、開始時期の制御は網羅しない。
- 伸長の拡大は右向きの1フォークであり、もう一方の複製フォークの消失を意味しない。
- 校正、損傷回避、染色体終結領域の全構成、XerCD/difの二量体解消、再開始制御の詳細は省略する。
- 原著図と参考動画を転載せず、論文の機構説明を基に独自の模式形状を作成する。

## 参考文献

番号はHTML・動画と共通。全著者を掲載し、DOIと書誌情報は2026-09-08に照合した。

- **[1]** Ozaki S, Katayama T, Nucleic Acids Research, 2012, [Highly organized DnaA-oriC complexes recruit the single-stranded DNA for replication initiation](https://pubmed.ncbi.nlm.nih.gov/22053082/). 40(4):1648-1665. DOI: [10.1093/nar/gkr832](https://doi.org/10.1093/nar/gkr832)
  - DnaAの機能領域、IHFによる屈曲、DUEの融解とssDUE recruitment。
- **[2]** Hayashi C, Miyazaki E, Ozaki S, Abe Y, Katayama T, Journal of Biological Chemistry, 2020, [DnaB helicase is recruited to the replication initiation complex via binding of DnaA domain I to the lateral surface of the DnaB N-terminal domain](https://pubmed.ncbi.nlm.nih.gov/32540966/). 295(32):11131-11143. DOI: [10.1074/jbc.RA120.014235](https://doi.org/10.1074/jbc.RA120.014235)
  - DnaA Domain IによるDnaBの係留とDomain IIIによるロード補助。
- **[3]** Arias-Palomo E, Puri N, O'Shea Murray VL, Yan Q, Berger JM, Molecular Cell, 2019, [Physical Basis for the Loading of a Bacterial Replicative Helicase onto DNA](https://pubmed.ncbi.nlm.nih.gov/30797687/). 74(1):173-184.e4. DOI: [10.1016/j.molcel.2019.01.023](https://doi.org/10.1016/j.molcel.2019.01.023)
  - DnaCによるDnaBリングの開閉と一本鎖DNAの取り込み。
- **[4]** Makowska-Grzyska M, Kaguni JM, Molecular Cell, 2010, [Primase directs the release of DnaC from DnaB](https://pubmed.ncbi.nlm.nih.gov/20129058/). 37(1):90-101. DOI: [10.1016/j.molcel.2009.12.031](https://doi.org/10.1016/j.molcel.2009.12.031)
  - DnaGとの相互作用およびプライマー形成に伴うDnaCの離脱。
- **[5]** Tsuruda T, Yoshida R, Hayashi C, Kasho K, Ozaki S, Katayama T, Nucleic Acids Research, 2026, [Dynamic DnaA-DnaB interactions at oriC coordinate the loading and coupled translocation of two DnaB helicases for bidirectional replication](https://pubmed.ncbi.nlm.nih.gov/41558826/). 54(2):gkaf1474. DOI: [10.1093/nar/gkaf1474](https://doi.org/10.1093/nar/gkaf1474)
  - Domain IIIを介した鎖特異的なロードと2個のDnaBの協調に関するモデル。
- **[6]** Yao NY, Georgescu RE, Finkelstein J, O'Donnell ME, Proceedings of the National Academy of Sciences of the United States of America, 2009, [Single-molecule analysis reveals that the lagging strand increases replisome processivity but slows replication fork progression](https://pubmed.ncbi.nlm.nih.gov/19666586/). 106(32):13236-13241. DOI: [10.1073/pnas.0906157106](https://doi.org/10.1073/pnas.0906157106)
  - Pol III、βクランプ、DnaGによる複製とトロンボーンモデルを支持する単分子実験。
- **[7]** Kitani T, Yoda K, Ogawa T, Okazaki T, Journal of Molecular Biology, 1985, [Evidence that discontinuous DNA replication in Escherichia coli is primed by approximately 10 to 12 residues of RNA starting with a purine](https://pubmed.ncbi.nlm.nih.gov/2411935/). 184(1):45-52. DOI: [10.1016/0022-2836(85)90042-7](https://doi.org/10.1016/0022-2836(85)90042-7)
  - 大腸菌のRNAプライマーとRNase HおよびPol Iの寄与。
- **[8]** Botto MM, Borsellini A, Lamers MH, Nature Structural & Molecular Biology, 2023, [A four-point molecular handover during Okazaki maturation](https://pubmed.ncbi.nlm.nih.gov/37620586/). 30(10):1505-1515. DOI: [10.1038/s41594-023-01071-y](https://doi.org/10.1038/s41594-023-01071-y)
  - Pol IIIからPol Iへの移行、RNA置換と5′ nuclease活性、DNA ligaseへの受け渡し。
- **[9]** Kawakami H, Keyamura K, Katayama T, Journal of Biological Chemistry, 2005, [Formation of an ATP-DnaA-specific initiation complex requires DnaA Arginine 285, a conserved motif in the AAA+ protein family](https://pubmed.ncbi.nlm.nih.gov/15901724/). 280(29):27420-27430. DOI: [10.1074/jbc.M502764200](https://doi.org/10.1074/jbc.M502764200)
  - 隣のDnaAに結合したATPを認識するArg285と開始複合体の機能。
- **[10]** Erzberger JP, Mott ML, Berger JM, Nature Structural & Molecular Biology, 2006, [Structural basis for ATP-dependent DnaA assembly and replication-origin remodeling](https://pubmed.ncbi.nlm.nih.gov/16829961/). 13(8):676-683. DOI: [10.1038/nsmb1115](https://doi.org/10.1038/nsmb1115)
  - Aquifex aeolicus DnaAの右巻きAAA+集合体。大腸菌全oriCの実測構造ではない。
- **[11]** Noguchi Y, Sakiyama Y, Kawakami H, Katayama T, Journal of Biological Chemistry, 2015, [The Arg Fingers of Key DnaA Protomers Are Oriented Inward within the Replication Origin oriC and Stimulate DnaA Subcomplexes in the Initiation Complex](https://pubmed.ncbi.nlm.nih.gov/26126826/). 290(33):20295-20312. DOI: [10.1074/jbc.M115.662601](https://doi.org/10.1074/jbc.M115.662601)
  - R1とR4に結合したDnaAから内側へ向かう協同的集合と左右のサブ複合体。
- **[12]** Shimizu M, Noguchi Y, Sakiyama Y, Kawakami H, Katayama T, Takada S, Proceedings of the National Academy of Sciences of the United States of America, 2016, [Near-atomic structural model for bacterial DNA replication initiation complex and its functional insights](https://pubmed.ncbi.nlm.nih.gov/27911788/). 113(50):E8021-E8030. DOI: [10.1073/pnas.1609649113](https://doi.org/10.1073/pnas.1609649113)
  - 大腸菌oriCの左右のDnaAらせんと中央R2のモデル。DNA非結合DnaAによる橋渡しはDiscussionで挙げられた可能性。
- **[13]** Su'etsugu M, Takada H, Katayama T, Tsujimoto H, Nucleic Acids Research, 2017, [Exponential propagation of large circular DNA by reconstitution of a chromosome-replication cycle](https://pubmed.ncbi.nlm.nih.gov/29036468/). 45(20):11525-11534. DOI: [10.1093/nar/gkx822](https://doi.org/10.1093/nar/gkx822)
  - RCRの再構成、Topo IVとTopo III-RecQによる娘DNA分離、Gyraseによる超らせん化。Tus-terは追加構成。
- **[14]** Suski C, Marians KJ, Molecular Cell, 2008, [Resolution of converging replication forks by RecQ and topoisomerase III](https://pubmed.ncbi.nlm.nih.gov/18570879/). 30(6):779-789. DOI: [10.1016/j.molcel.2008.04.020](https://doi.org/10.1016/j.molcel.2008.04.020)
  - RecQが未複製DNAをほどき、Topo IIIが一本鎖を含む終結中間体を解消する反応。
- **[15]** Mills M, Tse-Dinh YC, Neuman KC, Nature Structural & Molecular Biology, 2018, [Direct observation of topoisomerase IA gate dynamics](https://pubmed.ncbi.nlm.nih.gov/30478267/). 25(12):1111-1118. DOI: [10.1038/s41594-018-0158-x](https://doi.org/10.1038/s41594-018-0158-x)
  - 大腸菌Topo IとTopo IIIの一本鎖DNAゲート開閉の単分子観測。鎖通過は機構モデルとして表示。
- **[16]** Changela A, DiGate RJ, Mondragón A, Nature, 2001, [Crystal structure of a complex of a type IA DNA topoisomerase with a single-stranded DNA molecule](https://pubmed.ncbi.nlm.nih.gov/11429611/). 411(6841):1077-1081. DOI: [10.1038/35082615](https://doi.org/10.1038/35082615)
  - 大腸菌Topo IIIのssDNA認識と、5′-phosphotyrosine中間体を経るType IA反応の根拠。
- **[17]** Ozaki S, Noguchi Y, Hayashi Y, Miyazaki E, Katayama T, Journal of Biological Chemistry, 2012, [Differentiation of the DnaA-oriC subcomplex for DNA unwinding in a replication initiation complex](https://pubmed.ncbi.nlm.nih.gov/22942281/). 287(44):37458-37471. DOI: [10.1074/jbc.M112.372052](https://doi.org/10.1074/jbc.M112.372052)
  - 添付図の原著。左右のDnaAサブ複合体と、左側のDomain III界面におけるArg227・Leu290の役割。
- **[18]** Sakiyama Y, Kasho K, Noguchi Y, Kawakami H, Katayama T, Nucleic Acids Research, 2017, [Regulatory dynamics in the ternary DnaA complex for initiation of chromosomal replication in Escherichia coli](https://pubmed.ncbi.nlm.nih.gov/29040689/). 45(21):12354-12373. DOI: [10.1093/nar/gkx914](https://doi.org/10.1093/nar/gkx914)
  - 12個の結合サイトとIHFによるτ1占有の抑制、R5Mによる左側集合の促進、R1・R5MによるssDUE保持。
- **[19]** Zechiedrich EL, Cozzarelli NR, Genes & Development, 1995, [Roles of topoisomerase IV and DNA gyrase in DNA unlinking during replication in Escherichia coli](https://pubmed.ncbi.nlm.nih.gov/7590259/). 9(22):2859-2869. DOI: [10.1101/gad.9.22.2859](https://doi.org/10.1101/gad.9.22.2859)
  - 複製に伴うDNA連環の解消におけるTopo IVの主要な役割。Gyraseによる超らせん化と機能を分けて示す。
- **[20]** Abe Y, Jo T, Matsuda Y, Matsunaga C, Katayama T, Ueda T, Journal of Biological Chemistry, 2007, [Structure and function of DnaA N-terminal domains: specific sites and mechanisms in inter-DnaA interaction and in DnaB helicase loading on oriC](https://pubmed.ncbi.nlm.nih.gov/17420252/). 282(24):17816-17827. DOI: [10.1074/jbc.M701841200](https://doi.org/10.1074/jbc.M701841200)
  - NMRで確認された構造化したDomain Iと柔軟なDomain II。DnaAを連続した1分子として、柔軟なリンカーを含めて描く根拠。
- **[21]** Rice PA, Yang S, Mizuuchi K, Nash HA, Cell, 1996, [Crystal structure of an IHF-DNA complex: a protein-induced DNA U-turn](https://pubmed.ncbi.nlm.nih.gov/8980235/). 87(7):1295-1306. DOI: [10.1016/S0092-8674(00)81824-3](https://doi.org/10.1016/S0092-8674(00)81824-3)
  - IHFのαβ異種二量体と強いDNA屈曲の構造的根拠。解析DNAをoriC全体の実測構造として扱わない。
- **[22]** Spenkelink LM, Lewis JS, Jergic S, Xu ZQ, Robinson A, Dixon NE, van Oijen AM, Nucleic Acids Research, 2019, [Recycling of single-stranded DNA-binding protein by the bacterial replisome](https://pubmed.ncbi.nlm.nih.gov/30767010/). 47(8):4111-4123. DOI: [10.1093/nar/gkz090](https://doi.org/10.1093/nar/gkz090)
  - SSB四量体による一本鎖保護と、合成に伴う内部再利用・外部交換。DnaG到着時に全SSBが一斉離脱する描画を避ける根拠。
- **[23]** Ogawa T, Okazaki T, Molecular and General Genetics, 1984, [Function of RNase H in DNA replication revealed by RNase H defective mutants of Escherichia coli](https://pubmed.ncbi.nlm.nih.gov/6319961/). 193(2):231-237. DOI: [10.1007/BF00330673](https://doi.org/10.1007/BF00330673)
  - RNase HとPol IのRNAプライマー除去への寄与。RNase HIによる部分除去後にも残存RNAの処理が必要であり、全断片が同じ直列経路を通るとはしない。
- **[24]** Jergic S, Ozawa K, Williams NK, Su XC, Scott DD, Hamdan SM, Crowther JA, Otting G, Dixon NE, Nucleic Acids Research, 2007, [The unstructured C-terminus of the τ subunit of Escherichia coli DNA polymerase III holoenzyme is the site of interaction with the α subunit](https://pubmed.ncbi.nlm.nih.gov/17355988/). 35(9):2813-2824. DOI: [10.1093/nar/gkm079](https://doi.org/10.1093/nar/gkm079)
  - Pol III coreのα・ε・θの役割、τとαの連結、柔軟な領域を含むτの配置。直線の棒ではなく曲がるリンカーとして示す根拠。
- **[25]** Dohrmann PR, Correa R, Frisch RL, Rosenberg SM, McHenry CS, Nucleic Acids Research, 2016, [The DNA polymerase III holoenzyme contains γ and is not a trimeric polymerase](https://pubmed.ncbi.nlm.nih.gov/26786318/). 44(3):1285-1297. DOI: [10.1093/nar/gkv1510](https://doi.org/10.1093/nar/gkv1510)
  - γを含むPol III holoenzymeの組成解析。τ3を使う再構成系と区別し、構成紹介では(τ/γ)3δδ′χψと表記して固定比率を断定しない。
- **[26]** Seol Y, Hardin AH, Strub MP, Charvin G, Neuman KC, Nucleic Acids Research, 2013, [Comparison of DNA decatenation by Escherichia coli topoisomerase IV and topoisomerase III: implications for non-equilibrium topology simplification](https://pubmed.ncbi.nlm.nih.gov/23460205/). 41(8):4640-4649. DOI: [10.1093/nar/gkt136](https://doi.org/10.1093/nar/gkt136)
  - 利用可能な一本鎖領域を含む基質でのTopo III脱連環とduplex T通過。gapとnickの区別、異なる条件の速度比較を一般化しないための根拠。
- **[27]** Lee CM, Wang G, Pertsinidis A, Marians KJ, Journal of Bacteriology, 2019, [Topoisomerase III Acts at the Replication Fork To Remove Precatenanes](https://pubmed.ncbi.nlm.nih.gov/30617245/). 201(7):e00563-18. DOI: [10.1128/JB.00563-18](https://doi.org/10.1128/JB.00563-18)
  - DnaX・τによるTopo III反応の促進、catenaneとprecatenaneの処理後に残るDNA状態。DnaXを切断酵素や既知の原子構造界面として描かない。
- **[28]** Perez-Cheeks BA, Lee C, Hayama R, Marians KJ, Molecular Microbiology, 2012, [A role for topoisomerase III in Escherichia coli chromosome segregation](https://pubmed.ncbi.nlm.nih.gov/23066834/). 86(4):1007-1022. DOI: [10.1111/mmi.12039](https://doi.org/10.1111/mmi.12039)
  - Topo IVの機能低下背景におけるTopBの遺伝学的役割。過剰発現による救済と通常の細胞内での寄与を区別する根拠。
- **[29]** Bigot S, Marians KJ, Nucleic Acids Research, 2010, [DNA chirality-dependent stimulation of topoisomerase IV activity by the C-terminal AAA+ domain of FtsK](https://pubmed.ncbi.nlm.nih.gov/20081205/). 38(9):3031-3040. DOI: [10.1093/nar/gkp1243](https://doi.org/10.1093/nar/gkp1243)
  - Discussionで説明されたTopo IVのG/Tセグメント、ParC2ParE2、ATP依存のゲートサイクル。FtsKを新たな反応系として追加する意図ではない。
- **[30]** WEHImovies, YouTube, 2017, [DNA Replication 2010](https://www.youtube.com/watch?v=6j8CV3droDw) [動画]. 閲覧日: 2026-09-08.
  - トロンボーンループとリーディング鎖・ラギング鎖の協調を説明する参考アニメーション。分子機構の実験的根拠は原著論文を参照。

