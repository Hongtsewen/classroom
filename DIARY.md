# DIARY

to track my works and thoughts

### @-2022/09/05(月) -
- 約東港李明祥談房地事。
- 約呂森民龍舟隊教練。

### @-2022/09/04(日)林口-颱風 
- ubuntu20.04安裝deb-get 參考[Install Third Party DEB Packages With 'deb get'](https://www.youtube.com/watch?v=xkdTMIp3PTg) 用$deb-get help 可看指令參數。在github上找wimpysworld/deb-get 可看到他public的整個project。看他們怎樣開發opensource程式，在github上工作與分享。
- ubuntu20.04安裝OpenShot [How to Install OpenShot Video Editor on Ubuntu 22.04 LTS Jammy](https://www.how2shout.com/linux/how-to-install-openshot-video-editor-on-ubuntu-22-04-lts-jammy/)
- ubuntu20.04安裝OBS studio錄影軟體。看教學影片 [OBS必學第一招-你會使用OBS錄製教學影片嗎?](https://www.youtube.com/watch?v=t5SgWlzjYu0)
- tweetter的用法參考 
<pre>不過一篇只能280字元，中文最多140字，一次可以貼四張圖，每天可以發1000篇推文，貼文不能編輯，創辦人認為最好的編輯就是重發。(雖然之後馬斯克搞不好會新增這個功能)
1. 長按右下角「+」可以推文、可以配GIF推文  、也可以開語音聊天室。
2.可以用「#」來HASHTAG，很有用，雖然可以放好幾個，但推特使用者習慣只放一個HASHTAG，不像IG習慣標到飽。
Q：RT是什麼？🤔
RT = Retweet = 轉推，可以把原推原封不動分享到自己的TL上
Q：看到好棒的推文，怎麼辦？🥰
設書籤，改天看，TL一滑過就無法恢復，推文一期一會，錯過就沒了。</pre>
- 關於srv程式的檢討
<details>
	<summary>找出並查看srv程式的功能</summary>
	1.htw@htw-B15:~$ find www/lfh -name "*srv*.php" 找出有寫srv的程式
	2.逐一去看這程式的功能
	localhost/lfh/test/htw_srv.php  //srv主程式 <br>
	localhost/lfh/test/htw_srv_mthckemd.php  核對SRV和EMD的人事資料<br>
	localhost/lfh/test/htw_srv_autorenew.php<br>
	localhost/lfh/test/htw_srv_autorenew.php.php //從 SRV 取出 202208 月份資料了....<br>
	insert error:<br>
	localhost/lfh/test/htw_srv_chkemd2srv.php //用EMD查查某月的SRV有無資料<br>
	localhost/lfh/ds/srvmrps.php  //首頁 >統計作業 >BIOS-業務月營績效統計<br>
	localhost/lfh/ds/newsrv.php   //首頁 >銷貨作業 >建立每月SRV<br>
</details>

- 在github的classroom上，新建這個DIARY.md日記檔案

### @-2022/09/03(土)林口-颱風 
- 花は咲く「わたしは何を残しただろう」。我們都在這塊地上走過，大多數的人無聲無息，有少數人留下了一些痕跡。「私たちは皆この野原を歩きましたが、ほとんどの人は黙って歩き、何人かは足跡を残しました。」
- 關於error log的等級：trace debug info warn error fatal <br> 
[When to use the different log levels](https://stackoverflow.com/questions/2031163/when-to-use-the-different-log-levels/2031209#2031209)
- 我註冊了[Stack Overflow](https://zh.m.wikipedia.org/zh-tw/Stack_Overflow) 帳號了(用gmail帳號)。


