## 跟你朋友介紹 Git

首先要版本控制時先移置要先移至 gitflow的檔案
- git init 先將版本初始化
- git status 檢視檔案是否有加入進來
- git add . 將全部檔案加入 or git add 檔案名稱
- git commit -m”想附註的話”  更新版本
- git log 檢視版本更新紀錄
如果他之後有更新檔案，處存後可以一直重複 git commit -am””，的動作，想要檢視之前的更新的話可以先輸入git log，查看前幾次的版本代號，並使用 vim 版本代號 即可檢閱

上面的檔案更新與commit完成的話，請他註冊github並建立一個repository
，點選clone or download 按鍵，複製裡面的連結
- git remote add origin 連結 在github建立一個資料夾與電腦檔案連結
- git push -u origin master 一個叫master的檔案建好了
-	
之後如果檔案有做任何修改
- git branch “latest version” 建一個叫latest version 的檔案
- git checkout 移至新的branch
- git push origin “latest version” 將新的branch 推送到網頁上


