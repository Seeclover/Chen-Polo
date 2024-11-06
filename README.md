<pre>

 .----------------.  .----------------.
| .--------------. || .--------------. |
| |  ________    | || |    _______   | |
| | |_   ___ `.  | || |   /  ___  |  | |
| |   | |   `. \ | || |  |  (__ \_|  | |
| |   | |    | | | || |   '.___`-.   | |
| |  _| |___.' / | || |  |`\____) |  | |
| | |________.'  | || |  |_______.'  | |
| |              | || |              | |
| '--------------' || '--------------' |
 '----------------'  '----------------'

 .----------------.  .----------------.  .----------------.
| .--------------. || .--------------. || .--------------. |
| |      __      | || |   ______     | || |     ______   | |
| |     /  \     | || |  |_   _ \    | || |   .' ___  |  | |
| |    / /\ \    | || |    | |_) |   | || |  / .'   \_|  | |
| |   / ____ \   | || |    |  __'.   | || |  | |         | |
| | _/ /    \ \_ | || |   _| |__) |  | || |  \ `.___.'\  | |
| ||____|  |____|| || |  |_______/   | || |   `._____.'  | |
| |              | || |              | || |              | |
| '--------------' || '--------------' || '--------------' |
 '----------------'  '----------------'  '----------------'

 .----------------.  .----------------.  .----------------.  .----------------.
| .--------------. || .--------------. || .--------------. || .--------------. |
| |   ______     | || |     ____     | || |   _____      | || |     ____     | |
| |  |_   __ \   | || |   .'    `.   | || |  |_   _|     | || |   .'    `.   | |
| |    | |__) |  | || |  /  .--.  \  | || |    | |       | || |  /  .--.  \  | |
| |    |  ___/   | || |  | |    | |  | || |    | |   _   | || |  | |    | |  | |
| |   _| |_      | || |  \  `--'  /  | || |   _| |__/ |  | || |  \  `--'  /  | |
| |  |_____|     | || |   `.____.'   | || |  |________|  | || |   `.____.'   | |
| |              | || |              | || |              | || |              | |
| '--------------' || '--------------' || '--------------' || '--------------' |
 '----------------'  '----------------'  '----------------'  '----------------'


 ლ(╹◡╹ლ)
</pre>

--== Note ==--
各位同學大家好,
以下有3點對於CP1的資訊想要傳達給大家:
1.  最一開始的auc算法比較貼近acc算法,
    因此我有對此問題進行修改,完善auc算法,
    因此我預計會在今天(11/04) 19點行資料清
    空的動作,然後套用正確的auc算法,

2.  上傳的檔案已經不會是0跟1的數字,而
    是預測結果為1的機率,請各位參考這篇
    莊助教發的公告,資料夾格式也必須遵
    照一定的格式上傳(參考這篇的資料夾
    結構,主要就是直接對
    Competition_data壓縮),才會有分数。

3.  如果顯示資料上傳成功,可是在個人儀表板沒
    出現的話,就代表你上傳的資料不被接受,請
    檢查資料夾結構,資料夾名稱,或者内容。
    如果對於server還有任何建議,請各位來信指
    教。

已更新部分:
個人儀表板會以時間為基礎逆序排列,最新繳
交的結果會在最上面。
修正主要儀表板不能顯示所有組別的歷史最高
記錄的問題。

--==========--

<pre>
├── ABC_Binary_Classification_001.ipynb                         # 0.798371
├── ABC_Binary_Classification_002.ipynb                         # 0.802563 (3rd)
├── ABC_Binary_Classification_003.ipynb                         # 0.838294 (2nd)
├── ABC_Binary_Classification_004.ipynb                         # 0.840522 (1st)
└── README.txt
</pre>

Upload File:
  1. Prepare the ZIP file
  <pre>
  (.venv) CP1 % zip Chen\ Polo.zip Competition_data/*/*                                               
  adding: Competition_data/Dataset_1/X_test.csv (deflated 88%)
  adding: Competition_data/Dataset_1/X_train.csv (deflated 89%)
  ...
  adding: Competition_data/Dataset_9/y_predict.csv (deflated 77%)
  adding: Competition_data/Dataset_9/y_train.csv (deflated 78%)
  (.venv) CP1 %
  </pre>
