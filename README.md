# HUAWEI-DIGIX-AgeGroup
2019 HUAWEI DIGIX Nurbs Solutions

#### Notes:
###### RAdam,AdamW,Lookahead,CycLearn在/snake/11. lstm-atten中
###### 原生的adam与Lookahead配合较好，效果比较为adam<AdamW<RAdam<RAdam + Lookahead<AdamW + Lookahead<adam + lookahead，效率是纯AdamW最快
###### Graph特征构建在/snake/3. Graph Feature中，有一些特征较慢，可以注释掉，我们选择的建图为二分图建图方法

