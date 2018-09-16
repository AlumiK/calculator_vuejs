# 简单计算器

利用 [Vue.js](https://vuejs.org/) 框架制作的一个简单计算器。

演示网站 [https://calculator.ret.red](https://calculator.ret.red)

## 说明

1. 要先 **点击答案区域使其获得焦点** 才能采用键盘输入。此时右上角会出现 “KEYBOARD ON” 字样。按键如下表。

    | 功能  | 按键                         |
    |------|-----------------------------|
    | C/AC | `c` / `C`                   |
    | +/-  | `~` (shift+&#96;)           |
    | %    | `%` (shift+5)               |
    | +    | `+` / `NUM+`                |
    | -    | `-` / `NUM-`                |
    | ×    | `*` (shift+8) / `NUM*`      |
    | ÷    | `/` / `NUM/`                |
    | =    | `Enter` / `NUM Enter` / `=` |
    | 0~9  | `0`\~`9` / `NUM0`\~`NUM9`   |
    | .    | `.` / `NUM.`                |

2. 按一下清除键是清除当步，再按一下清除键是清除全部。

3. 在 Chrome/Edge 浏览器中测试通过，在 IE 中无法正常显示，Safari 未测试。在屏幕宽度极小（小于7寸）的情况下会出现轻微的按键显示错位。与屏幕宽度有关而与窗口大小无关，原因不明。

4. 对于浮点数计算的精度问题，我自创了一个方法进行解决。不确定是不是最优解决方法。

5. 为了不损失数据，允许显示数据长度超出显示框范围。

6. 网站在 Ubuntu 18.04 + Node.js 10.7.0 + npm 6.1.0 环境下测试通过。

## 运行方法

1. 安装依赖。

    ```
    npm install
    ```

2. 在 localhost:8080 启动开发服务器。

    ```
    npm run dev
    ```

更多信息请参阅 [指引](http://vuejs-templates.github.io/webpack/) 和 [vue-loader 文档](http://vuejs.github.io/vue-loader)。
