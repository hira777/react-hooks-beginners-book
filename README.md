# 『React Hooks 入門』

『React Hooks 入門』のサンプルコード集です。

サンプルコードは[CodeSandbox](https://codesandbox.io/)上にあるため、各サンプルコードのリンクを記載しています。

## 3. useState

- [01-useStateの基本的な利用例](https://codesandbox.io/s/01-usestatenojibendenaliyongli-tb02z?file=/src/App.js)
- [02-usestateの戻り値であるstate更新関数の引数に関数を渡す](https://codesandbox.io/s/02-usestatenolirizhidearustategengxinguanshunoyinshuniguanshuwodusu-wvfb2?file=/src/App.js)
- [03-usestateでオブジェクトを扱う](https://codesandbox.io/s/03-usestatedeobuziekutowoxiu-nze7v?file=/src/App.js)
- [04-usestateでオブジェクトを扱っているがコンポーネントが再レンダーされない例](https://codesandbox.io/s/04-usestatedeobuziekutowoxituteirugakonponentogazairendasarenaili-6mljy?file=/src/App.js)
- [05-usestateで配列を扱う](https://codesandbox.io/s/05-usestatedepeiliewoxiu-tnior?file=/src/App.js)
- [06-usestateで配列を扱っているがコンポーネントが再レンダーされない例](https://codesandbox.io/s/06-usestatedepeiliewoxituteirugakonponentogazairendasarenaili-1fv6v?file=/src/App.js)

## 4. useEffect

- [01-useEffectでコンポーネントがレンダーされる度に副作用を実行させる](https://codesandbox.io/s/01-useeffectdekonponentogarendasarerudunifuzuoyongwoshixingsaseru-n56bd?file=/src/App.js)
- [02-useEffectで副作用を１度だけ実行させる（外部APIからデータを取得する）](https://codesandbox.io/s/02-useeffectdefuzuoyongwo1dudakeshixingsaseruwaibuapikaradetawoqudesuru-vun0d?file=/src/App.js)
- [03-useEffectで副作用に依存する値（クエリ）が更新した時だけ副作用を実行させる（外部APIからデータを取得する）](https://codesandbox.io/s/03-useeffectdefuzuoyongniyicunsuruzhikuerigagengxinsitashidakefuzuoyongwoshixingsaseruwaibuapikaradetawoqudesuru-bzjjz?file=/src/App.js)
- [04-useEffectでクリーンアップ（タイマーを削除する処理）を実行させる](https://codesandbox.io/s/04-useeffectdekurinatuputaimawoxuechusuruchuliwoshixingsaseru-gygtc?file=/src/App.js)

## 5. useRef

- [01-useRefで前回のstateの値を保持して要素の出し分けに利用する](https://codesandbox.io/s/01-userefdeqianhuinostatenozhiwobaochisiteyaosunochusifenkeniliyongsuru-4nsq4?file=/src/App.js)
- [02-useRefでコンポーネント内の値を更新しつつ、再レンダーを防ぐ](https://codesandbox.io/s/02-userefdekonponentoneinozhiwogengxinsitutuzairendawofanggu-8zk93?file=/src/App.js)
- [03-useRefではなく、useStateで「初回レンダー」の表示を試す](https://codesandbox.io/s/03-userefdehanakuusestatedechuhuirendanobiaoshiwoshisu-rnkdm?file=/src/App.js)
- [04-useRefでDOMを参照する](https://codesandbox.io/s/04-userefdedomwocanzhaosuru-8zj3q?file=/src/App.js)

## 6. React.memo / useCallback / useMemo

- [01-React.memoを利用しない場合、親コンポーネントが再レンダーされると、その子コンポーネントも常に再レンダーされる](https://codesandbox.io/s/01-reactmemowoliyongsinaichangheqinkonponentogazairendasarerutosonozikonponentomochangnizairendasareru-1f2ne?file=/src/App.js)
- [02-React.memoでChildコンポーネントの再レンダーをスキップする](https://codesandbox.io/s/02-reactmemodechildkonponentonozairendawosukitupusuru-4d2r5?file=/src/App.js)
- [03-React.memoでレンダーコストが高いコンポーネントをメモ化する](https://codesandbox.io/s/03-reactmemoderendakosutogagaoikonponentowomemohuasuru-m4p6i?file=/src/App.js)
- [04-React.memoで頻繁に再レンダーされるコンポーネント内の子コンポーネントをメモ化する](https://codesandbox.io/s/04-reactmemodepinfannizairendasarerukonponentoneinozikonponentowomemohuasuru-k91bi?file=/src/App.js)
- [05-コールバック関数を受け取ったコンポーネントはReact.memoを利用しても必ず再レンダーされてしまう](https://codesandbox.io/s/05-korubatukuguanshuwoshoukeqututakonponentohareactmemowoliyongsitemobizuzairendasaretesimau-ghiyq?file=/src/App.js)
- [06-useCallbackでメモ化したコールバック関数を渡し、コンポーネントの再レンダーをスキップする](https://codesandbox.io/s/06-usecallbackdememohuasitakorubatukuguanshuwodusikonponentonozairendawosukitupusuru-ucixd?file=/src/App.js)
- [07-React.memoでメモ化をしていないコンポーネントに、メモ化をしたコールバック関数を渡してもコンポーネントは常に再レンダーされる](https://codesandbox.io/s/07-reactmemodememohuawositeinaikonponentonimemohuawositakorubatukuguanshuwodusitemokonponentohachangnizairendasareru-mugp6?file=/src/App.js)
- [08-メモ化したコールバック関数を、それを生成したコンポーネント自身で利用しても、コンポーネントの再レンダーはスキップできない](https://codesandbox.io/s/08-memohuasitakorubatukuguanshuwosorewoshengchengsitakonponentozishendeliyongsitemokonponentonozairendahasukitupudekinai-9unxh?file=/src/App.js)
- [09-useMemoを利用しない場合、コンポーネントを再レンダーする度に不要な再計算が発生する](https://codesandbox.io/s/09-usememowoliyongsinaichanghekonponentowozairendasurudunibuyaonazaijisuangafashengsuru-nfrvj?file=/src/App.js)
- [10-useMemoで不要な再計算をスキップする](https://codesandbox.io/s/10-usememodebuyaonazaijisuanwosukitupusuru-8w7p8?file=/src/App.js)
- [11-useMemoでコンポーネントの再レンダーをスキップする](https://codesandbox.io/s/11-usememodekonponentonozairendawosukitupusuru-45e58?file=/src/App.js)
- [12-関数コンポーネント内でReact.memoを利用してもコンポーネントをメモ化できない](https://codesandbox.io/s/12-guanshukonponentoneidereactmemowoliyongsitemokonponentowomemohuadekinai-j53oo?file=/src/App.js)

## 7. useReducer

- [01-useReducerの利用例](https://codesandbox.io/s/01-usereducernoliyongli-jqumb?file=/src/App.js)
- [02-useStateを利用した場合、stateの更新方法の数だけ、コンポーネントに state 更新関数を渡す必要がある](https://codesandbox.io/s/02-usestatewoliyongsitachanghestatenogengxinfangfanoshudakekonponentoni-state-gengxinguanshuwodusubiyaogaaru-emtj1?file=/src/App.js)
- [03-useReducerを利用した場合、stateを更新する窓口はdispatchに集約するため、コンポーネントにはdispatchさえ渡せば良い](https://codesandbox.io/s/03-usereducerwoliyongsitachanghestatewogengxinsuruchuangkouhadispatchnijiyuesurutamekonponentonihadispatchsaedusebaliangi-up8e0?file=/src/App.js)
- [04-dispatchは同一性が保たれるので、useCallbackでラップをせずにメモ化したコンポーネントに渡せる](https://codesandbox.io/s/04-dispatchhatongyixinggabaotarerunodeusecallbackderatupuwosezunimemohuasitakonponentoniduseru-fq4by?file=/src/App.js)
- [05-Counterコンポーネントの再レンダーを防ぐためには、Propsとして渡す関数を全てuseCallbackでラップする必要がある](https://codesandbox.io/s/05-counterkonponentonozairendawofanggutamenihapropstositedusuguanshuwoquanteusecallbackderatupusurubiyaogaaru-zylfw?file=/src/App.js)

## 8. Context / useContext

- [01-useContextで、Appから見てひ孫にあたるGreatGrandChildコンポーネントからMyContextの値を取得する](https://codesandbox.io/s/01-usecontextdeappkarajiantehisunniatarugreatgrandchildkonponentokaramycontextnozhiwoqudesuru-947gu?file=/src/App.js)
- [02-useContextを利用しない場合、AppからGreatGrandChildComponentに値を渡すためにはProp drillingを行う必要がある](https://codesandbox.io/s/02-usecontextwoliyongsinaichangheappkaragreatgrandchildcomponentnizhiwodusutamenihaprop-drillingwoxingubiyaogaaru-sn9fm?file=/src/App.js)
- [03-複数のコンポーネントで共通利用するデータをContextで扱い、それをuseContextで取得する](https://codesandbox.io/s/03-fushunokonponentodegongtongliyongsurudetawocontextdexiisorewousecontextdequdesuru-ks7sc?file=/src/App.js)
- [04-Contextの更新により不要な再レンダーが発生している例](https://codesandbox.io/s/04-contextnogengxinniyoribuyaonazairendagafashengsiteiruli-ew6nj?file=/src/App.js)
- [05-Contextオブジェクトを分割して、Contextの更新による不要な再レンダーを防ぐ](https://codesandbox.io/s/05-contextobuziekutowofengesitecontextnogengxinniyorubuyaonazairendawofanggu-wcqix?file=/src/App.js)
- [06-React.memoを利用して、Contextの更新による不要な再レンダーを防ぐ](https://codesandbox.io/s/06-reactmemowoliyongsitecontextnogengxinniyorubuyaonazairendawofanggu-45d5h?file=/src/App.js)
- [07-useMemoを利用して、Contextの更新による不要な再レンダーを防ぐ例](https://codesandbox.io/s/07-usememowoliyongsitecontextnogengxinniyorubuyaonazairendawofangguli-oqpod?file=/src/App.js)
- [08-props.childrenを利用してProp drilling問題を解消する](https://codesandbox.io/s/08-propschildrenwoliyongsiteprop-drillingwentiwojiexiaosuru-bll6k?file=/src/App.js)

## 9. カスタムフック

- [01-Appコンポーネントがカウンターのstateとstate更新ロジックを持っているコード](https://codesandbox.io/s/01-appkonponentogakauntanostatetostategengxinrozitukuwochituteirukodo-43ctm?file=/src/App.js)
- [02-Appコンポーネントのstateとstate更新ロジックをカスタムフックに切り出す](https://codesandbox.io/s/02-appkonponentonostatetostategengxinrozitukuwokasutamuhutukuniqierichusu-uqp6m?file=/src/App.js)
- [03-カスタムフックを再利用する](https://codesandbox.io/s/03-kasutamuhutukuwozailiyongsuru-dbqj8?file=/src/App.js)