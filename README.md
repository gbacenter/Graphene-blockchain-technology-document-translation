# Graphene-blockchain-technology-document-translation
石墨烯技术文档翻译，包括但不限于how.bitshares.works, dev.bitshares.works, BSIP等内容
# Graphene-blockchain-technology-document-translation
石墨烯技术文档翻译，包括但不限于how.bitshares.works, dev.bitshares.works, BSIP等内容



高质量的译者直接给予编辑权限，协助发起人管理项目。与发起人一起成为翻译的组织者。

普通的译者领取任务 fork，翻译完后 push request。翻译组织者审校提交的译文，如果通过则 merge。

翻译
翻译的组织者在项目 wiki 中明确翻译规范 #1 与术语表，以便统一翻译质量。

具体的翻译，或者将项目 clone 到本地。适合于需要预览网站的情况，比如 Jekyll。不过，在国内糟糕的网络下，如果项目文件很大，不一定能成功下载到本地。要求使用专业的编辑器，比如 Sublime Text 等编辑器，避免给文件的缩进、编码等带来问题。在提交的之前先 git status 看一下修改情况，如果全部是红色，通常说明自己哪里操作出现了问题，除非是完全更新了那个文件。

或者在线翻译，不用下载什么文件，比较适合简单的操作，基本上能满足需求。如果觉得在线编辑器不方便，可以把内容复制到自己常用的文本编辑器内。同样的，请使用专业的编辑器，友情提醒：在按提交按钮之前，最好复制一次文本框内的内容，避免因网络问题而丢失编辑内容。

更新翻译
每次更新新开一个 issue。

在 issue 中给出上次翻译的 commit sha，以及这次的 commit sha（通常是最新的一次提交）。比较两个 commit 得到 diff。

或者在本地比较，事先将原项目（注意不是翻译项目）克隆到本地，切换到目标分支（通常是 master)，然后：

git diff <commit> <commit> > patch
上述命令生成一个补丁文件，用编辑器打开它，会高亮。然后一项项的修改。

组织者可以在 issue 里面按文件分派任务，同时最好附上完成日期。领取任务的译者，自己比较待更新的文件：

git diff <commit> <commit> -- <path> > patch
编辑更新之后提交。注意不要有遗漏，提交前仔细检查一遍，避免给他人麻烦。

或者在 Github 上比较，见帮助 Comparing commits across time。

##校译
采用交叉检查法，每个翻译志愿者在完成自己的任务之后，需要完成同等任务量的其他译者的校译工作。

##格式
请使用markdown编辑，具体编辑格式按照英文页面

##工作量说明
工作量按照XX人民币每千字计算，其中字数指英文字数，空格、标点符号、代码等除外

##统计字数工具
任务领取页面的字数是参考英文字数，实际字数可根据如下工具统计。如有差异，请将实际字数告知小希。
统计字数：https://wordcounter.net/
统计网页字数：https://wordcounter.net/website-word-count
