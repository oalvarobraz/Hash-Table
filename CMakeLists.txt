cmake_minimum_required(VERSION 3.24)
project(hash_table C)

set(CMAKE_C_STANDARD 11)

add_executable(hash_table main.c funcionario.c funcionario.h encadeamento_exterior.c encadeamento_exterior.h compartimento_hash.c compartimento_hash.h interface.c interface.h)
