project(
    'maddy',
    'cpp',
    version: '1.1.2',
    license: 'MIT',
    default_options: ['warning_level=3', 'cpp_std=c++14', 'c_std=c11'],
    meson_version: '>=0.60.0',
)


maddy_inc = include_directories('include')

maddy_dep = declare_dependency(
    include_directories: maddy_inc
)

meson.override_dependency('maddy', maddy_dep)
