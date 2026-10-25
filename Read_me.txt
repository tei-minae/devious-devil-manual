Devious Devil 取扱説明書

DEVIOUS DEVIL USER GUIDE

Devious Devil 取扱説明書

素体と衣装が連動する胸サイズ調整ギミックを搭載しています。アバターに応じて、専用のDevil_BreastShapeまたはアバター標準の胸メニューから操作できます。

専用ラジアルメニューで、サングラスの着脱・透明度調整・専用ループダンスも操作できます。

衣装を導入する

VCCのVRChatアバター用Unity Projectに、Modular AvatarとlilToonを先に導入します。

使用するアバターに対応したunitypackageをインポートします。

素体のBodyにある胸関連Shape Keyをあらかじめ0にします。Breast_Inside／Breast_insideなどの内寄せ補正も0に戻し、基準の形状にしてください。Shape Keyの表記はアバターごとに異なります。

パッケージのPrefabフォルダーから、使用する色の衣装Prefabをアバター直下に配置します。色違いを同時に複数配置しないでください。

GestureManagerまたはVRChatで、Devious Devilの専用メニューを開きます。

GestureManagerはUnity内での動作確認用です。衣装を使用するための必須ツールではありません。

全7色のカラーバリエーション

各アバター版に、以下の全7色を同梱しています。

 | 色名 | カラー名（英語）

 | ピンク | Pink

 | ブルー | Blue

 | ラベンダー | Lavender

 | ミント | Mint

 | パンプキン | Pumpkin

 | ホワイト | White

 | イエロー | Yellow

Prefabフォルダーから好みの色を1つ選び、アバター直下へ配置してください。色名が付いていない標準PrefabはPink（ピンク）です。

アバター別の設定とMA Blendshape Sync対応

 | アバター | 胸サイズの操作入口 | 導入前の個別設定 | 確認済みのMA Blendshape Sync項目

 | しなの / Sinano | Devious Devil → Devil_BreastShape | Toe_heels = 100 | hipbig / Stockings3

 | エク / Eku | body → Breast | Foot_highheels = 100 | Hutomomo_big / Hutomomo_slim

 | ゆめか / Yumeka | Yumeka_Option → Breasts_Size | Foot_heel = 100 | —

 | siusiu / Siusiu | Devious Devil → Devil_BreastShape | highheels_up_heels = 65 | —

 | ナナセノワール / NanaseNoir | アバター標準の胸サイズメニュー | Highheels = 50 | —

 | ショコラ / Chocolat | Devious Devil → Devil_BreastShape | Foot_HighHeel = 100 | Foot_HighHeel
01_Devil_Platform_Sandals

 | ミルティナ / Milltina | Devious Devil → Devil_BreastShape | Toe_heels = 100 | —

 | ウェンディ / Wendy | アバター標準の胸サイズメニュー | Breasts_closer = 0
Toe_heels = 100 | —

 | うらら / Urara | Devious Devil → Devil_BreastShape | Toe_Heels = 50 | —

 | ミリアム / Miriam | Devious Devil → Devil_BreastShape | Foot_heel = 100 | —

 | ラムネ / Ramune | バストサイズ | Heel_Middle = 100 | —

ミルティナの事前準備

ミルティナは、衣装を使用する前に素体側のToe_heelsを100に設定してください。

ラムネの事前準備

ラムネは、衣装を使用する前に素体側のHeel_Middleを100に設定してください。

ミリアムの事前準備

ミリアムは、衣装を使用する前に素体側のFoot_heelを100に設定してください。

うららの事前準備

うららは、衣装を使用する前に素体側のToe_Heelsを50に設定してください。

エクの事前準備

エクは、衣装を使用する前に素体側のFoot_highheelsを100に設定してください。

ウェンディの事前準備

ウェンディは、衣装を使用する前に素体側のToe_heelsを100に設定してください。

siusiuの事前準備

siusiuは、衣装を使用する前に素体側のhighheels_up_heelsを65に設定してください。

ナナセノワールの事前準備

ナナセノワールは、衣装を使用する前に素体側のHighheelsを50に設定してください。

ゆめかの事前準備

ゆめかは、衣装を使用する前に素体側のFoot_heelを100に設定してください。

ショコラの事前準備

ショコラは、衣装を使用する前に素体側のFoot_HighHeelを100に設定してください。MA Blendshape Syncにより、衣装の01_Devil_Platform_Sandalsにある同名のFoot_HighHeelへ連動します。

「—」は本書で個別の指定値・対応項目を掲載していない欄です。非対応を意味しません。

アバター別の補足

ゆめか / Yumeka

アバター標準のYumeka_Option → Breasts_Sizeを使用します。50％が中立、100％で素体Big_1＝75／衣装＝100になります。Big_2は動かしません。

Siusiu

衣装メニューのDevil_BreastShapeを使用します。50％が中立で、下げると小さく、上げると大きくなります。

ナナセノワール / NanaseNoir

アバター標準の胸サイズメニューを使用し、衣装も連動します。衣装側のDevil_BreastShapeは使用しません。

ショコラ / Chocolat

衣装メニューのDevil_BreastShapeを使用します。50％が中立で、下げると小さく、上げると大きくなります。

ミルティナ / Milltina

衣装メニューのDevil_BreastShapeを使用します。50％が中立です。バッグにはSmall用Shape Keyがないため、バッグはBigのみ連動します。

ウェンディ / Wendy

アバター標準の胸サイズメニューを使用します。100％時は素体Breasts_big＝50／衣装＝100です。導入前に素体のBreasts_closerを0にしてください。ボレロとトップのBreasts_closer初期値も0です。

うらら / Urara

衣装メニューのDevil_BreastShapeを使用します。50％が中立です。バッグにはSmall用Shape Keyがないため、バッグはBigのみ連動します。

Miriam

ミリアムは専用のDevil_BreastShapeから操作します。Breastは胸を大きくするShape Keyで、Small用Shape Keyはありません。

Ramune

ラムネはアバター標準の「バストサイズ」メニューを使用します。

衣装のシェイプキー一覧

全11アバターの完成版衣装にあるシェイプキーを、メッシュごとに掲載しています。名前の大文字・小文字・記号はそのまま記載しています。

Blenderの完成版衣装をもとにした一覧です。2026-10-25に全アバターのボレロへ追加した袖調整キー2項目を反映しています。MA Blendshape Syncの連動対象や推奨値は、上の「アバター別の設定」をご確認ください。

更新日：2026-10-25。衣装220メッシュ、シェイプキー654個（Basisを除く）。素体・修復素体・Animation用メッシュは含みません。
アバターすべてのアバターゆめかしなのナナセノワールsiusiuミルティナうららウェンディエクショコラミリアムラムネメッシュ名・シェイプキー名で検索
アバター名を選ぶと一覧が開きます。検索は表示中のアバターと、メッシュ内のキー名に適用されます。
ゆめか20メッシュ / 60シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

Foot_heel

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breasts_Big_1

Breasts_Big_2

Waist_corset

Breasts_Width_1

Breasts_Width_2_(for Breasts_Big)

Breasts_Squash_(for Breasts_Big)

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | なし

 | 02_Devil_Waist_Wings.silver.ribbon | なし

 | 02_Devil_Wrap_Skirt_Upper | なし

 | 03_Devil_Halter_Top | 
Breasts_Big_1

Breasts_Big_2

Waist_corset

Nipple_ON

Nipple_big

Nipple_small

Breasts_Width_1

Breasts_Width_2_(for Breasts_Big)

Breasts_Squash_(for Breasts_Big)

 | 03_Devil_Wrap_Skirt_Lower | なし

 | 04_Devil_Bikini_Briefs | 
Hip_big

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

Wide

Narrow

Back.001

 | 04_Devil_Leg_Harness | なし

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | なし

 | 05_Devil_Crossbody_Bag | 
Extend

WidenStraps

WidenStraps2

WidenStraps3

Breasts_Big_1

Breasts_Big_2

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | なし

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

 | 05_Devil_Waist_FlipPhone_Holster | なし
しなの20メッシュ / 56シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
Toe_heels

RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breasts_big

Breasts_flat

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | 
Hip_big

 | 02_Devil_Waist_Wings.silver.ribbon | 
Hip_big

 | 02_Devil_Wrap_Skirt_Upper | 
Hip_big

 | 03_Devil_Halter_Top | 
Breasts_big

Breasts_flat

Nipple_ON

Nipple_big

Nipple_small

 | 03_Devil_Wrap_Skirt_Lower | 
Hip_big

 | 04_Devil_Bikini_Briefs | 
Hip_big

Hip_big2

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

 | 04_Devil_Leg_Harness | 
Hip_big

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | 
Hip_big

 | 05_Devil_Crossbody_Bag | 
Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | 
Hip_big

Stocking

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

 | 05_Devil_Waist_FlipPhone_Holster | なし
ナナセノワール20メッシュ / 53シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

Toe_heels

 | 01_Devil_Sheer Bolero | 
TieCuffs

14_Breast_big

15_Breast_small

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | なし

 | 02_Devil_Waist_Wings.silver.ribbon | なし

 | 02_Devil_Wrap_Skirt_Upper | なし

 | 03_Devil_Halter_Top | 
14_Breast_big

15_Breast_small

Nipple_ON

Nipple_big

Nipple_small

 | 03_Devil_Wrap_Skirt_Lower | なし

 | 04_Devil_Bikini_Briefs | 
Hip_big

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

Narrow

 | 04_Devil_Leg_Harness | なし

 | 04_Devil_Ribbon | 
14_Breast_big

15_Breast_small

 | 04_Devil_Waist_Belt | なし

 | 05_Devil_Crossbody_Bag | 
14_Breast_big

15_Breast_small

Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | なし

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

Back

 | 05_Devil_Waist_FlipPhone_Holster | なし
siusiu20メッシュ / 70シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

breasts_small

highheels_up_heels

 | 01_Devil_Platform_Sandals | 
Toe_heels

RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

breasts_small

highheels_up_heels

 | 01_Devil_Sheer Bolero | 
TieCuffs

breasts_big

breasts_small

breasts_bra

breasts_bra2

slim_back

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

breasts_small

highheels_up_heels

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | なし

 | 02_Devil_Waist_Wings.silver.ribbon | なし

 | 02_Devil_Wrap_Skirt_Upper | なし

 | 03_Devil_Halter_Top | 
breasts_big

breasts_small

slim_back

Nipple_ON

Nipple_big

Nipple_small

breasts_bra

breasts_bra2

 | 03_Devil_Wrap_Skirt_Lower | なし

 | 04_Devil_Bikini_Briefs | 
Hip_big

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

 | 04_Devil_Leg_Harness | なし

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | なし

 | 05_Devil_Crossbody_Bag | 
breasts_big

breasts_small

slim_back

Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

breasts_small

breasts_big

breasts_bra

breasts_bra2

slim_back

 | 05_Devil_Stockings | なし

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

Back

 | 05_Devil_Waist_FlipPhone_Holster | 
breasts_small

slim_back

ミルティナ20メッシュ / 61シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
Toe_heels

RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breasts_big

Breasts_small

(Wear bra)Breasts_Normal

(Wear bra)Breasts_Big

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | なし

 | 02_Devil_Waist_Wings.silver.ribbon | なし

 | 02_Devil_Wrap_Skirt_Upper | 
Hip_big

 | 03_Devil_Halter_Top | 
Breasts_big

Breasts_small

Nipple_ON

Nipple_big

Nipple_small

(Wear bra)Breasts_Normal

(Wear bra)Breasts_Big

 | 03_Devil_Wrap_Skirt_Lower | 
Hip_big

 | 04_Devil_Bikini_Briefs | 
Hip_big

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

Wide

Narrow

 | 04_Devil_Leg_Harness | 
Stocking

 | 04_Devil_Ribbon | 
(Wear bra)Breasts_Normal

 | 04_Devil_Waist_Belt | なし

 | 05_Devil_Crossbody_Bag | 
Breasts_big

(Wear bra)Breasts

Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | 
Stocking

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

Back

 | 05_Devil_Waist_FlipPhone_Holster | なし
うらら20メッシュ / 52シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
Toe_heels

RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breast_Big

Breast_Small

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | なし

 | 02_Devil_Waist_Wings.silver.ribbon | なし

 | 02_Devil_Wrap_Skirt_Upper | 
Hip_big

 | 03_Devil_Halter_Top | 
Breast_Big

Breast_Small

Nipple_ON

Nipple_big

Nipple_small

 | 03_Devil_Wrap_Skirt_Lower | 
Hip_big

 | 04_Devil_Bikini_Briefs | 
Hip_big

Hip_big2

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

 | 04_Devil_Leg_Harness | なし

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | なし

 | 05_Devil_Crossbody_Bag | 
Extend

WidenStraps

WidenStraps2

WidenStraps3

Breast_Big

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | なし

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

Back

 | 05_Devil_Waist_FlipPhone_Holster | なし
ウェンディ20メッシュ / 63シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
Toe_heels

RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breasts_big

Breasts_small

Breasts_flat

Breasts_closer

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | 
Hip_big

 | 02_Devil_Waist_Wings | 
Hip_big

 | 02_Devil_Waist_Wings.silver.ribbon | 
Hip_big

 | 02_Devil_Wrap_Skirt_Upper | 
Hip_big

 | 03_Devil_Halter_Top | 
Breasts_big

Breasts_small

Breasts_flat

Nipple_ON

Nipple_big

Nipple_small

Breasts_closer

 | 03_Devil_Wrap_Skirt_Lower | 
Hip_big

 | 04_Devil_Bikini_Briefs | 
Hip_big

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

Narrow

Wide

 | 04_Devil_Leg_Harness | 
Hip_big

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | 
Hip_big

 | 05_Devil_Crossbody_Bag | 
Breasts_big

Breasts_small

Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | 
Hip_big

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

 | 05_Devil_Waist_FlipPhone_Holster | なし
エク20メッシュ / 61シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
Toe_heels

RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

Foot_highheels

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breast_big

Breast_small

Breast_inside

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | なし

 | 02_Devil_Waist_Wings.silver.ribbon | なし

 | 02_Devil_Wrap_Skirt_Upper | 
Hip_big

 | 03_Devil_Halter_Top | 
Breast_big

Breast_small

Breast_inside

Nipple_ON

Nipple_big

Nipple_small

 | 03_Devil_Wrap_Skirt_Lower | 
Hip_big

 | 04_Devil_Bikini_Briefs | 
Hip_big

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

Wide

Narrow

 | 04_Devil_Leg_Harness | 
Hutomomo_big

Hutomomo_slim

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | なし

 | 05_Devil_Crossbody_Bag | 
Breast_big

Breast_small

Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | 
Hutomomo_big

Hutomomo_slim

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

Back

 | 05_Devil_Waist_FlipPhone_Holster | なし
ショコラ20メッシュ / 56シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

Foot_HighHeel

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breasts_big

Breasts_small

Waist_slim

Breasts_push_up

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | なし

 | 02_Devil_Waist_Wings.silver.ribbon | なし

 | 02_Devil_Wrap_Skirt_Upper | なし

 | 03_Devil_Halter_Top | 
Breasts_big

Breasts_small

Nipple_ON

Nipple_big

Nipple_small

Waist_slim

Breasts_push_up

 | 03_Devil_Wrap_Skirt_Lower | なし

 | 04_Devil_Bikini_Briefs | なし

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

Wide

Narrow

 | 04_Devil_Leg_Harness | なし

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | 
Waist_slim

 | 05_Devil_Crossbody_Bag | 
Breasts_big

Breasts_small

Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | なし

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

Back

 | 05_Devil_Waist_FlipPhone_Holster | なし
ミリアム20メッシュ / 57シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
Foot_heel

RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breast

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | 
Hip_big

 | 02_Devil_Waist_Wings.silver.ribbon | 
Hip_big

 | 02_Devil_Wrap_Skirt_Upper | 
Hip_big

 | 03_Devil_Halter_Top | 
Breast

Nipple_ON

Nipple_small

Nipple_big

 | 03_Devil_Wrap_Skirt_Lower | 
Hip_big

 | 04_Devil_Bikini_Briefs | 
Hip_big

Hip_big2

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

Wide

Narrow

 | 04_Devil_Leg_Harness | 
Hip_big

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | 
Hip_big

 | 05_Devil_Crossbody_Bag | 
Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | 
Hip_big

Stocking

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

Back

 | 05_Devil_Waist_FlipPhone_Holster | なし
ラムネ20メッシュ / 65シェイプキー
 | 衣装メッシュ | シェイプキー名

 | 01_Devil_Leg_Covers | 
Wide

narrow

 | 01_Devil_Platform_Sandals | 
Heel_Middle

RaiseToeStrap

RaiseToeStrap2

RaiseToeStrap3

RaiseHeelStrap

Up

Down

Wide

narrow

Raisingthebottom

Vertical

 | 01_Devil_Sheer Bolero | 
TieCuffs

Breasts_big

Breasts_little

Sleeve_ruching

Sleeve_cuff_slim

 | 02_Devil_Ankle_Straps | 
Wide

Narrow

Wingfold

Up

Down

 | 02_Devil_Tail | なし

 | 02_Devil_Waist_Wings | 
Hips_Thick

 | 02_Devil_Waist_Wings.silver.ribbon | 
Hips_Thick

 | 02_Devil_Wrap_Skirt_Upper | 
Hips_Thick

 | 03_Devil_Halter_Top | 
Breast_Big

Breast_Little

Nipple_ON

Nipple_big

Nipple_small

Belly_Slim

Belly_Thick

 | 03_Devil_Wrap_Skirt_Lower | 
Hips_Thick

 | 04_Devil_Bikini_Briefs | 
Hips_Thick

Hips_Slim

Hip_big

 | 04_Devil_Horn_Headband | 
Up

Down

Forward

Back

Wide

Narrow

 | 04_Devil_Leg_Harness | 
Thighs_Thick

Thighs_Slim

 | 04_Devil_Ribbon | なし

 | 04_Devil_Waist_Belt | 
Hips_Thick

 | 05_Devil_Crossbody_Bag | 
Breasts_big

Breast_Little

Extend

WidenStraps

WidenStraps2

WidenStraps3

 | 05_Devil_Crossbody_Plush | 
SizeUp

SizeUpExtra

 | 05_Devil_Stockings | 
Thighs_Thick

Thighs_Slim

 | 05_Devil_Sunglasses | 
Wear

Extend

Forward

Tilt

Wide

Vertical

WidenEnds

Narrow

Back

 | 05_Devil_Waist_FlipPhone_Holster | なし

該当するメッシュはありません。

専用ラジアルメニューを使う

Devious Devil内のカスタマイズメニューで操作します。画像の右上のSunglassesから時計回りに、次の6項目が並んでいます。
しなの版の表示例。画像を選ぶと原寸で確認できます。上部のBackで前のメニューに戻ります。
 | 順 | 項目 | 使い方

 | 1 | サングラスの着脱Sunglasses | 選ぶたびにサングラスの表示をON／OFFできます。

 | 2 | ボレロの透明度を調整するBolero Transparency | 初期値は50％です。0％＝24、50％＝34、100％＝43を基準に、ボレロの透明度を調整します。

 | 3 | スカート上段の透明度を下げるUpper Skirt Transparency | 上段だけの透明度を下げます。最大まで操作すると透明度0（透けない状態）になります。

 | 4 | スカート下段の透明度を下げるLower Skirt Transparency | 下段だけの透明度を下げます。最大まで操作すると透明度0（透けない状態）になります。

 | 5 | 専用ループダンスDeviousRolly | ONで専用のループダンスを再生し、OFFで終了します。

 | 6 | 胸のサイズ調整Devil_BreastShape | 対応するアバターのみ表示されます。50％が中立で、下げると小さく、上げると大きくなります。

ボレロは50％が初期値です。スカートは上下段を個別に、最大で透明度0（透けない状態）まで下げられます。ラジアルの％は調整量で、透明度0は非表示を意味しません。メニュー位置や表示項目は、アバターと他のメニュー構成によって異なる場合があります。

ボレロの透明度スライダー

専用メニューの Bolero Transparency で調整します。初期値は50％です。50％を基準に、0％側・100％側の両方向へ調整できます。

 | スライダー | ボレロの調整値 | 状態

 | 0% | 24 | 下限

 | 50% | 34 | 初期値・基準

 | 100% | 43 | 上限

0～50％は24から34へ、50～100％は34から43へ、直線的に変化します。基準状態に戻したい場合は50％に戻してください。

スライダーの％や調整値24・34・43は、実際の透過率を示すものではありません。0％でもボレロは非表示になりません。スカート上下段の透明度スライダーは別の設定です。

羽としっぽのAnimation

衣装には、背中の羽・しっぽ・足首の羽の専用Animationを搭載しています。

胸ギミックを使わない場合も、これらのAnimation用設定はそのまま残してください。

胸の調整入口を確認する

しなの・Siusiu・ショコラ・ミルティナ・うらら・ミリアムは、専用メニューのDevil_BreastShapeから操作します。

エク・ゆめか・ナナセノワール・ウェンディ・ラムネは、アバター標準の胸サイズメニューから操作します。

衣装に胸ギミックを追加したタイプ

専用メニューのDevil_BreastShapeを使用します。しなの版はこのタイプです。

50％が中立です。下げると小さく、上げると大きくなります。

アバター標準の胸ギミックを使うタイプ

アバター本来の胸サイズメニューを使用し、衣装も連動して変形します。

エクはbody → Breastから操作します。衣装専用メニューには、重複を避けるためDevil_BreastShapeを表示していません。

他のアバターではBreastやBreasts_Sizeなど、元のメニュー名が異なります。

エク版としなの版の補正基準

 | ラジアル値 | 素体 | 衣装

 | 0％ | Small／Flat 100
Big 0 | Small／Flat 75
Big 0

 | 50％ | Small／Flat 0
Big 0 | Small／Flat 0
Big 0

 | 100％ | Big 75
Small／Flat 0 | Big 100
Small／Flat 0

素体と衣装の補正量に差を設け、貫通を抑える構成です。Shape Keyの名称・有無はアバターごとに異なり、形状や姿勢によって追加調整が必要な場合があります。

胸ギミックを使わず手動で設定する

好みの胸の形状を固定したい場合は、胸ギミックを外してから、素体と衣装のShape Keyを手動設定します。以下は共通の進め方です。オブジェクト名・FXのLayer名はアバターごとに異なります。エクとしなのの具体名は例として記載しています。

UnityのPlay Modeを終了し、作業前の衣装Prefabと変更するFXを複製してバックアップします。

胸補正専用オブジェクトの、素体用・衣装用の胸補正MA Merge Animatorを外します。エクはDeviousDevil_BreastCorrection、しなのはDeviousDevil_BreastCorrection_Sinanoが対象です。胸補正だけを含む子オブジェクトなら、その子ごと削除できます。衣装ルートや他のギミック用Componentは残してください。子を非表示にするだけではなく、胸補正を追加するComponentを外します。

元から胸ギミックがないタイプは、そのまま手動設定に進みます。使用しないDevil_BreastShapeのメニュー項目は、衣装側Expressions Menuを複製してから削除できます。複製したメニューを、元のメニューを参照していたMA設定へ割り当てます。

標準の胸ギミックがあるタイプは、アバター側FXを複製し、胸サイズを動かすLayerの制御も外します。エクの具体例は下記を参照してください。他のアバターではLayer名が異なるため、同じ名前で探して削除しないでください。

素体のBodyの胸関連Shape Keyを、Breast_Inside／Breast_insideなども含めてまず0に戻します。その後、素体と衣装のSkinned Mesh Renderer → BlendShapesで好みの値を設定します。ボレロ・トップ・バッグは、存在する胸用Shape Keyを調整します。胸用MA Blendshape Syncが残っている場合は連動元から調整し、各パーツを別々に設定する場合だけ胸用の同期項目も外してください。

衣装Prefabとシーンを保存し、GestureManagerまたはVRChatで固定値が維持されることを確認します。

エクの標準FXから胸サイズ制御を外す

Avatar DescriptorのPlayable Layers → FXに割り当てられたControllerを複製します。複製したFXをAnimatorウィンドウで開き、Breast Layerだけを削除します。エクの標準FXでは、State名はBreastSizeです。

複製したControllerをAvatar DescriptorのFXへ割り当てます。他のLayerとParameterは維持してください。元のFXのままでは、標準BreastメニューのAnimationが手動値を上書きします。

手動設定時に確認すること

エクの胸補正を外すとBreast_insideの0固定も外れます。Big／Smallだけで設定したい場合は、Body_baseのBreast_insideを手動で0にします。

別のMA Blendshape SyncやAnimationが胸へ書き込む構成では、その胸の制御も外してから設定します。

サングラス・透明度・ダンス用のAnimatorは外さないでください。

衣装ルートの名前を変更する

素体用と衣装用を分けた配布Prefabでは、衣装ルート名にPinkやBlueを付けられます。内部のメッシュ名（01_Devil_Sheer Boleroなど）と階層は変更しないでください。

衣装用MA Merge Animatorの相対パスのルートは、衣装ルートを指定したままにします。

Performance

既存の掲載値を参考として記載しています。今回追加した7体それぞれの再計測値ではありません。

 | 項目 | 値

 | Triangles / Tris | △ 79,766

 | Skinned Mesh Renderers | 21

 | Material Slots | 22

 | Materials | 5 Main（2048px）＋ 2 Auxiliary

 | Texture Size | 38.1 MB
lilAvatarUtils 2.1.2で計測

 | 衣装単体アップロード時のDownload Size | 約13 MB

補助マテリアルは、512pxのストッキング網目用タイリングマテリアルと、既存テクスチャを共有するRender Queue調整用マテリアルです。

Material Slotsは22ですが、ユニークなマテリアル数は7です。内訳はメイン5＋補助2です。

Skinned Mesh Rendererは21ですが、ストッキングが2スロット使用しているためMaterial Slotsが22になっています。

Read_meをダウンロード　印刷

Devious Devil 取扱説明書 · 更新日 2026年10月25日
