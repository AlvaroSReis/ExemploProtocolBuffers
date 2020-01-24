# ProtocolBufferersExample
Exemplo do uso de Protocol Bufferes no marshalling de mensagens

Precisa-se instalar o compilador


```
sudo apt install protobunf-compiler

```

apos isto executar o comando

```
protoc --java_out=src/main/java/ aluno.proto

mvn clean compile assembly:single

export PATH=$PATH:/home/ubuntu/workspace/sistemas-distribuidos/ExemploProtocolBuffers/protobuf-compiler/bin
```
