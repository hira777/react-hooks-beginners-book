# 『React Hooks 入門』

[『React Hooks 入門』](https://www.amazon.co.jp/dp/B08JTXQ2M6/)のサンプルコード集です。

サンプルコードは[CodeSandbox](https://codesandbox.io/)上にあるため、各サンプルコードのリンクを記載しています。

## 3. useState

- [01-useState の基本的な利用例](https://codesandbox.io/s/01-usestatenojibendenaliyongli-tb02z?file=/src/App.js)
- [02-usestate の戻り値である state 更新関数の引数に関数を渡す](https://codesandbox.io/s/02-usestatenolirizhidearustategengxinguanshunoyinshuniguanshuwodusu-wvfb2?file=/src/App.js)
- [03-usestate でオブジェクトを扱う](https://codesandbox.io/s/03-usestatedeobuziekutowoxiu-nze7v?file=/src/App.js)
- [04-usestate でオブジェクトを扱っているがコンポーネントが再レンダーされない例](https://codesandbox.io/s/04-usestatedeobuziekutowoxituteirugakonponentogazairendasarenaili-6mljy?file=/src/App.js)
- [05-usestate で配列を扱う](https://codesandbox.io/s/05-usestatedepeiliewoxiu-tnior?file=/src/App.js)
- [06-usestate で配列を扱っているがコンポーネントが再レンダーされない例](https://codesandbox.io/s/06-usestatedepeiliewoxituteirugakonponentogazairendasarenaili-1fv6v?file=/src/App.js)

## 4. useEffect

- [01-useEffect でコンポーネントがレンダーされる度に副作用を実行させる](https://codesandbox.io/s/01-useeffectdekonponentogarendasarerudunifuzuoyongwoshixingsaseru-n56bd?file=/src/App.js)
- [02-useEffect で副作用を１度だけ実行させる（外部 API からデータを取得する）](https://codesandbox.io/s/02-useeffectdefuzuoyongwo1dudakeshixingsaseruwaibuapikaradetawoqudesuru-vun0d?file=/src/App.js)
- [03-useEffect で副作用に依存する値（クエリ）が更新した時だけ副作用を実行させる（外部 API からデータを取得する）](https://codesandbox.io/s/03-useeffectdefuzuoyongniyicunsuruzhikuerigagengxinsitashidakefuzuoyongwoshixingsaseruwaibuapikaradetawoqudesuru-bzjjz?file=/src/App.js)
- [04-useEffect でクリーンアップ（タイマーを削除する処理）を実行させる](https://codesandbox.io/s/04-useeffectdekurinatuputaimawoxuechusuruchuliwoshixingsaseru-gygtc?file=/src/App.js)

## 5. useRef

- [01-useRef で前回の state の値を保持して要素の出し分けに利用する](https://codesandbox.io/s/01-userefdeqianhuinostatenozhiwobaochisiteyaosunochusifenkeniliyongsuru-4nsq4?file=/src/App.js)
- [02-useRef でコンポーネント内の値を更新しつつ、再レンダーを防ぐ](https://codesandbox.io/s/02-userefdekonponentoneinozhiwogengxinsitutuzairendawofanggu-8zk93?file=/src/App.js)
- [03-useRef ではなく、useState で「初回レンダー」の表示を試す](https://codesandbox.io/s/03-userefdehanakuusestatedechuhuirendanobiaoshiwoshisu-rnkdm?file=/src/App.js)
- [04-useRef で DOM を参照する](https://codesandbox.io/s/04-userefdedomwocanzhaosuru-8zj3q?file=/src/App.js)

## 6. React.memo / useCallback / useMemo

- [01-React.memo を利用しない場合、親コンポーネントが再レンダーされると、その子コンポーネントも常に再レンダーされる](https://codesandbox.io/s/01-reactmemowoliyongsinaichangheqinkonponentogazairendasarerutosonozikonponentomochangnizairendasareru-1f2ne?file=/src/App.js)
- [02-React.memo で Child コンポーネントの再レンダーをスキップする](https://codesandbox.io/s/02-reactmemodechildkonponentonozairendawosukitupusuru-4d2r5?file=/src/App.js)
- [03-React.memo でレンダーコストが高いコンポーネントをメモ化する](https://codesandbox.io/s/03-reactmemoderendakosutogagaoikonponentowomemohuasuru-m4p6i?file=/src/App.js)
- [04-React.memo で頻繁に再レンダーされるコンポーネント内の子コンポーネントをメモ化する](https://codesandbox.io/s/04-reactmemodepinfannizairendasarerukonponentoneinozikonponentowomemohuasuru-k91bi?file=/src/App.js)
- [05-コールバック関数を受け取ったコンポーネントは React.memo を利用しても必ず再レンダーされてしまう](https://codesandbox.io/s/05-korubatukuguanshuwoshoukeqututakonponentohareactmemowoliyongsitemobizuzairendasaretesimau-ghiyq?file=/src/App.js)
- [06-useCallback でメモ化したコールバック関数を渡し、コンポーネントの再レンダーをスキップする](https://codesandbox.io/s/06-usecallbackdememohuasitakorubatukuguanshuwodusikonponentonozairendawosukitupusuru-ucixd?file=/src/App.js)
- [07-React.memo でメモ化をしていないコンポーネントに、メモ化をしたコールバック関数を渡してもコンポーネントは常に再レンダーされる](https://codesandbox.io/s/07-reactmemodememohuawositeinaikonponentonimemohuawositakorubatukuguanshuwodusitemokonponentohachangnizairendasareru-mugp6?file=/src/App.js)
- [08-メモ化したコールバック関数を、それを生成したコンポーネント自身で利用しても、コンポーネントの再レンダーはスキップできない](https://codesandbox.io/s/08-memohuasitakorubatukuguanshuwosorewoshengchengsitakonponentozishendeliyongsitemokonponentonozairendahasukitupudekinai-9unxh?file=/src/App.js)
- [09-useMemo を利用しない場合、コンポーネントを再レンダーする度に不要な再計算が発生する](https://codesandbox.io/s/09-usememowoliyongsinaichanghekonponentowozairendasurudunibuyaonazaijisuangafashengsuru-nfrvj?file=/src/App.js)
- [10-useMemo で不要な再計算をスキップする](https://codesandbox.io/s/10-usememodebuyaonazaijisuanwosukitupusuru-8w7p8?file=/src/App.js)
- [11-useMemo でコンポーネントの再レンダーをスキップする](https://codesandbox.io/s/11-usememodekonponentonozairendawosukitupusuru-45e58?file=/src/App.js)
- [12-関数コンポーネント内で React.memo を利用してもコンポーネントをメモ化できない](https://codesandbox.io/s/12-guanshukonponentoneidereactmemowoliyongsitemokonponentowomemohuadekinai-j53oo?file=/src/App.js)

## 7. useReducer

- [01-useReducer の利用例](https://codesandbox.io/s/01-usereducernoliyongli-jqumb?file=/src/App.js)
- [02-useState を利用した場合、state の更新方法の数だけ、コンポーネントに state 更新関数を渡す必要がある](https://codesandbox.io/s/02-usestatewoliyongsitachanghestatenogengxinfangfanoshudakekonponentoni-state-gengxinguanshuwodusubiyaogaaru-emtj1?file=/src/App.js)
- [03-useReducer を利用した場合、state を更新する窓口は dispatch に集約するため、コンポーネントには dispatch さえ渡せば良い](https://codesandbox.io/s/03-usereducerwoliyongsitachanghestatewogengxinsuruchuangkouhadispatchnijiyuesurutamekonponentonihadispatchsaedusebaliangi-up8e0?file=/src/App.js)
- [04-dispatch は同一性が保たれるので、useCallback でラップをせずにメモ化したコンポーネントに渡せる](https://codesandbox.io/s/04-dispatchhatongyixinggabaotarerunodeusecallbackderatupuwosezunimemohuasitakonponentoniduseru-fq4by?file=/src/App.js)
- [05-Counter コンポーネントの再レンダーを防ぐためには、Props として渡す関数を全て useCallback でラップする必要がある](https://codesandbox.io/s/05-counterkonponentonozairendawofanggutamenihapropstositedusuguanshuwoquanteusecallbackderatupusurubiyaogaaru-zylfw?file=/src/App.js)

## 8. Context / useContext

- [01-useContext で、App から見てひ孫にあたる GreatGrandChild コンポーネントから MyContext の値を取得する](https://codesandbox.io/s/01-usecontextdeappkarajiantehisunniatarugreatgrandchildkonponentokaramycontextnozhiwoqudesuru-947gu?file=/src/App.js)
- [02-useContext を利用しない場合、App から GreatGrandChildComponent に値を渡すためには Prop drilling を行う必要がある](https://codesandbox.io/s/02-usecontextwoliyongsinaichangheappkaragreatgrandchildcomponentnizhiwodusutamenihaprop-drillingwoxingubiyaogaaru-sn9fm?file=/src/App.js)
- [03-複数のコンポーネントで共通利用するデータを Context で扱い、それを useContext で取得する](https://codesandbox.io/s/03-fushunokonponentodegongtongliyongsurudetawocontextdexiisorewousecontextdequdesuru-ks7sc?file=/src/App.js)
- [04-Context の更新により不要な再レンダーが発生している例](https://codesandbox.io/s/04-contextnogengxinniyoribuyaonazairendagafashengsiteiruli-ew6nj?file=/src/App.js)
- [05-Context オブジェクトを分割して、Context の更新による不要な再レンダーを防ぐ](https://codesandbox.io/s/05-contextobuziekutowofengesitecontextnogengxinniyorubuyaonazairendawofanggu-wcqix?file=/src/App.js)
- [06-React.memo を利用して、Context の更新による不要な再レンダーを防ぐ](https://codesandbox.io/s/06-reactmemowoliyongsitecontextnogengxinniyorubuyaonazairendawofanggu-45d5h?file=/src/App.js)
- [07-useMemo を利用して、Context の更新による不要な再レンダーを防ぐ例](https://codesandbox.io/s/07-usememowoliyongsitecontextnogengxinniyorubuyaonazairendawofangguli-oqpod?file=/src/App.js)
- [08-props.children を利用して Prop drilling 問題を解消する](https://codesandbox.io/s/08-propschildrenwoliyongsiteprop-drillingwentiwojiexiaosuru-bll6k?file=/src/App.js)

## 9. カスタムフック

- [01-App コンポーネントがカウンターの state と state 更新ロジックを持っているコード](https://codesandbox.io/s/01-appkonponentogakauntanostatetostategengxinrozitukuwochituteirukodo-43ctm?file=/src/App.js)
- [02-App コンポーネントの state と state 更新ロジックをカスタムフックに切り出す](https://codesandbox.io/s/02-appkonponentonostatetostategengxinrozitukuwokasutamuhutukuniqierichusu-uqp6m?file=/src/App.js)
- [03-カスタムフックを再利用する](https://codesandbox.io/s/03-kasutamuhutukuwozailiyongsuru-dbqj8?file=/src/App.js)
