project(
    'CoverageBugReport',
    'cpp',
    version: '0.0.1',
    default_options: ['cpp_std=c++20', 'buildtype=release'],
)

cc = meson.get_compiler('cpp')
py = import('python').find_installation(pure: false)
pybind11_dep = dependency('pybind11')

subdir('coverage_bug_report')
