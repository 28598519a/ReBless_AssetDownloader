# ReBless_AssetDownloader
用於下載所有ReBless Zwei的資源文件，而不用實際去玩 (Nutaku版)<br>
***This program will only download hotfix file, not include files in apk.**

由於資源是動態下載的，意思是如果要正常取得所有的話，必須要遊戲畢業才行

我猜url產生方式一部分是寫在lua裡，因為我在IDA Pro裡分析都指向lua，但lua是加密的，要分析怎麼解密又很懶，最後url產生是用猜的猜出來的，猜的過程又猜錯過一次，導致只抓到2/3資源，結果又跑回遊戲玩一邊看封包，都練到CP 3055k了...還好最後有猜出來

Sample:

![](https://user-images.githubusercontent.com/33422418/215297275-9b8bb32d-e913-4f50-a044-1d3bff3fa45a.png)
