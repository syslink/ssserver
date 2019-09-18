# ssserver

config.json:\
{\
    "server":"0.0.0.0",\
    "server_port":8388,\
    "local_port":1080,\
    "local_address":"127.0.0.1",\
    "password":"syslink",\
    "method": "aes-128-cfb",\
    "timeout":600\
}

\
nohup ./shadowsocks-server > log &
