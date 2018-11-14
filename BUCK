prebuilt_cxx_library(
  name = 'numeric-conversion', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
    'buckaroo.github.buckaroo-pm.boost-core//:core', 
    'buckaroo.github.buckaroo-pm.boost-detail//:detail', 
    'buckaroo.github.buckaroo-pm.boost-integer//:integer', 
    'buckaroo.github.buckaroo-pm.boost-preprocessor//:preprocessor', 
    'buckaroo.github.buckaroo-pm.boost-throw_exception//:throw-exception',
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
