# BUG
记录因为粗心而出的bug, 以此勉励,以后不再犯错.
#### 1. for循环里continue错误的使用成return.
#### 2. 在调用方法的时候因为一些相似的单词而调用错误, 造成功能上的出现逻辑性bug.
#### 3. 在对redis存储的时候,要提前写debug看是否能够正确的存取, 以免造成存取为空.
#### 4. 为了避免逻辑混乱, 在写代码之前, 要先理清楚功能. 通过伪代码和注释搭建逻辑框架, 同时, 在看别人的代码的时候, 要学会站在第三者的角度上, 逻辑不能被带偏. 要学会拆分功能模块, 方便在特定的地方插入.
#### 5. 在使用switch case的时候, 要习惯加default, 避免因其它条件的出现造成bug而挂掉服务器.
