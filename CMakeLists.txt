set(CONF_FILE prj.conf litex.conf)
set(DTC_OVERLAY_FILE litex.overlay app.overlay)
set(BOARD litex_vexriscv)

cmake_minimum_required(VERSION 3.20.0)
find_package(Zephyr REQUIRED HINTS $ENV{ZEPHYR_BASE})
project(shell_module)

target_sources(app PRIVATE src/main.c)
