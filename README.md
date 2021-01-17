# 107370708
1.輸入並執行args.malware_paths 、args.benignware_paths 、args.evaluate
2.從 malware_paths 和 benignware_paths 內的檔案取得資料
3.使用隨機森林決策樹model來進行訓練
4.得出曲線圖
補充<un_completedetector.sh-這只程序是驅動的主程序，驅動的是completedetector.py
complete_detector.py 中主要用到的套件是sklearn的RandomForestClassifier及FeatureHasher
透過RandomForestClassifier及FeatureHasher提取特徵並使用機器學習來訓練題曲惡意程式的特徵
執行run_completedetector.sh-程序，添加ROC曲線>
                     
