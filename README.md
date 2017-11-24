# map-area-rwd
響應式影像地圖

感應區域根據現有圖片大小伸縮，使用規則如下：

1. 建立一個類別 MarNode，方法存在類別原型 MarNode.prototype.mar
2. new 一個 MarNode 物件時，需傳入一個圖片節點
3. 必須使用 window.onload，等圖片加載完成
4. no jQuery

範例：

    window.onload = function(){
		var box = new HerlNode(document.querySelector('.box')); //建立一個 HerlNode 物件

		box.mar();
	}
