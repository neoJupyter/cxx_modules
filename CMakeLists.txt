cmake_minimum_required(VERSION 3.11)

include(klsxx/Build/Config.cmake)
project(njp.cxx)

set(KLS_DISABLE_TEST TRUE)
kls_configure()
kls_define_modules(klsxx common count)
