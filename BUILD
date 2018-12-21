cc_library(
  name = 'SDL2',
  visibility = ['//visibility:public'],
  srcs = glob([
    'libSDL_build.so'
    'libSDL_build.a'
  ]),
  hdrs = glob([
    'src/**/*.h',
    'include/**/*.h',
  ]),
  includes = [
    '.',
    'include',
  ],
  copts = [
    '-Wno-unused-parameter',
    '-Wno-unused-variable',
    '-Wno-sign-compare',
  ]
)

