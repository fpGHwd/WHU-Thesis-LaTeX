1.适用 TeX Live 2015 软件环境. 安装 TeX Live 2015 之后需要立即更新.  
  TeX Live 安装及更新方法，参见：http://aff.whu.edu.cn/huangzh/

2.使用 XeLaTeX 编译.

3.主文档是 MasterTemplate.tex . 文档类型 3 种

   \documentclass{WHUMaster}              % 硕士论文 
   \documentclass[forprint]{WHUMaster}    % 硕士论文打印版 
   \documentclass[forlib]{WHUMaster}      % 硕士论文图书馆提交版 

   2016年 4 月更新: 专业硕士毕业论文, 请在上述情形另外加上选项 smd. 
   专业硕士毕业论文的封面稍有不同(中英文封面), 页眉也顺势改变了.

4.图片请放在 figures 文件夹.

5.文件夹 includefile 存放的是英文封面、中英文摘要、致谢等等正文以外的部分。
  请直接在这些文件中填写相关内容,不要改变文件的位置.

6.更多使用说明请参看 MasterTemplate-BACK.pdf , 以及源文件 MasterTemplate.tex 里的注释说明.

7.模板下载更新地址:
  http://aff.whu.edu.cn/huangzh/ 
