load('//:subdir_glob.bzl', 'subdir_glob')
load('//:buckaroo_macros.bzl', 'buckaroo_deps')

prebuilt_cxx_library(
  name = 'numeric-conversion',
  header_namespace = 'boost',
  header_only = True,
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  deps = buckaroo_deps(),
  visibility = [
    'PUBLIC',
  ],
)
