# unicorn-protobuf-mutator
This project is designed to improve unicornafl with structure-aware fuzzing.  
The method combines AFLplusplus with libprotobuf-mutator to generate valid structured input and use existing libprotobuf-mutator python binding to load protobuf msg. 

## Reference
[afl-libprotobuf-mutator](https://github.com/thebabush/afl-libprotobuf-mutator)  
[libprotobuf-mutator](https://github.com/google/atheris/tree/master/contrib/libprotobuf_mutator)  
[AFLplusplus](https://github.com/AFLplusplus/AFLplusplus)  