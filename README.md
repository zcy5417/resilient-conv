# -
PGD attack以后：
0.2646 0.1766 0.1475 0.1254

不用弹性模子：
好像是 0.0008 0.0005 0.0003 0.0003

但是用了advesarial training以后都是0.4几，好像弹性模子没起到作用。
总结可能弹性模子有以下问题：
1、可能A会变，B、C之间的差异用它们和A的距离来比较不合适
2、所谓的距离不一定是自己定义的距离，可能是学习出来的某个距离
3、这种迭代优化都不一定能保证起到啥作用