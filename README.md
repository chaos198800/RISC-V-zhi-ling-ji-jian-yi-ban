# RISC-V指令集 简易版

## 资源描述

本仓库提供了一个名为“RISC-V指令集 简易版”的资源文件，该文件包含了RISC-V指令集的部分内容，主要涵盖了32位指令和RV32C的16位指令。然而，该资源文件中缺少了一些指令，例如32位的`li`等伪指令，以及RV64的`sd`、`ld`指令等。

## 资源内容

- **32位指令**：包括了RISC-V指令集中的部分32位指令。
- **RV32C 16位指令**：涵盖了RV32C指令集中的部分16位指令。

## 注意事项

由于资源文件中缺少一些指令，用户在使用时需要根据指令类型进行推测。例如，对于缺少的指令，可以通过编译汇编后所得的二进制代码进行分析，推断出指令的类型和具体内容。

例如，对于指令`60a2 ld ra8(sp)`，其二进制表示为`0110 0000 1010 0010`。根据`ld`指令为I型且为16位的特性，可以推断该指令属于CI-type，其中`fun3`为`011`，`op`为`10`，`imm`为`001000`，`rd`为`00001`。

## 使用建议

1. **指令推测**：对于缺少的指令，建议用户根据已有的指令类型和二进制表示进行推测。
2. **扩展学习**：用户可以通过查阅RISC-V官方文档或其他相关资料，进一步了解和补充缺失的指令。

## 贡献与反馈

如果您在使用过程中发现任何问题或有改进建议，欢迎提交Issue或Pull Request。我们期待您的贡献，共同完善这个资源文件。

## 下载链接

[RISC-V指令集简易版](https://pan.quark.cn/s/62862a8c3f3e)