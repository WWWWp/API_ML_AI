## 框架
Target release|2018/12
--|--
Epic|&nbsp;
**Document status**|&nbsp;
**Document owner**|<a href="https://www.github.com/WWWWp">王伟鸿</a>
**Designer**|<a href="https://www.github.com/WWWWp">王伟鸿</a>
**Developer**|&nbsp;
**QA**|&nbsp;

## 目录

## Goals
当前智能手机的出现大大降低了人们交流的局限性，然而当人们遇到不可避免的问题时，即使是视频聊天也无法解决（不会普通话的人和不会当地方言的人遇到一起）。潮汕方言输入法以潮汕话为例子，一方面能够有效地解决最基本的交流问题，另一方面也方便让人学习普通话。
## Background and strategic fit
截至2015年，中国70%人口具备普通话应用能力，尚有约4亿人只局限于听懂的单向交流，而还有一部分人（不包含刚出生婴儿）对普通话并不熟悉，甚至不会说普通话。
## Assumptions
用户在使用手机的输入法时，手机会自动识别接收到的音频，并转换成相对应的文字。
## Requirements
### User Portrait
name|性别|职业|age|Marriage|location|children
--|--|--|--|--|--|--
王阿姨|女|家庭妇女|53|已婚|潮汕|2男2女


Use of electronic equipment|
:--|
2015年开始接触智能触屏手机，2015年前一直使用传统翻盖手机，平时使用手机进行打电话和微信聊天，聊天形式几乎是语音输入和语音通话，不曾使用过电脑。|

### User Usage Scenarios
&nbsp;|User|Story|Importance|Notes
--|:--:|:--:|:--:|:--:
1|会讲潮汕话但不会讲普通话的人|工作日时，王阿姨微信收到小儿子老师发的文字，老师的电访让王阿姨不知所措，她看不懂，不知道儿子在学校是否闯祸又或是受到表扬，于是王阿姨将这段文字通过输入法转换成她听得懂的潮汕话，得知儿子在学校没做作业。|Important|&nbsp;
2|会讲普通话但听不懂潮汕话的人|李老师是一位尽职尽责的人民教师，而小王在学校经常没写作业，李老师通过微信发了一段语音给王阿姨，但是他知道王阿姨听不懂普通话 ，于是机智的李老师通过输入法，将他想说的话转换成王阿姨听得懂的潮汕话，成功地让王阿姨明白了此次家访的目的。|Important|&nbsp;

## User intercaion and design
- **输入**：语音（潮汕话，普通话），文字
- **输出**：相对应文字、语音
### 产品流程图