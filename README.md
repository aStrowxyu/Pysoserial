# Pysoserial

## 介绍

[![Python 3.x](https://img.shields.io/badge/python-3.x-yellow.svg)](https://www.python.org/) [![Python 2.x](https://img.shields.io/badge/python-2.x-green.svg)](https://www.python.org/)

Pysoserial是完全由python编写的用于生成利用不安全Java对象反序列化的有效负载的概念验证工具。工具参考[ysoserial](https://github.com/frohoff/ysoserial)

## 安装

使用git拉取项目

```bash
git clone https://github.com/aStrowxyu/Pysoserial
```

## 使用

```bash
usage: JAVA deserialize payload [-h] [-p PAYLOAD] [-c COMMAND] [-o OUTPUT]
                                [-l]

Generate the JAVA Deserialize Payload

optional arguments:
  -h, --help            show this help message and exit
  -p PAYLOAD, --payload PAYLOAD
                        JAVA deserialize payload
  -c COMMAND, --command COMMAND
                        Payload Specifies the command to be executed
  -o OUTPUT, --output OUTPUT
                        Output to a file
  -l, --list            Payload List

examples:
  python pysoserial.py -p CommonsCollections1 -c whoami
  python pysoserial.py -p CommonsCollections1 -c whoami -o payload.ser
```

## 参考项目

[https://github.com/frohoff/ysoserial](https://github.com/frohoff/ysoserial)
