# Core Concepts
The following are the terminologies and their definitions of Message Queue.
## 1. Message Related Terminologies 
| Term | Definition |
| :- | :- | :- |
| Message | The carrier of data transmission in Message Queue. |
| Message ID | Message ID is a unique identifier of the message that automatically generated by the system, and uniquely identifies a message. |
| Message Body | The message content carries by the message is the data to transmit. Message Body is the message content carried by the message and is actually the data to transmit. |
| Tag | Message Queue allows you to set tags on subscribers and messages to filter messages, ensures that the subscribers only consume the messages they want. The strategy of tag is that the subscribers’ only consumer the message tagged in accord with tags in the subscribers. |
| Transport Type | It includes two protocols such as SDK (TCP) and HTTP to transmit messages. |
|Message Retention Period | The longest survival time of a message on the server and it calculates from writing messages successfully. Messages will be deleted no matter whether they have been consumed. The unit is second, and the default value is 259200(3 days). It does not allow modifying. |
| Visibility Timeout | In order to avoid other consumers to consume the message at the same time; it is the temporarily hidden time of the message after receiving a message. |
| Maximum Message Size | The maximum size of the message body is 256KB. |
| Maximum Receives | The number of server pushing messages to the subscribers ensures at least one time, and 16 times at most. |
| Maximum Query Rate | The maximum total number of requests per second includes production and consumption messages of Message Queue. |
| Message Stacking | When a message is not delivered or the subscriber fails in receiving it, a topic holds the message that is not consumed; the state of message is called message accumulation. |
| Delayed Message | The producer sends a message to the server but does not want the message to be delivered immediately and delays the delivery of the message to the consumer after a period for consumption. This type of message is called delayed messages. |
| Ordered Message | Message Queue provides a type of message that is released and consumed in strict order. Ordered messages are consist of two parts: Ordered publication and Ordered consumption. |
| Reset Consumer Offset | In the period of message persistence storage (default 3 days), this ability is to reset the consumption progress of a message subscriber to its subscription topic. |
| Dead Letter Queue | Messages are sent to the dead-letter queue after a maximum number of receipts and can be isolated from the dead-letter queue to determine the cause of its processing failure. |

## Topic Subscription Related Terminologies 
| Term | Definition |
| :- | :- | :- |
| Topic | To category the messages through creating topics. |
| Subscriber | The role of subscribing messages in the topic. |
| Producer | The role of sending messages in the topic. |
| Consumer Group | The role of consuming messages to subscribe in the topic. |
| Consumer | The role of consuming messages to subscribe in the topic. |
| Subscribe | Need to build subscription relationship when receiving messages in the topic. |



