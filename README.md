# ProtocolBufferersExample
Exemplo do uso de Protocol Bufferes no marshalling de mensagens

precisa-se instalar o protoc
Sudo apt install protobunf-compiler

```
protoc --java_out=src/main/java/ aluno.proto

mvn clean compile assembly:single

export PATH=$PATH:/home/ubuntu/workspace/sistemas-distribuidos/ExemploProtocolBuffers/protobuf-compiler/bin
```
