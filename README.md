# 使用jieba斷詞並建立反向索引
Information Retrival作業
建立反向索引以方便後續使用

> **Initialize**  
![image](https://user-images.githubusercontent.com/121109511/211741918-059cba3b-5c9b-4583-83f1-855081e1635d.png)  
資料使用5萬篇的wiki文章

> **下載詞庫**  
![image](https://user-images.githubusercontent.com/121109511/211742283-7dabdfa3-2e1e-4fda-ace5-b33472b6466f.png)  
使用基本的dict.txt  
若是覺得不夠可以再透過userdict增加詞彙  
~~其實我發現新的詞彙直接加到dict.txt就好了，幹嘛還多用userdict~~  
>![image](https://user-images.githubusercontent.com/121109511/211743524-b1ca61fc-324d-4a91-b06e-2ba20b5858b7.png)  
在增加詞彙時還有2個參數  
數字代表詞頻 英文代表詞性 [詳細可看](https://github.com/fxsjy/jieba)

> **使用jieba進行斷詞**  
![image](https://user-images.githubusercontent.com/121109511/211745193-990bdc70-e02c-4e91-862f-5a2e16843a61.png)

>![image](https://user-images.githubusercontent.com/121109511/211745510-6546102a-ce64-4e6d-81d2-2acdd96869a6.png)  
由於單一詞彙可能會單一文章多次提及  
所以需要去除重複的文章編號

>印出需要的反向索引  
![image](https://user-images.githubusercontent.com/121109511/211746010-a6d24e38-21a9-4cf6-b6e1-e7d29dd4b916.png)








