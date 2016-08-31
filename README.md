# <h3>黑白棋 课程设计 + AI</h3>
#<h4>准备</h4>
	编程语言：C++
	编译环境：VS2015 + EasyX
	编译平台：Windows

#<h4>介绍</h4>
	黑白棋，又叫翻转棋（Reversi）、奥赛罗棋（Othello）、苹果棋或反棋（Anti reversi）。
	游戏通过相互翻转对方的棋子，最后以棋盘上谁的棋子多来判断胜负。
	它的游戏规则简单，因此上手很容易，但是它的变化又非常复杂。
	有一种说法是：只需要几分钟学会它，却需要一生的时间去精通它。
    
#<h5>单人模式</h5>
	玩家执黑棋
	提供简单、中等、困难AI。
	其中简单AI返回可转化棋子最大位置，
	中等以及困难AI进行极大极小博弈树搜索，返回搜索指定层数之后的最优解。
    
#<h5>双人模式</h5>
	黑棋为先，两人交替出棋
    
#<h5>联机对战</h5>
	通过Socket编程实现，两人必须处于同一个局域网下，一人创建，一人连接，
	连接成功后进入游戏，对弈开始，其中服务端为白棋，客户端为黑棋，黑棋为先。
    
#<h5>观战模式</h5>
	电脑 Middle 对战电脑 Difficult
    
#<h5>游戏介绍</h5>
		"五步之内，百人不当",
		"十年磨剑，一孤侠道",
		"千里挥戈，万众俯首",
		"四海江湖，百世王道",
		"每一个来到墨问的人 都会面临选择",
		"天下皆白 唯我独黑",
		"民生涂炭 奈之若何",
		"墨门绝术 克而不攻",
		"八横八纵 兼爱平生",
		"墨家主张非攻兼爱 要获得胜利",
		"并非一定要通过杀戮 攻城为下 攻心为上",
		"墨攻棋局 棋子虽然不多",
		"但是敌我双方的转化 却是千变万化 步步惊心",
		
#<h5>操作说明</h5>
		"王道之室中 不是普通的棋局",
		"而是根据本门绝学精髓设计而成的墨攻棋阵",
		"墨攻棋阵与围棋明显的不同就是",
		"墨攻棋局中不会有任何棋子被杀死",
		"当一方的棋子被另一方棋子前后围堵",
		"那这些棋子就转化成另一方",
		"当然 如果这些棋子又被围堵时",
		"还可以再次转化",
		"最后六十四格棋盘布满时就看双方谁的棋子数量多",
		"哪一方就获胜",
		"墨攻棋局 每一次落子必须要形成转换",
		"如果对方没有可被转换的棋子时",
		"这种情况 本方就只能放弃这一轮出手",
		"能够把对手逼入这种困境 就叫作破阵 是最厉害的招数",
		
#<h5>关于</h5>
		"感觉主动进入这个页面的人都是关心 千千 的人哟！",
		"怎么说千千也都是新人那！",
		"懵懂无知感觉时间过得真的好快，不知不觉就要度过大一啦~",
		"只是不想在考试之后看到自己会挂科 o(╯□╰)o",
		"每次更换头像都会找很久很久惹",
		"千千的梦想呢？不会说出来的~ 因为自己也不知道",
		"想让身边的每个人开心~ 毕竟他们也曾经让我开心过~",
		"#More 哒哒……",
		"千千是我啦！不是千玺~",
		"毕竟我是让班里唯一一个喜欢千玺的女孩更换称呼的人惹~",
		"当然继续叫千千也没事啦~ 我不会介意的╮(╯▽╰)╭[害羞]  @蛋蛋",
		"千千是个90后，噫~",
		"不能这么说啦，98后~",
		"千千的生日是新年的第四天 n(*≧▽≦*)n",
		"对我说元旦快乐的同时也可以Happy  birthday  to  me!",
		
#<h5>退出游戏</h5>
	exit(0);
    
#<h4>关于</h4>
	作者：千千
	版本：v1.2
	分支：大一C语言课程设计
	说明：游戏中部分界面可按ESC退出，使用过程中如若发现Bug，请不要忘记在这里留言哦！
	网站：https://www.dreamwings.cn/

#<h5>已知Bug：<h5>
	1、ESC必须通过鼠标配合才可以正常退出
	2、可能会出现创建服务器时候 连接失败 的情况

#<h5>已修复Bug：<h5>
在某方无子可走的情况下“当前执子”显示出现错误 (感谢 <a href='http://t.qq.com/wyywyy520899'>@王余阳</a>)
		
# <h4>链接 <a href="https://www.dreamwings.cn/reversi/3013.html">黑白棋中的AI</a></h4>
