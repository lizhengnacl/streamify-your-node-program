# Node Stream
对[Node.js]中[stream]模块的学习积累和理解。

- [什么是流](docs/what-is-stream.md)
- [为什么使用流](docs/when-to-use-stream.md)
- [Readable](docs/readable.md)
  - [如何创建](docs/readable.md#如何创建)
    - [end事件](docs/readable.md#end事件)
  - [如何使用](docs/readable.md#如何使用)
    - [flowing模式](docs/readable.md#flowing模式)
    - [paused模式](docs/readable.md#paused模式)
- [Writable](docs/writable.md)
  - [创建与使用](docs/writable.md#创建与使用)
  - [finish事件](docs/writable.md#finish事件)
- [objectMode](docs/objectMode.md)
  - [对Readable的影响](docs/objectMode.md#对readable的影响)
  - [对Writable的影响](docs/objectMode.md#对writable的影响)
  - [什么时候用objectMode](docs/objectMode.md#什么时候用objectmode)
- [highWaterMark](docs/highWaterMark.md)
  - [Readable中的缓存](docs/highWaterMark.md#readable中的缓存)
  - [Writable中的缓存](docs/highWaterMark.md#writable中的缓存)
- [pipe](docs/pipe.md)
  - [pipe的使用](docs/pipe.md#pipe的使用)
  - [从push到pull](docs/pipe.md#从push到pull)
- [Duplex](docs/duplex.md)
- [Transform](docs/transform.md)
- [Pipeline](docs/pipeline.md)

[Node.js]: https://nodejs.org/
[stream]: https://nodejs.org/api/stream.html

