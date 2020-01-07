src = [
    'zzip/dir.c',
    'zzip/err.c',
    'zzip/fetch.c',
    'zzip/file.c',
    'zzip/fseeko.c',
    'zzip/info.c',
    'zzip/memdisk.c',
    'zzip/mmapped.c',
    'zzip/plugin.c',
    'zzip/stat.c',
    'zzip/write.c',
    'zzip/zip.c',
]

incdir = include_directories(
    #'zzip',
    '.',
)

zziplib  = library('zziplib', src,
  dependencies: [
      zlibDep,
  ],
  include_directories : incdir)

zziplibDep  = declare_dependency(
  link_with: zziplib,
  include_directories : incdir)
