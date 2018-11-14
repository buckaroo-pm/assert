prebuilt_cxx_library(
  name = 'assert', 
  header_namespace = 'boost', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.boost-config//:config', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
