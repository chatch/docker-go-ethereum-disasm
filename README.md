# docker-go-ethereum-disasm
Containerised [disasm](https://github.com/ethereum/go-ethereum/blob/master/cmd/disasm/main.go) command disassembles EVM bytecode.

On Docker Hub at https://hub.docker.com/r/chatch/go-ethereum-disasm

```
 cat evm_bytecode.dump | docker run --rm -i chatch/go-ethereum-disasm
```
