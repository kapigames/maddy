project('maddy', 'cpp',
  version: '1.1.2',
  default_options: ['warning_level=3', 'cpp_std=c++14'],
  license: 'MIT')


maddy_includes = include_directories('include')
maddy_depends = [dependency('threads')]

maddy_dep = declare_dependency(include_directories: maddy_includes)