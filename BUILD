cc_library(
  name = 'SDL2',
  visibility = ['//visibility:public'],
  srcs = glob([
    'libSDL2_build.a',
    'libSDL2_build.so',
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

