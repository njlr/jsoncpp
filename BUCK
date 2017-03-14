cxx_library(
  name = 'jsoncpp',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', 'json/*.h'),
  ]),
  headers = subdir_glob([
    ('src/lib_json', '*.h'),
  ]),
  srcs = glob([
    'src/lib_json/*.cpp',
  ]),
  visibility = [
    'PUBLIC',
  ],
)
