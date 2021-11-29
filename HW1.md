
Linux常用指令
  * 1.cd 前往其他目錄
  * 2.pwd 顯示目前所在目錄
  * 3.ls 目前目錄下的所有檔案
  * 4.cp 複製檔案
  * 5.cat 查看檔案
  * 6.mkdir 建立一個新目錄
  * 7.rmdir 刪除一個目錄
  * 8.rm 刪除檔案
 
Linux目錄權限 
  * chmod(change mode)664
  *    user     group     other  
  *  [r   w   x] [r   w   x] [r   w   x] 
  *   [4   2   0] [4   2   0] [4   0   0]

壓縮檔案
  * 1.節省空間
  * 2.壓縮檔案時可加密

壓縮率
  * 不一樣的壓縮程式會有不同的壓縮率，意即可以將檔案壓到多小。
  * 解壓縮需要的時間就是CPU的計算量。
  * 相容性問題，目前壓縮的檔案通常都能被普遍電腦解壓縮了。

Linux指令(壓縮)
  gzip
  * 1.gzip 壓縮 gzip Filename
  * 2.gunzip (gzip -d) 解壓縮 gunzip Filename.gz
 
  xz 
 * 1.xz -z 壓縮 xz -z FileName
 * 2.xz -d 解壓縮 xz -d FileName.xz
 
* tar.gz
 * 1.tar -zcvf 壓縮 FileName.tar.gz DirName
 * 2.tar -zxvf 解壓縮 FileName.tar.gz

Linux指令
 * head()取出前面幾行(預設10行)
 * tail()取出後面幾行(預設10行)
