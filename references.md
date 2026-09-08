---
date: 2026-09-08
version: 3
tags: [DNA-replication, references]
---

# 科学的な解説と参考文献

[アニメーションへ](index.html)

## 科学的な描写の判断

### カテナンと負のスーパーコイル

冒頭では、負のスーパーコイルを持つ閉じた環状DNAを、形を広げながらシータ型複製の表示へ移す。
形を広げる操作は全DNAが生化学的に弛緩するという意味ではなく、フォークの進行を読みやすくするための表示である。
複製した娘二本鎖DNAが閉じた環として連環した**カテナン**を、1組の連環に単純化して示す。[13,19]

Topo IVは二本鎖を一時切断し、別の二本鎖を通して再結合する。
アニメーションでも一方の環の両鎖にゲートを開き、そこを他方のDNAが通過してから閉じる。
Gyraseによる負の超らせん化を後段に置く。[13,19]
これらの過程は実際には時期が重なりうるため、映像の段階順を全細胞に共通の直列過程とはしない。
後半に示すTopB反応は一本鎖領域を持つ中間体が対象であり、冒頭の閉じた二本鎖カテナンにそのまま適用しない。

### DnaAの分子数と結合サイト

描画の基準は、Shimizu et al. (2016) のIHFを含む大腸菌開始複合体モデルとする。[12]
同モデルのDNA結合DnaAは左5分子、中央R2の1分子、右5分子の計11分子である。
これは実験と計算を組み合わせた構造モデルの分子数であり、全条件におけるoriCの固定的な総占有数という意味ではない。

| 領域 | 描画するDnaAの結合先 | 分子数 |
|---|---|---|
| 左 | R1、R5M、τ2、I1、I2 | 5 |
| 中央 | R2 | 1 |
| 右 | C3、C2、I3、C1、R4 | 5 |
| IHFと重なるτ1 | このIHF結合モデルではDnaAを置かない | 0 |

Sakiyama et al. (2017) はDORに12個のDnaA boxを記載している。[18]
この数はτ1を含むサイト数であり、IHF結合後の同時占有数と区別する。
同論文のfootprintではIHFがτ1の9 bp中7 bpを覆い、DnaAによるτ1占有を抑える。
添付された2012年の図は当時のR3やR5を含む表記であるため、描画のサイト名と分子数には2016・2017年の整理を採用した。[12,17,18]
DNA非結合DnaAの追加分子数は確定していないため、v2で半透明に示していた橋渡し分子はv3に加えない。

### 協同的な集合とIHFの屈曲

R1・R4は高親和性、R2は中程度の親和性として表示する。[18]
これらの先行占有の後に、間の低親和性サイトにDnaAを並べる。
左側ではR5Mに結合したATP-DnaAが集合を主導し、R1に結合したDnaAが補助することが示されている。[18]
右側ではR4から内向きへの協同的集合を表す。[11]
動画中の結合順序・時刻は、占有が増える過程を説明するための補間である。

各サブ複合体内のDomain III同士を直接接する大きさにし、ずれを伴う界面によるらせんを示す。[9,12,17]
Arg227とLeu290に関する左側の機能差を示した添付図の原著を、局所の配置を考える根拠として追加した。[17]
R2を含めて全oriCを一続きの均一ならせんとすることは避け、左右のサブ複合体を分ける。[12]
回転角、ピッチ、分子形状は模式値であり、原子座標の再現ではない。

らせんの拡大場面ではIHFを含むR1-R5M間の長いDNAループを省略し、次の場面でそのループとIHFの屈曲を示す。
DnaA領域のらせんを保ったままDUEを左側へ近づけ、融解したT-rich ssDUEをR1・R5MのDnaA付近に保持する。[1,12,18]
DUEの融解は塩基対の解離であり、糖リン酸骨格は連続している。

白い説明枠では、負のスーパーコイルが環状oriCのDUE融解を助けることを示す。
IHFによるDNA屈曲そのものに負のスーパーコイルが必須という断定にはしない。
Sakiyama et al. (2017) は特定条件で線状oriCのDUE融解も起こると述べており、基質と実験条件を分けて扱う。[18]

### ヘリケースのロードと伸長

Domain IによるDnaBの係留と、Domain IIIによるロード補助を区別する。[2,5]
DnaCのリング開閉、DnaGのprimingに伴うDnaC離脱、βとPol IIIの装着を順に見せる。[3,4,6]
全分子が一斉に同じ経路を通るという意味ではなく、動画上の到着時刻と移動経路は説明用の補間である。

右向きのフォークのラギング鎖鋳型は左5′、フォーク側3′とする。
リーディング鎖鋳型は左3′、フォーク側5′である。
新生鎖は両方とも5′から3′へ伸び、RNAは各断片の5′側に置く。[6,7]
トロンボーン場面では曲がった鎖上の同じ極性を表示する。
Pol IIIは2-coreの機能模式図であり、量比と交換動態を網羅していない。

### Pol IとLigA、ニックの可視化

Pol IのDNA合成と5′ nucleaseによるRNA置換を描き、RNase HIの寄与を補足する。[7,8]
置換後は3′-OHと5′-phosphateの間に骨格の不連続が残り、LigAが封鎖する。[8]

末端の変位、揺れる範囲、ニックの幅は視認のための作画上の強調である。
塩基が欠落するギャップ、恒常的な数塩基の解離、測定された揺らぎを意味しない。
拡大窓にもこの区別を記載した。

### RCRの終結とTopB

ここでのRCRはSu’etsugu et al. (2017) のreplication-cycle reactionを指す。[13]
oriCからのシータ型複製を反復する再構成系であり、rolling-circle replicationの略としては用いていない。
2017年論文のFigure 1とFigure 2を基に、Topo IVとTopo III-RecQによる娘DNAの分離、Gyraseによる負の超らせん化を扱う。
Tus-terは同論文で追加検討された構成として説明する。

映像のTopB経路はSuski and Marians (2008) の再構成結果を使って具体化した。[14]
RecQが残った親二本鎖をほどき、TopB（Topo III）が一本鎖領域を利用する経路である。
TopB処理直後の娘DNAには未合成部が残りうるため、合成とLigAによる封鎖を後段にも描く。
実際の反応は協働して進みうる。
説明のための場面順を、必ず成り立つ固定的な直列順序とはしない。

ゲート場面では親鎖2本を取り出し、娘二本鎖の部分と多数の絡まりを省略する。
1回の鎖通過の前後を、連環した2本の環と分離した環として示す。
G鎖は切断される一本鎖、T鎖はそこを通過する別のDNAセグメントである。
TopBは5′末端を触媒Tyrとの共有結合で保持し、通過後はTopB自身が骨格を再結合する。[15,16]
青いゲート全体が1分子のTopBを表す。
表面の球の数はサブユニット数ではない。

Type IAは一本鎖にゲートを作り、通過セグメントには条件により一本鎖または二本鎖を使う。[15]
今回は一本鎖通過の代表例を描いた。
閉じた二本鎖環同士のカテナンを、そのままTopBの一本鎖ゲートで解く描写にはしない。
Topo IVによる二本鎖カテナンの脱連環を別経路として併記する。[13,14]
2017年RCRではTopB単独でも活性が見られ、RecQが促進したため、「全てのRCRでRecQがなければTopBは働かない」とは述べない。[13]

## 根拠の対応箇所

| 論点 | 原著で確認した箇所 | 表現上の区別 |
|---|---|---|
| Arg285と隣接DnaAのATP | Kawakami et al. (2005), Abstract [9] | Arg fingerに関わる機能証拠 |
| 左右の協同的集合 | Noguchi et al. (2015) [11]、Shimizu et al. (2016), Introduction [12] | R1・R4からの集合とR5Mの役割を区別 |
| らせんとR2、橋渡し分子 | Shimizu et al. (2016), Fig. 2, Discussion [12] | 左5・中央1・右5のモデル。未確定の橋渡しは追加しない |
| 右巻きAAA+集合 | Erzberger et al. (2006), Abstract, Fig. 2 [10] | Aquifex由来。E. coli全oriCの直接観察ではない |
| τ1、R5M、IHF | Sakiyama et al. (2017), Fig. 1-3と本文 [18] | サイト12個とIHF結合モデルの占有11分子を区別 |
| 左側Domain III界面 | Ozaki et al. (2012), Fig. 1とAbstract [17] | 添付図の原著。左側に固有な界面の機能 |
| カテナンの処理 | Zechiedrich and Cozzarelli (1995), Abstract [19] | Topo IVの主要な役割とGyraseの超らせん化 |
| RCRと脱連環 | Su’etsugu et al. (2017), Fig. 1, Fig. 2と本文 [13] | Topo IVとTopo III-RecQ、RecQによる促進 |
| RecQによる終結中間体の処理 | Suski and Marians (2008), Fig. 1, Fig. 2, Fig. 6-7 [14] | 一本鎖を含む中間体とgapped daughter products |
| TopBのゲート開閉 | Mills et al. (2018), Fig. 1, Fig. 3, Fig. 5 [15] | ゲート開閉の単分子観測と機構モデル。動画の運動そのものは創作 |
| ssDNAと5′末端の保持 | Changela et al. (2001), Abstract [16] | ssDNA認識構造とType IAの触媒機構 |

## 模式化と範囲

- 球の集合で作った分子形状を3次元座標から遠近投影する。PDB座標、cryo-EM密度、AlphaFoldの形状や分子動力学計算ではない。
- DNA長、分子間距離、反応速度、カメラ移動は説明用。DnaAは採用したモデルの11分子に合わせ、他の分子数は機能を説明する範囲とする。DNAの曲率と超らせん形状も定量値に対応しない。
- DNAの線が画面上で交差するだけでは切断や連結を意味しない。TopBの一時切断と再結合、LigAのニック封鎖は個別に示す。
- oriCの配列間隔、全サイトの占有率、HU、Fis、DiaA、SeqA、DARS、datA、開始時期の制御は網羅しない。
- 伸長の拡大は右向きの1フォーク。対向フォークの消失を意味しない。
- ループの成長と解放は機能模式図。同じ塩基を物質点として追跡する動力学モデルではない。
- 校正、損傷回避、染色体終結領域の全構成、XerCD/difの二量体解消、複製再開始の詳細は省略する。
- 終結はRCRを基にした代表経路。全ての生体内染色体が同じ時系列で終結するとはしない。

## 参考文献

各場面と本文の番号に対応する。
文献の図を転載せず、反応の説明を基に独自の模式形状を作った。

- **[1]** Ozaki & Katayama, Nucleic Acids Research, 2012, [Highly organized DnaA-oriC complexes recruit the single-stranded DNA for replication initiation](https://academic.oup.com/nar/article/40/4/1648/2411284). DOI: [10.1093/nar/gkr832](https://doi.org/10.1093/nar/gkr832)
  - DnaAの機能領域、IHFによる屈曲、DUEの融解とssDUE recruitment。
- **[2]** Hayashi et al., Journal of Biological Chemistry, 2020, [DnaB helicase is recruited to the replication initiation complex via binding of DnaA domain I to the lateral surface of the DnaB N-terminal domain](https://pubmed.ncbi.nlm.nih.gov/32540966/). DOI: [10.1074/jbc.RA120.014235](https://doi.org/10.1074/jbc.RA120.014235)
  - DnaA Domain IによるDnaBの係留とDomain IIIによるロード補助。
- **[3]** Arias-Palomo et al., Molecular Cell, 2019, [Physical Basis for the Loading of a Bacterial Replicative Helicase onto DNA](https://www.sciencedirect.com/science/article/pii/S1097276519300437). DOI: [10.1016/j.molcel.2019.01.023](https://doi.org/10.1016/j.molcel.2019.01.023)
  - DnaCによるDnaBリングの開閉と一本鎖DNAの取り込み。
- **[4]** Makowska-Grzyska & Kaguni, Molecular Cell, 2010, [Primase Directs the Release of DnaC from DnaB](https://doi.org/10.1016/j.molcel.2009.12.031). DOI: [10.1016/j.molcel.2009.12.031](https://doi.org/10.1016/j.molcel.2009.12.031)
  - DnaGとの相互作用およびプライマー形成に伴うDnaCの離脱。
- **[5]** Tsuruda et al., Nucleic Acids Research, 2026, [Dynamic DnaA-DnaB interactions at oriC coordinate the loading and coupled translocation of two DnaB helicases for bidirectional replication](https://pubmed.ncbi.nlm.nih.gov/41558826/). DOI: [10.1093/nar/gkaf1474](https://doi.org/10.1093/nar/gkaf1474)
  - Domain IIIを介した鎖特異的なロードと2個のDnaBの協調に関するモデル。
- **[6]** Yao et al., PNAS, 2009, [Single-molecule analysis reveals that the lagging strand increases replisome processivity but slows replication fork progression](https://doi.org/10.1073/pnas.0906157106). DOI: [10.1073/pnas.0906157106](https://doi.org/10.1073/pnas.0906157106)
  - Pol III、βクランプ、DnaGによる複製とトロンボーンモデルを支持する単分子実験。
- **[7]** Kitani et al., Journal of Molecular Biology, 1985, [Evidence that discontinuous DNA replication in Escherichia coli is primed by approximately 10 to 12 residues of RNA starting with a purine](https://pubmed.ncbi.nlm.nih.gov/2411935/). DOI: [10.1016/0022-2836(85)90042-7](https://doi.org/10.1016/0022-2836(85)90042-7)
  - 大腸菌のRNAプライマーとRNase HおよびPol Iの寄与。
- **[8]** Botto et al., Nature Structural & Molecular Biology, 2023, [A four-point molecular handover during Okazaki maturation](https://www.nature.com/articles/s41594-023-01071-y). DOI: [10.1038/s41594-023-01071-y](https://doi.org/10.1038/s41594-023-01071-y)
  - Pol IIIからPol Iへの移行、RNA置換と5′ nuclease活性、DNA ligaseへの受け渡し。
- **[9]** Kawakami et al., Journal of Biological Chemistry, 2005, [Formation of an ATP-DnaA-specific initiation complex requires DnaA Arginine 285, a conserved motif in the AAA+ protein family](https://pubmed.ncbi.nlm.nih.gov/15901724/). DOI: [10.1074/jbc.M502764200](https://doi.org/10.1074/jbc.M502764200)
  - 隣のDnaAに結合したATPを認識するArg285と開始複合体の機能。
- **[10]** Erzberger et al., Nature Structural & Molecular Biology, 2006, [Structural basis for ATP-dependent DnaA assembly and replication-origin remodeling](https://www.nature.com/articles/nsmb1115). DOI: [10.1038/nsmb1115](https://doi.org/10.1038/nsmb1115)
  - Aquifex aeolicus DnaAの右巻きAAA+集合体。大腸菌全oriCの実測構造ではない。
- **[11]** Noguchi et al., Journal of Biological Chemistry, 2015, [The Arg Fingers of Key DnaA Protomers Are Oriented Inward within the Replication Origin oriC and Stimulate DnaA Subcomplexes in the Initiation Complex](https://pubmed.ncbi.nlm.nih.gov/26126826/). DOI: [10.1074/jbc.M115.662601](https://doi.org/10.1074/jbc.M115.662601)
  - R1とR4に結合したDnaAから内側へ向かう協同的集合と左右のサブ複合体。
- **[12]** Shimizu et al., PNAS, 2016, [Near-atomic structural model for bacterial DNA replication initiation complex and its functional insights](https://pubmed.ncbi.nlm.nih.gov/27911788/). DOI: [10.1073/pnas.1609649113](https://doi.org/10.1073/pnas.1609649113)
  - 大腸菌oriCの左右のDnaAらせんと中央R2のモデル。DNA非結合DnaAによる橋渡しはDiscussionで挙げられた可能性。
- **[13]** Su’etsugu et al., Nucleic Acids Research, 2017, [Exponential propagation of large circular DNA by reconstitution of a chromosome-replication cycle](https://pubmed.ncbi.nlm.nih.gov/29036468/). DOI: [10.1093/nar/gkx822](https://doi.org/10.1093/nar/gkx822)
  - RCRの再構成、Topo IVとTopo III-RecQによる娘DNA分離、Gyraseによる超らせん化。Tus-terは追加構成。
- **[14]** Suski & Marians, Molecular Cell, 2008, [Resolution of Converging Replication Forks by RecQ and Topoisomerase III](https://pubmed.ncbi.nlm.nih.gov/18570879/). DOI: [10.1016/j.molcel.2008.04.020](https://doi.org/10.1016/j.molcel.2008.04.020)
  - RecQが未複製DNAをほどき、Topo IIIが一本鎖を含む終結中間体を解消する反応。
- **[15]** Mills et al., Nature Structural & Molecular Biology, 2018, [Direct observation of topoisomerase IA gate dynamics](https://pubmed.ncbi.nlm.nih.gov/30478267/). DOI: [10.1038/s41594-018-0158-x](https://doi.org/10.1038/s41594-018-0158-x)
  - 大腸菌Topo IとTopo IIIの一本鎖DNAゲート開閉の単分子観測。鎖通過は機構モデルとして表示。
- **[16]** Changela et al., Nature, 2001, [Crystal structure of a complex of a type IA DNA topoisomerase with a single-stranded DNA molecule](https://pubmed.ncbi.nlm.nih.gov/11429611/). DOI: [10.1038/35082615](https://doi.org/10.1038/35082615)
  - 大腸菌Topo IIIのssDNA認識と、5′-phosphotyrosine中間体を経るType IA反応の根拠。

- **[17]** Ozaki et al., Journal of Biological Chemistry, 2012, [Differentiation of the DnaA-oriC Subcomplex for DNA Unwinding in a Replication Initiation Complex](https://pubmed.ncbi.nlm.nih.gov/22942281/). DOI: [10.1074/jbc.M112.372052](https://doi.org/10.1074/jbc.M112.372052)
  - 添付図の原著。左右のDnaAサブ複合体と、左側のDomain III界面におけるArg227・Leu290の役割。
- **[18]** Sakiyama et al., Nucleic Acids Research, 2017, [Regulatory dynamics in the ternary DnaA complex for initiation of chromosomal replication in Escherichia coli](https://academic.oup.com/nar/article/45/21/12354/4428980). DOI: [10.1093/nar/gkx914](https://doi.org/10.1093/nar/gkx914)
  - 12個の結合サイトとIHFによるτ1占有の抑制、R5Mによる左側集合の促進、R1・R5MによるssDUE保持。
- **[19]** Zechiedrich & Cozzarelli, Genes & Development, 1995, [Roles of topoisomerase IV and DNA gyrase in DNA unlinking during replication in Escherichia coli](https://pubmed.ncbi.nlm.nih.gov/7590259/). DOI: [10.1101/gad.9.22.2859](https://doi.org/10.1101/gad.9.22.2859)
  - 複製に伴うDNA連環の解消におけるTopo IVの主要な役割。Gyraseによる超らせん化と機能を分けて示す。

