How to build pgo binaries for node-v8

update LinkTimeCodeGeneration inside common.gypi with 1,2,3
2 = PGIInstrument
3 = PGOptimization


copy pgort140.dll is present in node\release folder

```
C:\Program Files (x86)\Microsoft Visual Studio 14.0>dir /s pgort140.dll /b
C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\bin\pgort140.dll
C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\bin\amd64\pgort140.dll
C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\bin\arm\pgort140.dll

```