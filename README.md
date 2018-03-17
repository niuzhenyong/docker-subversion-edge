# docker-subversion-edge
基于容器的 SubversionEdge 运行环境

    docker run --privileged --name csvn -d -p 3343:3343 -p 4434:4434 -p 18080:18080 -v {数据存放目录}:/opt/csvn/data --restart=always niuzhenyong/docker-subversion-edge
