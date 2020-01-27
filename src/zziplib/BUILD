package(default_visibility = ["//visibility:public"])

cc_library(
    name = "zziplib",
    srcs = [
      'zzip/dir.c',
      'zzip/err.c',
      'zzip/file.c',
      'zzip/fseeko.c',
      'zzip/info.c',
      'zzip/memdisk.c',
      'zzip/mmapped.c',
      'zzip/plugin.c',
      'zzip/stat.c',
      'zzip/write.c',
      'zzip/zip.c',
      'zzip/fetch.c',
    ],
    hdrs = [
      'zzip/__debug.h',
      'zzip/__dirent.h',
      'zzip/__fnmatch.h',
      'zzip/__hints.h',
      'zzip/__mmap.h',
      'zzip/_config.h',
      'zzip/_msvc.h',
      'zzip/_msvc.sed',
      'zzip/autoconf.h',
      'zzip/conf.h',
      'zzip/file.h',
      'zzip/format.h',
      'zzip/fseeko.h',
      'zzip/info.h',
      'zzip/lib.h',
      'zzip/memdisk.h',
      'zzip/mmapped.h',
      'zzip/plugin.h',
      'zzip/stdint.h',
      'zzip/types.h',
      'zzip/write.h',
      'zzip/fetch.h',
      'zzip/zzip.h',
      'zzip/zzip32.h',
    ],
    
    copts = [
        "-Isubprojects/ogredeps/src/zziplib",
    ],
    includes = [
        '.'
    ],
    deps = [ "//subprojects/ogredeps/src/zlib" ],

)
