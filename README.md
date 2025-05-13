//策略說明:<br/>
//假設當 CCI 值高於 +100 時，市場被視為超買，可能會出現價格回調，當 CCI 值低於 -100 時，市場被視為超賣，可能會出現價格反彈。<br/>
//快慢線離開CCI正負一百以外，又回來CCI正負一百以內，發生金叉死叉，就做單，因為是搶乖離反彈，所以1倍art停損停利。<br/>
//如果打到對向的CCI會提前出場(代表方向可能改變所以先提早出場)。<br/>
//<br/>
//<br/>
//參數:<br/>
//CCI 18 (快線)<br/>
//<br/>
//CCI 54 (慢線)<br/>
//<br/>
//ATR 14天  停損1倍<br/>





## Tips
程式歸宿:<br/>
classpack.mqh >>> Include 第一層<br/>
策略程式 >>>Exprets 第一層<br/>



如果查資料時https://www.mql5.com被封掉，到C:\Windows\System32\drivers\etc，去找到hosts把127.0.0.1 www.mql5.com刪掉。<br/>
