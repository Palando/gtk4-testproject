project('testproject', 'c',
  version : '0.1',
  default_options : ['warning_level=3'])

gtkdep = dependency('gtk4')

exe = executable('testproject', 'testproject.c', 
  dependencies : gtkdep,
  install : true)

test('basic', exe)
