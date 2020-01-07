freetype_sources = [
  'src/autofit/autofit.c',
  'src/base/ftbase.c',
  'src/base/ftbbox.c',
  'src/base/ftbitmap.c',
  'src/base/ftfstype.c',
  'src/base/ftgasp.c',
  'src/base/ftglyph.c',
  'src/base/ftinit.c',
  'src/base/ftmm.c',
  'src/base/ftpfr.c',
  'src/base/ftstroke.c',
  'src/base/ftsynth.c',
  'src/base/ftsystem.c',
  'src/base/fttype1.c',
  'src/base/ftwinfnt.c',
  'src/bdf/bdf.c',
  'src/bzip2/ftbzip2.c',
  'src/cache/ftcache.c',
  'src/cff/cff.c',
  'src/cid/type1cid.c',
  'src/gzip/ftgzip.c',
  'src/lzw/ftlzw.c',
  'src/pcf/pcf.c',
  'src/pfr/pfr.c',
  'src/psaux/psaux.c',
  'src/pshinter/pshinter.c',
  'src/psnames/psmodule.c',
  'src/raster/raster.c',
  'src/sfnt/sfnt.c',
  'src/smooth/smooth.c',
  'src/truetype/truetype.c',
  'src/type1/type1.c',
  'src/type42/type42.c',
  'src/winfonts/winfnt.c'
]

incdir = include_directories(
    'include',
    #'include/freetype',
    #'include/ft2build',
)

freetype = library('freetype', freetype_sources,
  include_directories : incdir,
  c_args: '-DFT2_BUILD_LIBRARY',
  )

freetypeDep = declare_dependency(
  link_with: freetype,
  include_directories : incdir)

# install_dep(['freetype', 'include'])

#freetype_ft2build_include_dir = ['${freetype_SOURCE_DIR}/include', 'CACHE', 'PATH', '', 'FORCE']
#freetype_include_dir = ['${freetype_SOURCE_DIR}/include/freetype', 'CACHE', 'PATH', '', 'FORCE']
#freetype_library_dbg = ['freetype', 'CACHE', 'STRING', '', 'FORCE']
#freetype_library_rel = ['freetype', 'CACHE', 'STRING', '', 'FORCE']
# mark_as_advanced(['FREETYPE_FT2BUILD_INCLUDE_DIR', 'FREETYPE_INCLUDE_DIR', 'FREETYPE_LIBRARY_DBG', 'FREETYPE_LIBRARY_REL'])
