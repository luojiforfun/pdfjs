## 九页缓冲，带目录功能

### 注意事项

- html读取文件会有跨域问题，建议使用nginx，关闭跨域检查也行；
- 有两种指定加载文件的方式，一是使用url，二是在js中指定，本例使用第二种；
- 每次只加载9页确实快了不少，但在部分平板上效果仍然不够好；
- 代码无注释，力求通过代码本身来说明。

### 预计开发

- 实现一般pdf软件应有的所有功能；
- 提升加载速度，在平板端尽量拉近与原生软件的使用体验；
- 使用node实现桌面应用；
- 结合H5的canvas实现白板功能。

