# sell

> sell app

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

1. .babelrc babel配置文件，因为代码都是es6，大部分浏览器不支持；"comments": false,表示转换后代码不生成注释
2. .editorconfig 编辑器配置文件，
    charset = utf-8     // 编码风格
    indent_style = space  // 缩进方式
    indent_size = 2  // 缩进大小
    end_of_line = lf  // 换行符风格
    insert_final_newline = true  // 当创建一个文件自动在文件末尾插入新行
    trim_trailing_whitespace = true  // 自动移除行尾多余空格
3. .eslintrc配置文件
    'arrow-parens': 0  // 允许箭头函数前面不写括号
4. 报错：Module build failed: Error: Cannot find module 'stylus',以前版本好像不要安装
    npm install stylus --save-dev
5. [Vue warn]: Error in render function: "TypeError: Cannot read property '0' of undefined"
    TypeError: Cannot read property '0' of undefined
    错误原因：没有写 ‘ v-if="seller.supports" ’
6. padding （上右下左）
7.  报错：Invalid handler for event "click": got undefined；可能原因：method没有加s;methods要data() 同级
8.  报错： - Component template should contain exactly one root element. If you are using v-if on multiple elements, use v-else-if to chain them instead.
    解决：最外层用一个div包起来
9.  import {formatDate}和import formatDate 的区别，第一个是export function 是一个方法,第二个是export default 是一个对象

最后，非常感谢黄轶老师(https://github.com/ustbhuangyi)，课程非常精彩，讲得非常细致，每句代码都解释，而且有自己的见解,让我受益匪浅，这门课对想对vue进行深入了解的人来说非常值得一看，
再次感谢


