目前討論的結果，以及進度 請 ＠鴻暘學長 ＠陳羿豐 看一下
目前我遇到顯示影像的問題是，因為我是全部blur完畢後才寫回檔案，感覺要有方法可以讀取正在執行的記憶體（就是正被loading到
host記憶體中去做高斯模糊的）
有什麼問題都歡迎提出來

主題如同上一篇，比較各個平台（pthread, OpenMP，CUDA（可以的話在多做一個 OpenCL好了））

然後，分工一下，我今天會來研究怎麼用 opencv 即時將執行的影像秀出來（鴻暘學長說這樣會在demo的時候比較有fu）
至於最後要統一跑結果的話，就在我的電腦跑好了（因為我這台還算足夠力，顯示卡是 GTX1070 + 32GB RAM）

分工：
鴻暘學長：pthread + 豐富報告的內容（例如可以跟我一起研究怎麼樣show 影像比較合適）
羿豐：OpenMP 或是 OpenCL （要兩個也可以）
我：寫出可以即時show 出影像的 py 和 CUDA

每個人都要自己寫自己的報告唷，分析一下執行情形，為什麼會有這樣的結果，更好的話題一下「如何針對這個平台（自己寫的那個平台）做更好的優化（例如 pthread 要變得更快等等）」

最後我們找個時間寫個結論

然後上台的時候就是
先講我們的主題（我）
為什麼要做這個（鴻暘）
平台一
平台二
平台三
平台四
結論 可以各自都講一點
播放demo video（我之後會用Adobe Premiere Pro CC 來讓它快轉，就不用等那麼久了）
