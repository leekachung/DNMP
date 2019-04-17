# DNMP
Docker集成PHP7.2 Nginx MySQL Redis Swoole等

## 环境
    #确保已安装
    docker
    docker-compose

## 使用
    git clone https://github.com/leekachung/DNMP.git
    docker-compose up -d

## 可能出现的问题

- ERROR: Get https://registry-1.docker.io/v2/: net/http: TLS handshake timeout

        修复方法：重启docker
