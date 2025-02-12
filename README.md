用python让你的微信消费更可观和可控


BASH# === 你的代码魔法书 ===
# 安装核心工具包（Python版瑞士军刀）
pip install pandas matplotlib seaborn   # 数据分析三件套
pip install jieba wordcloud chardet     # 中文词云黑科技
pip install tk                          # 文件选择弹窗工具

# === 咒语背后的秘密 ===
# Windows玩家请用管理员模式运行（右键点终端的正确姿势）
# Mac/Linux用户可能在命令前要加sudo（比如sudo pip install...）

运行准备指南：

第一步：Python环境
# 一次性搞定所有核心调料（建议先升级你的"锅铲"pip）
python -m pip install --upgrade pip
python -m pip install pandas matplotlib seaborn jieba wordcloud chardet tk
//小贴士：如果安装卡住，可以试试加上清华镜像源 -i https://pypi.tuna.tsinghua.edu.cn/simple

第二步:中文支持
(字体彩蛋
请确保系统有微软雅黑字体（Windows自带，Mac建议更纱黑体） 🤔 如果看到满屏□□□，请把代码里的msyh.ttc改成你的字体路径，就像给机器人配眼镜！)
# 安装中文字体渲染神器（Linux用户需要）
sudo apt-get install python3-tk  # 🐧 给企鹅系统装个图形界面小推车

第三步：微信账单
"获取新鲜食材",下载好解压后不用动就行了
打开微信 → 我 → 服务 → 钱包 → 账单 → 常见问题 → 下载账单 → 选CSV格式 🚨 注意：要选带这些"食材标签"的账单：
交易时间 | 交易类型 | 交易对方 | 商品 | 收/支 | 金额(元)

 第四步：运行代码
 # 优雅地启动你的消费分析火箭
python WeChat_Bill_Analysis.py

遇到问题时的"求生指南"：
·看到ModuleNotFoundError → 漏装调料了，快查安装命令
·出现火星文 → 给代码换个字体"眼镜"（修改font_path参数）
·程序装死 → 检查是不是选了外卖图片当账单（要选.csv文件啊亲！）


**次代码有很多能够简单修改的地方,"category_rules"的分类、最后建议等等,总之这些都无关紧要,图像化的展示已经满足一个较好的要求了**


类别            必备物品                                 特别提醒
核心装备        Python 3.6+                     别用上古版本的Python，会哭的！
秘密武器        支持图形界面的电脑               拒绝黑屏操作，我们要看漂亮图表！
调料包          pandas+matplotlib全家桶         数据分析界的"老干妈"
灵魂配料        微信官方CSV账单                  在手机微信上导出,电脑上下载


![9709307c886ba47f273c8d086ea5587-1024x782](https://github.com/user-attachments/assets/f2d988e7-b534-4cdf-a2f0-0df40607cb5e)



下面是微信导出邮件的步骤:(从上往下按顺序)
第一步:左上角的"账单"
第二步:"常见问题"
第三步:下载账单
第四步:用于个人对账
第五步:选择要下载的时间段
第六步:下载并解压,ok
![0e9b34826f13dd79e5cde9550c0bfd4](https://github.com/user-attachments/assets/f0d2ed38-705f-4945-8f79-4421fe2c588c)
![6f93070f277a9a5b85eb00d3f34134c](https://github.com/user-attachments/assets/7639ed67-d526-4120-9aad-b22307aa0559)
![f390a6b0bc79d8a20d362d55094e90a](https://github.com/user-attachments/assets/fd30134c-8e77-45a2-a063-9dfcfe7d1928)
![d4f787014363a919d8421569b1557a8](https://github.com/user-attachments/assets/6277d05a-d224-4302-82a7-a4fc0accb9ff)
![b1d1a85a76aac55800290f5b7900cf9](https://github.com/user-attachments/assets/f08490fa-9002-4522-ad8f-945e6455c761)
![4ac7071f78faf0cfceb3da3e1d15729](https://github.com/user-attachments/assets/3d39a68f-9806-4071-9763-fe303380fdb8)

