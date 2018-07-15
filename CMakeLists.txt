cmake_minimum_required(VERSION 3.10)
project(easycwmp_1_6_2 C)

set(CMAKE_C_STANDARD 11)

include_directories(src)

add_executable(easycwmp_1_6_2
        src/backup.c
        src/backup.h
        src/config.c
        src/config.h
        src/cwmp.c
        src/cwmp.h
        src/digestauth.c
        src/digestauth.h
        src/easycwmp.c
        src/easycwmp.h
        src/external.c
        src/external.h
        src/http.c
        src/http.h
        src/json.c
        src/json.h
        src/log.c
        src/log.h
        src/md5.c
        src/md5.h
        src/messages.h
        src/time.c
        src/time.h
        src/ubus.c
        src/ubus.h
        src/xml.c
        src/xml.h)
