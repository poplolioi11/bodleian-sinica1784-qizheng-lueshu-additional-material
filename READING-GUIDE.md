# 閱讀指南

book.json內每一頁有官方canvas/image URL、母圖到半面的crop/hash映射；source_face_sha256是確定性半裁PNG，初錄者primary所見為整幅1000×1164母圖。高解析ROI依實際ref另列，並非本包影像附件。

book.txt是按來源單元順序的忠實輸出，不能直接假定小字位於欄尾。四個序文小余及其他小字保留parent/anchors/reading_position；READABLE-TEXT只對已接受且定位吻合的來源點插入明示小註，其餘列未定清單。兩個舊small-note錨點照存，未將原先非精確位置改稱精確。圖號及圖內字不等同圖像，需依官方原件核對。

碼位offset從0起算、end不含，沒有NFC/NFKC。序列化碼點數不是印字準確率或實際可辨字數，未知長度標記不當一字。
