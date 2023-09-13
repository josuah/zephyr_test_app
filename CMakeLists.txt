cmake_minimum_required(VERSION 3.20.0)

set(CONF_FILE prj.conf litex.conf)

find_package(Zephyr)
prjoect(tinynx33_som)

target_sources(app PRIVATE src/main.c)
