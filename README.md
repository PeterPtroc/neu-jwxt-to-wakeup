# NEU JWXT 课表导出

这是一个简单的 js 脚本，用于从新版东北大学教务系统导出课程表，生成能导入 WakeUp 课程表的 CSV 文件。

本项目受 [CreamPig233/neu_wisedu2wakeup](https://github.com/CreamPig233/neu_wisedu2wakeup) 项目的启发，将其 Python 逻辑移植为更为轻量的浏览器控制台脚本，无需安装 Python 环境，直接在浏览器中运行即可。


## 使用方法

1.  登录教务系统
    使用电脑浏览器（Chrome/Edge等）访问并登录 [东北大学本科教务管理系统](https://jwxt.neu.edu.cn/)。

2.  打开控制台
    在教务系统页面，按下键盘上的 `F12` 键，然后切换到 Console (控制台) 标签页。

3.  运行脚本
    复制 [`extract_schedule.js`](extract_schedule.js) 文件中的所有代码，粘贴到控制台中，回车运行。

4.  导入课表
    脚本运行成功后会自动下载一个 `schedule_xxxx-xxxx-x.csv` 文件。
    *   将该文件发送到手机。
    *   打开 **WakeUp 课程表** APP。
    *   进入设置 -> 导入/导出 -> 从 CSV 文件导入 -> 选择文件即可。
