cxx_binary(
  name = 'hello',
  header_namespace = '',
  headers = subdir_glob([
    ('include', '*.hpp')
  ]),
  srcs = [
    'src/main.cpp',
  ],
  platform_srcs = [
    ('default', ['src/default.cpp']),
    ('^macos.*', ['src/macos.cpp']),
    ('^linux.*', ['src/linux.cpp']),
    ('^windows.*', ['src/windows.cpp']),
  ],
)
