![1](https://i.loli.net/2020/12/29/q5ZIRXPYhHEbmKO.jpg)

<center><span style="color:red">区块链技术与应用课程设计</span></center>

### 题目：<u>基于区块链的高校学生成绩管理系统</u>

### 学院：<u>区块链学院</u>

### 专业：<u>软件工程（区块链方向）</u>

### 姓名：<u>曾尉斌</u>

### 学号：<u>2019000101091</u>

### 指导老师：<u>江海</u>

### 完成时间：<u>2020年1月8日</u>

---

<center>摘要</center>

> **中共中央政治局就区块链技术发展现状和趋势进行第十八次集体学习。中共中央总书记习近平在主持学习时强调，区块链技术的集成应用在新的技术革新和产业变革中起着重要作用。我们要把区块链作为核心技术自主创新的重要突破口，明确主攻方向，加大投入力度，着力攻克一批关键核心技术，加快推动区块链技术和产业创新发展。**[1]

**关键词：区块链技术；创新**

# 目录

### 摘要

### 第一节 需求分析

#### 1.1社会痛点

​	2019年2月8日，翟天临因在直播中回答网友提问时，不知知网为何物，导致他的北大博士学位真实性受到质疑，并由此引发了一场全社会对学术造假的深刻反思。教育作为社会阶层流动的重要通道，其公平性关乎到的不仅仅是个人的荣誉，还有社会的公正，从古代科举到现在的各种考试，无不备受重视。

​	近些年来，我们的教育在规模和质量上取得了突飞猛进的成果，但是在“开放”和“公信”方面却依然备受质疑。其实，开放是教育的基本理念，知识的公共性决定了教育的开放性。教育的开放意味着教育服务主体的多样化，打通各个教育机构之间的壁垒，突破传统的专业限制和学习时段限制，构建跨校和跨地区的学习环境也是教育开放的另一个重要趋势。

​	进一步来看，教育的开放是全过程，不仅包括教育资源的开放，也包括教育行为记录、教育评价结果的开放。随着现代远程教育的兴起和大规模开放在线课程（慕课）的推广，开放教育已经从趋势变为了共识。开放教育的形式丰富多样，突破了面授的单一形式。但是，现有的教育系统尚未很好地适应这种模式，面授以外的学习过程和学习结果往往不被公众认可，从而产生了信任危机。即使是在传统的高等教育领域，学生的学历信用记录体系不完整、不透明，导致政府或者企业无法获得完整的有效信息。在求职时，又存在学历造假、简历造假等问题，用人单位和相关院校缺乏简单高效的验证手段。为此，我们急需一种新的机制，来保障人们在享受教育开放带来的便利的同时，保障教育应有的公信力，并进一步地推动教育走向开放。

#### 1.2探索解决方式

在此背景下，区块链技术的独特性也逐渐成为教育领域关注的焦点。2016年 10月，工信部颁布《中国区块链技术和应用发展白皮书》，指出“区块链系统的透明化、数据不可篡改等特征，完全适用于学生征信管理、升学就业、学术、资质证明、产学合作等方面，对教育就业的健康发展具有重要的价值”。2018年颁布的《教育信息化2.0行动计划》更是明确指出加快面向下一代网络的高校智能学习体系建设，探索区块链、大数据等新技术在学习效果记录、转移、交换、认证等方面的有效方式，形成泛在化、智能化学习体系。

<img src="https://i.loli.net/2020/12/29/z58CpRiLwIJ1BWV.png" style="zoom:50%;" />

区块链是一种把区块以链的方式组合在一起的数据结构，具有去中心化、按时序记录数据、集体维护、可编程和安全可信等特点，可以为信用背书、信息加密、智能合约等提供极大的便利，这对于当前的教育领域有很大的应用潜力。

首先，通过开发、应用基因区块链技术的学习管理平台，学习者和教师将成为教学资源和信息的管理和控制者，而不再是学校。因为基于区块链技术的分布式账本能够安全、灵活地管理分布式教学资源和信息，并能够通过数据分析技术的应用，在实现大规模学习认证的同时，扩大学习者的受教育机会。例如阿里云云学院就充分利用互联网及区块链的特点与优势，为学习用户提供云计算、大数据等专业的体系化在线课程与实验环境。进阶式的课程内容、闯关式的节点测试与在线认证相结合，培养兼备理论与实操双能力的技术人才。阿里云云学院为毕业学员颁发阿里云官方认证证书，出具技能评估报告，并给企业推荐。

其次，对那些因工作或其他原因而无法完成传统学校教育的个人学习者来说，通过区块链技术平台，可以把从不同教育机构修来的学分或学习结果绑定、组合在一起，申请认可此学习模式的教育机构的认证，而获得相应毕业或学位证书。英国开放大学已积极实践这一基于区块链技术的新型学习模式，此外，英国开放大学的“知识与媒体研究中心”已开发出组合“微认证”，或者说徽章的创新技术，以适应基于区块链技术平台的学习和认证。

最后，区块链技术的发展和应用能够帮助更多的人取得学习证明、职业资格证书或学位证书，尤其是不发达国家公民，从而有效提高个人在劳动力市场上的竞争力、促进其职业发展，并进而促进创业。例如江西软件职业技术大学为新生颁发基于区块链的录取通知书，该证书具备不可篡改性和与可验证特性。

### 第二节 系统分析

#### 2.1术语简介

**区块链**：区块链是一个数据集，这个数据集的组织方式比较特殊，它 把数据打包成一个一个的区块，每一个区块是一个区块链数据集的子 集。区块和区块之间的数据相互关联形成逻辑上的链式结构，所以区块 链因此得名，1.1.2节中我们会具体介绍这种链式结构。 区块链技术源于比特币，最开始就是为了解决去中心化的问题，所 以区块链是分布式的，可以把区块链看作一个分布式的账本。区块链上 的数据是每一个参与者的机器上都拥有的，而不是只放在某一台中心机 器上。 使用区块链来做什么呢？其实有太多场景。例如，使用区块链完成 类似于银行的转账职能，具体会在后面介绍。现在我们关心的是区块链 转账的数据如何传递给其他参与者，如果让每一个参与者都拥有区块链 数据，就需要每一个参与者之间能相互通信，因此需考虑怎样组建网 络。 假设已经组建好了网络，每一个参与者之间都能相互通信了，那么 另一个问题来了，每一个参与者都有全部的区块链数据，怎样保证大家 的数据都是一致的，或者说区块链的数据怎样不被篡改呢？ 简单地来说，区块链解决的主要问题就是：分布式网络中每一个参 与者的数据交换和防止数据不被参与者篡改，获得每一个参与者的认同。

![](https://i.loli.net/2020/12/31/M4eFzcDCVkptRxm.png)

每一个区块（Block）中包含一个区块头（Block Header），区块头 中包含一些块的元数据信息，例如区块编号、区块Hash值、区块创建时 间、父区块的Hash值和Nonce等数据。其中，Nonce是用来做工作量证 明的，它对于使用工作量证明机制的区块链来说很重要，所以后面会反 复介绍。 每一个区块中还包含一个区块体（Block Body），区块体中包含数 据交易信息和账户信息等，不同的区块链有不同的实现。 每一个Block会计算一个Hash值，这个Hash值会被下一个Block包 含，这样前一个Block就被固定了，所以只需要简单地计算前一个Block 的Hash值和自己包含的前一个Block的Hash值是否一致，这样就能判断 前一个Block是否已被修改，每一个Block都确定了前一个Block就形成了 一个链式的结构。

区块链结构时提到区块链除了交易数据，还包含一些其 他的数据，可以称这些数据为Block的元数据（Meta Data）。这些元数 据如下所述。 ·Index：第几区块（创世区块的索引为0）。 ·Hash：当前区块的Hash值。 ·Previous Hash：上一个区块的Hash值。 ·Timestamp：当前区块创建时的时间戳。 ·Data：存储在当前区块上的交易信息。 ·Nonce：参与Hash运算的数值，使区块的Hash值满足指定条件。

**以太坊**：以太坊是一个任何人都可以创建和运行去中心化应用的区块链平 台。但是没有任何人可以控制或者拥有以太坊，它是由很多世界各地的 人建立的开放源码项目。 注意：我们上面提到的以太坊特指以太坊整个生态，而不是指以太币，请读者不要混淆。 以太坊作为和比特币对标的项目，它的设计更具有适应性和灵活 性，可以容易地创建应用在以太坊上运行。以太坊和许多平台一样，例 如Android平台，遵循Android的规范，使用Java或者Kotlin语言就可以开 发了，以太坊则可以使用Solidity或者其他语言就可以进行开发。 应用开发完毕后要发布。像Android这类平台上的应用，开发完成 一般需要发布到第三方平台上，然后用户才能下载、安装，这些平台往 往有各种限制。以太坊不一样，以太坊开发完成之后可以直接部署在以 太坊平台上，没有任何限制。其他人要使用这些开发的应用也不需下 载，只需要调用开发者提供的接口或者开发者建立在接口上的服务就可 以了。另外，如果开发者要使用其他人开发的以太坊应用，还可以看到 其他人的源码。 当然，以太坊像比特币一样，也提供了自己的数字货币——以太 币，可以进行收款、付款、转账等各种交易。

挖矿只是一个比喻，对比于稀缺贵重金属需要实际挖矿而言，数字 货币运算的挖矿指的是一种计算。以太坊中挖矿的单位一般是区块，我 们一般说的矿工挖出一个区块，就是指一个运行以太坊客户端的节点从 现有的交易池中选择出一些交易，记录在一个块中，并且计算出一个指 定的值。 完成了上面的过程会有一些奖励，就是以太币，这就算是挖到矿 了，以太坊中称为挖出一个区块。总结一下，挖矿就是通过在区块链中 创建、验证、发布和传播区块来保护网络的一种方式。 至于为什么能够通过挖矿来保护网络，可以回顾一下第1章介绍的 工作量证明机制的相关内容。

![image-20201231113246483](https://i.loli.net/2020/12/31/nuitWPK5USxbavc.png)

挖矿奖励 前一节我们提到了成功挖出一个区块的矿工会有一些奖励，那么这 个奖励包含哪些部分呢？ ·静态区块奖励，5个以太币。 ·区块中所有交易gas花费，与当前gasPrice相关。 ·包含叔块的额外奖励。 其中，静态区块奖励是会逐渐减少的，最开始是5个以太币，现在 是3个以太币，区块中的交易使用gas并不是以太币，所以会乘以交易设 置的gasPrice。

以太坊的GHOST协议是一个非常重要的协议，它需要结合前面的 区块链、挖矿、工作量证明机制的知识才能更好地理解。如果能够理解 GHOST，那么对于以太坊的理解基本能够加深一个层次。正是因为 GHOST比较重要，所以本节我们尽量使用比较简化的模式来梳理一下 GHOST及其相关的知识。

我们使用网银转账，需要确认银行是否转账成功。有的银行需要30 秒就能确认，有的银行需要2小时才能确认。以太坊从根本来说是为了 完成交易，因此也需要确认一笔交易是否成功，我们一般希望交易在一 个比较确定的范围内被确认。 因为交易会被打包在区块之中，所以控制区块产生的时间在一定程 度上可以控制交易被确认的时间。区块产生的时间如何控制呢？我们知 道工作量证明机制中有一个难度值difficulty，这个难度值可以控制区块 产生的时间。中做了 一些调整，难度计算公式如下： block_diff = parent_diff + parent_diff // 2048 * max(1 - (block_timestamp - parent_timestamp) // 10, -99) + int(2**((block.number // 100000) - 2)) 其中，//表示整除。以太坊通过调整区块难度把区块产生时间控制 在15秒左右，所以我们可以认为以太坊的区块时间是15秒，当然这不是 一个绝对的时间，因为工作量证明机制使用的时间是不确定的。 一个区块时间不好控制，但是多个区块的平均时间就好控制了。以 太坊会把30 000区块当作一个纪元，只要把一个纪元的时间控制在125 小时左右就可以了。

区块分叉分为3种，分别是普通分叉、软分叉和硬分叉。其中软分 叉和硬分叉是因为修改源码造成的。如果修改的源码，只要求以太坊网 络中的50%以上的算力升级到新的版本，那么这个分叉叫做软分叉。如 果修改了源码，要求以太坊网络中的所有节点都必须升级到新的版本， 那么这个分叉叫做硬分叉。 通过以太坊的开发路线，知道以太坊的当前版本是Homestead， Homestead就是一个要求硬分叉的版本。应当注意分叉针对的是区块链数据，例如，Homestead版本的主网 要求大于等于1150000的区块号的产生必须是由Homestead版本产生。如 图4.8所示为以太坊区块链硬分叉示意图，就是把区块链数据从区块号 为1150000的区块分成了两部分。

![image-20201231113541405](https://i.loli.net/2020/12/31/EcNnjRhMreIvw2Z.png)



**DAPP**:Dapp是开放源代码能够运行在分布式网 络上，通过网络中不同对等节点相互通信进行去中心化操作的应用。 首先，DApp开放源代码，这样才能获得人的信任。例如比特币， 尽管很多人没有读过比特币的源码，但是仍然不影响这些人相信并且持 有比特币，就是因为比特币是开源的，如果有问题肯定会被发现。 去中心化应用肯定是分布式的应用，因为没有中心节点，所以必须 能够在节点之间进行通信。每一个去中心化应用都有自己的通信协议， 使用相同协议的节点共同组成了一个去中心化应用的网络。 注意：网络中的节点都是对等节点（peer），没有能完全控制 整个网络的节点。

DApp优点之一就是保证用户的匿名性，因为各种因素的限制，很 多应用必须经过身份验证才能使用。在中心化的应用中，可以通过要求 用户上传指定文件，如运营许可证等来验证用户的身份和资质。但是对 于去中心化的DApp来说，身份验证是一个比较有挑战性的问题，现阶 段使用的最广泛的方式就是数字证书。 其实最重要的就是私钥，谁拥有私钥，谁就是这个账户的拥有者， 比特币是这样，以太坊也是这样。这种方式就不能避免其他人“碰撞”私 钥，虽然碰撞到的几率很低，但还是存在这种可能性。DApp还没有尝 试次数限制或者短信验证的用户验证机制来避免这个问题。

比特币算知名度最高的DApp，是一个最早的数字货币，也是纯粹 的数字货币。比特币使用的很多技术也基本上成了其他DApp的“标 配”，例如区块链技术和工作量证明机制等。 还有一个大家比较关心的问题，就是比特币的合法性。首先需要明 确的一点是，比特币是合法的，问题的关键在于比特币被定义为什么 类，是一种货币，还是一种商品，亦或是其他分类。 国内比特币被定义为虚拟商品，不能作为货币流通，但是比特币交 易作为一种互联网上的商品买卖行为，普通民众在自担风险的前提下拥 有参与的自由。最重要的是金融机构和支付机构不得以比特币为产品或 服务定价。所以比特币是合法的，在国内只是限制了金融机构和支付机 构把比特币作为投资标的，在美国比特币被当作一种大宗商品，在英国 和欧盟比特币被当作一种货币。

以太坊也是热门的DApp，和比特币不同的是，以太坊的目标是做 一个DApp应用平台，而不仅仅是一个数字货币。最显著的特点就是以 太坊支持智能合约，这就为以太坊在很多应用场景的落地提供了夯实的 基础，例如在众筹、慈善、中介和公证等很多方面智能合约都能够发挥 它的作用。

DApp存在的问题 从辩证主义的角度来看，一件事有好的一面，肯定就会有不好的一 面，DApp也一样存在不完美的一面。我们知道DApp节点分布在网络 中，因此DApp的数据不会被轻易修改，辩证地看，也就让DApp升级困 难。 DApp保证了用户的匿名性，那么通常带来的问题就是用户身份的 验证困难，同样，因为DApp的安全性高，就存在DApp系统更加复杂的 问题。因为DApp的去中心化，所以DApp不能依赖以中心化的服务，那 么生态的建立是非常缓慢的。



#### 2.2开发工具



**Geth:**Geth是一个以太坊客户端，实现以太坊相关的协议，通过Geth来同 步以太坊区块链的数据，进行挖矿。 Geth还可以作为一个完全节点，为其他轻节点提供服务，比如我们 可以通过MetaMask或者web3.js访问Geth节点进行交易、查询等操作。

**MetaMask:**一般MetaMask是作为一个浏览器插件使用，可以看做是一个轻量 级的钱包，它提供了很多和以太坊交互的接口，降低了实际项目中与以 太坊交互的开发成本。 本质上MetaMask是使用web3.js和以太坊节点进行交互的，通过 HTTP请求调用以太坊客户端提供的RPC接口。MetaMask的所有功能都 可以通过web3.js来实现，不过使用MetaMask能简化开发工作。

##### **Solidity**



**:**Solidity是一门面向合约的高级语言，主要用来 编写以太坊智能合约。Solidity受C语言、Python、JavaScript语言的影 响，很多实现都和这些语言相似，但是Solidity为了编译成为以太坊虚拟 机字节码在EVM上执行，很多特性和限制都和EVM相关。 如图9.1所示为Solidity中常见的一些概念。Solidity是一门静态类型 语言，支持继承、库、自定义复杂类型和其他特性。

![image-20201231112250104](https://i.loli.net/2020/12/31/AFndVYy3uxElzpt.png)



**智能合约示例:**

![image-20201231112413746](https://i.loli.net/2020/12/31/Uz8JNVcdxaFlEbI.png)

上面的例子，最外层是contract关键字，Solidity是一门面向合约的 语言，contract就是一种很好地体现，所有的合约结构都是在contract包 围之中。 像Java这种面向对象的语言，最外层是class包围，不过在Solidity中 不是定义一个类，而是定义一个合约。合约中可以包含状态变量、函 数、事件、自定义类型等，这些都会在后面详细介绍，这里我们需要知 道的是合约的最基本结构。

````java
contract SolidityContract{

}
````

上面的示例就是合约的最简结构，首先是contract关键字，后面是 合约名字，花括号“{}”中是合约体。

智能合约中包含的基本结构，本节来了解一下合 约中第一行是什么意思。在Solidity文件中一般第一行是这样的：

````
pragma solidity ^0.4.24;
````

pragma是编译指示的意思，不是program。这是为了说明这个 Solidity文件可以使用哪些版本的编译器编译。^与前面5.3.2节中介绍的^ 限制范围含义一样。

**web3.js:**web3.js是一个JavaScript库，它和以太坊有什么关系？这还需要从 JSON-RPC协议说起。我们知道以太坊的很多客户端都实现了JSONRPC协议，会启动一个服务，其他轻客户端可以通过HTTP请求来查询 相关数据。前面我们接触的Ganache相当于一个以太坊客户端，使用 Postman来发送请求，通过影响的接口获取对应的数据。 web3.js本质和Postman一样，也是使用JSON-RPC协议，通过调用对 应接口的方法来获取数据，不过web3.js是通过浏览器或者Node等来发 送HTTP请求。

**Truffle:**Truffle是基于Solidity语言的一套开发框架，它简化了去中心化应用（Dapp）的构建和管理流程。本身是采用Javascript编写，支持智能合约的编译、部署和测试。truffle开发框架提供了很多功能，简化了我们的开发、编译、部署与调试过程。

**Git:**是一个开源的分布式版本控制系统，可以有效、高速地处理从很小到非常大的项目版本管理。

**Node.js:**Node.js是一个基于Chrome V8引擎的JavaScript运行环境，使用了一 个事件驱动、非阻塞式I/O的模型。Node.js的包管理器NPM，是全球最 大的开源库生态系统，因为它让JavaScript可以作为后端语言使用。

**Ganache:**以太坊的很多操作需要gas费用，按照现在以太坊的价格如果在主 链上开发测试的话，成本太高。 有读者可能会说以太坊还有很多测试链，的确如此，但是测试链的 速度很慢，确认交易需要很长时间，所以为了开发，我们需要搭建自己 的私链。 有很多客户端可以帮助我们完成这个工作，本章介绍的Ganache就 是这样一个以太坊客户端。Ganache可以帮助我们快速启动一个以太坊 私链来做开发测试、执行命令、探测区块链状态等。



#### 2.3系统开发环境

#### 2.4系统结构图

#### 2.5系统登录流程图

### 第三节 代码实现（功能实现）

#### 3.1

### 第四节 系统测试

#### 4.1测试目的

#### 4.2测试方案

#### 4.3测试结果

### 第五节 结论

#### 5.1

### 参考文献

[1]习近平：把区块链作为核心技术自主创新重要突破口《 人民日报海外版 》（ 2019年10月26日  第 01 版）



### 致谢
