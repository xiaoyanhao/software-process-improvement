## install & start development
1.  在linux或mac系统下安装最新版 meteor
2.  进入文件根目录
3.  启动应用 meteor
4. 	在chrome浏览器地址栏输入 localhost:3000

### 完成了所有的功能点，附上几点说明：
1. 自定义UI界面
2. 用户注册有学(工)号的输入和身份的选择（教师还是学生）。
3. 对于作业，未过截止日期，日期字体显示绿色，已过截止日期，显示红色。作业列表的展示按照截止日期降序排序。
4. 对于老师，作业未过截止日期，显示编辑（可修改截止日期和具体要求）和删除的操作，已过截止日期，只显示批改操作。点击批改，显示此次作业所有同学提交的作业链接，可点击下载查阅，可统一评分。
5. 对于学生，作业未过截止日期，可点击查看详情，进入后有此次作业的具体要求，并且可以上传作业，默认只支持.zip文件。支持作业覆盖更新。