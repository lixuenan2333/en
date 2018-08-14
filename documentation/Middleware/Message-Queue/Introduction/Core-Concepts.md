# Core Concepts
The following are the terminologies and their definitions of MQ.
## 消息相关名词 
| 术语名称 | Term | Definition |
| :- | :- | :- |
| 消息 | Message | 消息队列中数据传输的载体 |
| 消息ID | Message ID | 消息的全局唯一标识，由系统自动生成，唯一标识某条消息 |
| 消息主体 | Message Body | 消息所承载的消息内容，也就是所要传送的数据 |
| 标签 | Tag | 消息队列 JCQ允许对订阅者和消息设置tag来进行消息过滤，确保订阅者最终只消费到他想获得的消息，tag是消息订阅者对于消息的筛选 |
| 传送类型 | Transport Type | 包含SDK（TCP）和HTTP两种协议进行消息传输 |
| 消息生命周期 |Message Retention Period/Message Life Cycle | 消息存在服务端最长的存活时间，从消息成功写入开始计算，不论消息是否被消费过都将被删除，单位为秒，默认值为259200（3天），不允许修改 |
| 取出消息隐藏时长 | Visibility Timeout | 消息被接收后，为了避免其他消费者同时消费此消息，将消息暂时隐藏的时间 |
| 消息最大长度 | The Maximum Length of Message | 限制消息主体的大小最大为256KB |
| 最大接收次数 | The Number of Maximum Receives | 服务端向订阅者推送消息，保证至少一次，最多尝试16次 |
| QPS | Maximum Query rate | 消息队列 JCQ生产和消费消息合计每秒最大的请求次数 |
| 消息堆积 | Message Stacking | 消息还未投递或者订阅者接收消息失败，topic保存着未被消费的消息，该状态即消息堆积 |
| 延时消息 | Delayed Message | 消息的生产者发送一条消息到服务端但是并不想这条消息马上被投递，而是延迟设定的一段时间后才投递给消费者进行消费，该类消息被称为延时消息 |
| 顺序消息 | Ordered Message | 消息队列 JCQ提供的一种严格按照顺序进行发布和消费的消息类型。顺序消息由两个部分组成：顺序发布和顺序消费 |
| 重置消费位点 | reset consumer point/offset? | 在消息持久化存储的时间范围内（默认3天），重新设置消息订阅者对其订阅topic的消费进度的功能 |
| 死信队列 | Dead Letter Queue | 在超过最大接收次数后会将消息发送到死信队列，可以在死信队列中隔离这些消息以确定其处理失败的原因 |

## 主题订阅相关名词 
| 术语名称 | Term | Definition |
| :- | :- | :- |
| 主题 | Topic | 通过创建topic来对消息进行消息分类 |
| 订阅者 | Subscriber | 在主题中订阅消息的角色 |
| 生产者 | Producer | 在主题中发送消息的角色 |
| 消费组 | Consumer Group | 在主题中通过订阅进行消息消费的角色 |
| 订阅 | subscribe | 在主题中进行消息接收时要建立订阅关系 |


