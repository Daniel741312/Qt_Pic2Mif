这是我拿Qt做的第一个小工程, 主要是配置opencv的库费了一些时间, 如果你想复现一下这个小工程的话, 我的配置环境如下, 别再像我一样走弯路了:

- QT5.14.2, 使用MinGW64位编译器;
- 对应的opencv库我是直接从github上clone下来的:https://github.com/nczyw/opencv4_4_contrib4_4
- 记得把opencv库的bin目录放到系统环境变量里, 并重启电脑;



这个东西可能还有很多小bugs, 通过一些小的改动应该能de掉:

1. 弹窗的大小固定死了, 如果显示器缩放变化的话可能造成显示效果变化;
2. 不知道为什么有的图片读不进来;
3. 界面还很丑, 审美极差;
4. 代码比较屎, 有的地方可能绕弯了, 没办法, 刚学没几天;
5. mif文件的hex数据字母是小写的, 不知道可不可以;

另外我暂时做不出来release版, 因为我不知道怎么把dll库封装到工程自己的文件夹里, 估计换一台没有配置相关环境变量的电脑就不能运行了;



总之, 这个东西花了我一天多的时间, 暂时到此为止吧, 继续学习了;

