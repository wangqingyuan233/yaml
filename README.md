打开raw模式浏览以获得更好的阅读体验。

如你所见，这有“he”与“li”两个文件。
li相较于he，删除了所有选项，精简了节点与规则。
实际使用起来基本没有区别，如果你对Clash不是很了解，建议老老实实的用lite。
亲测可用在CFW、CFA 和 OpenClash。ClashX的话，因为我没有苹果电脑，不知道能不能用。

配置文件里各选项的介绍：
he：
    PROXY：EAST、WAST，选择用什么地方的节点，东西方各有特色，请根据自身实际使用体验选择。
        DIRECT：关闭访问国际互联网功能，但是保留去广告功能。
        REJECT：和DIRECT效果一样，为了排版好看放上去的（捂脸）。
    EAST：东方国家节点列表，日本与新加坡。自动切换节点，不可手动选择（见说明2）。
    WAST：西方国家节点列表，德国罗马尼亚。自动切换节点，不可手动选择（见说明2）。
    FISH：鱼，意为漏网之鱼，即“不在规则列表之内的”，比如https://www.speedtest.net/ 和一些小网站。可以选择让它们直连（DIRECT）或走代理（PROXY）。
li：
    PROXY：同“he”的“WAST”，不可选择。

一些说明：
    1。去广告，可拦截弹窗网页广告
    2。节点每5min进行一次ping，并切换到延迟最低的节点。
    3。节点列表每20min更新。规则列表每24h更新。
    4。由于2、3的存在，本配置文件实现了开箱即用。
    5。之所以只选用日本、新加坡、德国、罗马尼亚，只是因为这四个国家的线路亲测好用。

订阅链接：
https://raw.fastgit.org/wangqingyuan233/yaml/main/He.yaml
https://raw.fastgit.org/wangqingyuan233/yaml/main/Li.yaml

感谢：
https://github.com/Loyalsoldier/clash-rules
提供规则列表
