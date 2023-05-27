<div align="center">
    <h1 align="center">
     学习通,泛雅，超星 作业一键完成（全新版本✨✨✨）
    </h1>
<p>该脚本仅用于爬虫技术的学习，如果你有好的功能或者想法，欢迎提交pr<a href=""></a></p>
</div>

![GitHub stars](https://img.shields.io/github/stars/aglorice/new_xxt.svg)
![python](https://img.shields.io/badge/python-3.10-blue)
![version](https://img.shields.io/badge/version-v0.2.3-blue)
![contributors](https://badgen.net/github/contributors/aglorice/new_xxt)
![prs](https://badgen.net/github/prs/aglorice/new_xxt)

## 1️⃣实现方法
- 从已完成该课程的作业的账号中获取作业答案
- 登录到自己的账号获取题目顺序，与之前的答案进行比较获取到正确的选项或者填空
- 构造表单数据发起请求完成提交作业


## 2️⃣功能支持列表
> 该脚本目前已在其他的学校的学习通上成功运行，如果你在使用的时候遇到了问题，欢迎提交[issue](https://github.com/aglorice/new_xxt/issues)😍😍😍
### 🚀已实现的功能
* [x] 查询所有的课程
* [x] 查询课程作业
* [x] 提取已完成的作业的答案
* [x] 答案保存为json格式
* [x] 一键完成作业
* [x] 支持选择题，填空题，多选题，简答题，论述题，判断题等
* [x] 查询所有课程的未做作业
* [x] 查看作业的成绩以及完成状态
* [x] 获取个人信息
### 🛸打算实现的功能
* [ ] 多用户批量完成作业
* [ ] 提取一个课程所有的作业
* [ ] 实现扫码登录
## 目前对题型支持

| 题型  | 完成状态     |
|-----|----------|
| 单选题 | ✅支持      |
| 多选题 | ✅支持      |
| 判断题 | ✅支持      |
| 简答题 | ✅支持（未测试） |
| 填空题 | ✅支持      |
| 论述题 | ✅支持（未测试） |
| 其他  | ✅支持（未测试） |

## 3️⃣使用方法
#### 1.克隆到本地
```bash
git clone https://github.com/aglorice/new_xxt.git
```

#### 2.进入目录
```bash
cd new_xxt
```
#### 3.安装依赖
```bash
pip install -r requirements.txt
```
#### 4.运行`main.py`
```bash
python main.py
```
#### 注意：如果在运行的时候提示无效参数，直接再次运行一次就可以了。对于需要重做的作业，你可以先在手机或电脑上点击重做，然后再回到该脚本，作业会显示未交的状态，这个时候就可以使用脚本正常运行。

`answers/27835863.json`
```json
{
  "27835863": [
    {
      "id": "163497980",
      "title": "1.(单选题)在数据结构中，与所使用的计算机无关的是数据的（）结构。",
      "type": "单选题",
      "answer": "A",
      "option": [
        "A. 逻辑",
        "B. 存储",
        "C. 逻辑和存储",
        "D. 物理"
      ]
    },
    {
      "id": "163498096",
      "title": "2.(单选题)算法分析的两个主要方面是（）。",
      "type": "单选题",
      "answer": "A",
      "option": [
        "A. 空间复杂度和时间复杂度",
        "B. 正确性和简明性",
        "C. 可读性和文档性",
        "D. 数据复杂性和程序复杂性"
      ]
    },
    ...
  ]
}
```

终端运行结果:
![](img/uTools_1684916919281.png)
## 4️⃣注意事项
- 仓库发布的`new_xxt`项目中涉及的任何脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。
- 本项目遵循GPL-3.0 License协议，如果本特别声明与GPL-3.0 License协议有冲突之处，以本特别声明为准。
- 以任何方式查看此项目的人或直接或间接使用`new_xxt`项目的任何脚本的使用者都应仔细阅读此声明。`aglorice` 保留随时更改或补充此免责声明的权利。一旦使用并复制了任何相关脚本或`new_xxt`项目，则视为您已接受此免责声明。

**最后注意一下，作业还是得自己做，这种行为是不对得😁😁😁**

### Star History

[![Star History Chart](https://api.star-history.com/svg?repos=aglorice/new_xxt&type=Date)](https://star-history.com/#aglorice/new_xxt&Date)
