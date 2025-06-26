python_sources = [
    '__init__.py',
    'a_cpp_module.pyi',
]

py.install_sources(
    python_sources,
    subdir: 'coverage_bug_report'
)

py.extension_module(
    'a_cpp_module',
    'a_cpp_module.cpp',
    install: true,
    dependencies : [pybind11_dep],
    subdir: 'coverage_bug_report'
)
