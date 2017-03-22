prebuilt_cxx_library(
  name = 'fakeit',
  header_only = True,
  header_namespace = '',
  exported_headers = subdir_glob([
    # ('include/fakeit', '**/*.hpp'),
    ('single_header/standalone', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)

prebuilt_cxx_library(
  name = 'fakeit-tpunit',
  header_only = True,
  header_namespace = '',
  exported_headers = subdir_glob([
    ('single_header/tpunit', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
)
