project('filters', ['cpp'])

main_sources = files('main.cpp')

subdir('a/b')

executable('main_only', main_sources)
executable('main_a', main_sources + files('a/a.cpp'))
executable('main_b', main_sources + files('a/b/b.cpp'))
executable('main_a_b', main_sources + files('a/a.cpp', 'a/b/b.cpp'))
