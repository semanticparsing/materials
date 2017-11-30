## Grammar for NL2LF

### 1. 通用符号
* “<>”：非终结符，语法规则的左侧，可以作为term出现在右侧，如：<code><sing_a_song></code>。
* “()”：匹配区域/组（group），例如：<code>我要看(电视|小说)</code>，将<code>(电视|小说)</code>视为一个组。
* “[]”：表示其所包覆的内容是可选的，亦即可忽略，如<code>[给我]唱歌</code>，可以匹配“给我唱歌”和“唱歌”两种说法。
* “|”：逻辑符号“或”，例如：<code>电视|电影</code>，表示电视或电影。
  
  

### 参考资料
* [科大讯飞abnf文法规范](http://open.linglongtech.com/openweb/static/download/ABNF_open1.1.pdf)
* [欧拉蜜OSL语法描述语言](https://cn.olami.ai/wiki/?mp=osl&content=osl1.html)
* [Augmented BNF for Syntax Specifications: ABNF](http://www.ietf.org/rfc/rfc2234.txt)
