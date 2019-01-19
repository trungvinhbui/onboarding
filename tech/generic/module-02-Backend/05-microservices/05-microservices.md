Micro services
======================


## 1. Target

- Distributed systems
- Protocols and various micro services patterns

## 2. Content

- Networking protocols (RESTful, Thrift, gRPC)

- Data representation (JSON, Protobuf, MsgPack, Avro)

- [Distributed systems fallcies](https://www.infoworld.com/article/3114195/system-management/the-8-fallacies-of-distributed-computing-are-becoming-irrelevant.html) and [The 7 quests of resilient software design](https://www.slideshare.net/ufried/the-7-quests-of-resilient-software-design), [Why we need Resilient Software Design](https://jaxenter.com/need-resilient-software-design-115055.html), [Resilient software design in a nutshell](https://cdn.oreillystatic.com/en/assets/1/event/263/Resilient%20software%20design%20in%20a%20nutshell%20Presentation.pdf)

- [Micro services patterns](http://microservices.io/patterns/microservices.html)

- Message queues: Apache Kafka, ActivateMQ (and their benchmarks)

- [Distributed systems](http://book.mixu.net/distsys/single-page.html)

- [Awesome Scalability, Availability, and Stability Back-end Design Patterns](https://github.com/binhnguyennus/awesome-scalability)

- [Prometheus Monitoring With Grafana](https://dzone.com/articles/prometheus-monitoring-with-grafana)

- [Circuit Breaker Patterns](https://jaxenter.com/need-resilient-software-design-115055.html)

- Monitoring services with [Prometheus](https://povilasv.me/prometheus-tracking-request-duration/)

- [API versioning](https://cloudplatform.googleblog.com/2018/03/API-design-which-version-of-versioning-is-right-for-you.html)

- [Wheel Reinvention](https://capablerobot.com/blog/2018/2018-05-09-wheel-reinvention/)
## 3. Exercises

- Consul and decentralized service discovery
- Implement RESTful APIs for chat applications 
- Implement rate limiting patterns

### 3.1 gRPC

- Tìm hiểu về HTTP/2

- Tìm hiểu về [grpc](http://www.baeldung.com/grpc-introduction). Khuyến khích đọc slide sau: [Enabling Googley microservices with HTTP/2 and gRPC.](https://www.slideshare.net/borisovalex/enabling-googley-microservices-with-http2-and-grpc?qid=43320f5f-d8aa-4f9e-a898-441d08620564&v=&b=&from_search=5)

- Implement lại chương trình chat sử dụng gRPC

- Trình diễn nội dung tìm hiểu được

### 3.2 Rate limiting 

- Thuật toán [rate limiting](https://konghq.com/blog/how-to-design-a-scalable-rate-limiting-algorithm/) hoạt động thế nào? 

- [High-Performance Rate Limiting](https://www.smyte.com/blog/stopping-account-takeover?hs_preview=SqfhHtvj-5674313679)

- [Doorman](https://github.com/youtube/doorman)

- Implement rate limiting patterns trong chương trình chat để tránh việc chat quá nhiều

- Trình diễn nội dung tìm hiểu được

### 3.3 Service Discovery 

- Tìm hiểu và cài đặt [Consul](https://www.consul.io/)

- Tích hợp consul vào client và server chat để không cần cấu hình địa chỉ IP trước để hoạt động. (hint: sử dụng Consul Java client)

### 3.4 GraphQL

- [GraphQL vs. REST](https://dev-blog.apollodata.com/graphql-vs-rest-5d425123e34b)

- [google/rejoiner](https://github.com/google/rejoiner): Generates a unified GraphQL schema from gRPC microservices and other Protobuf sources

### 3.5 Reactive Design Pattern

- [Reactive Design Patterns](https://www.reactivedesignpatterns.com/)

### 3.6 RPC

https://github.com/topics/rpc-framework

https://github.com/Tencent/Tars/blob/master/README.en.md

https://github.com/brpc/brpc

https://github.com/apache/incubator-dubbo

https://github.com/alipay/sofa-rpc

https://github.com/ValveSoftware/GameNetworkingSockets

https://github.com/EsotericSoftware/kryonet