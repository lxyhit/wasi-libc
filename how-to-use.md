# 需要改动Makefile的地方
`Makefile`开始的`CC`变量需要改为`wasi-sdk`中对应的地址

# 如何得到libc.wasm
运行`make default libc_wasm`会在当前目录下生成`libc.wasm`文件
