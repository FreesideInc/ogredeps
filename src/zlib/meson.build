src = [
    'adler32.c',
    'compress.c',
    'crc32.c',
    'deflate.c',
    'gzclose.c',
    'gzlib.c',
    'gzread.c',
    'gzwrite.c',
    'infback.c',
    'inffast.c',
    'inflate.c',
    'inftrees.c',
    'trees.c',
    'uncompr.c',
    'zutil.c',
]
incdir = include_directories(
    '.',
)

zlib  = library('lzib', src,
  include_directories : incdir)

zlibDep = declare_dependency(
  link_with: zlib,
  include_directories : incdir)
