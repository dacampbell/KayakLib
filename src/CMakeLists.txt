add_library(KayakLib STATIC
    TaskQueue.cpp
    ThreadPool.cpp
    )

target_include_directories(KayakLib include)

target_compile_options(KayakLib PUBLIC std=c++14)
