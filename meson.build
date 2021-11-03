project('mesonquote')

run = find_program('run.py')
message('run is @0@'.format(run))
foo = find_program('foo')
message('foo is @0@'.format(foo))
message('foo.full_path() is @0@'.format(foo.full_path()))

custom_target('out', capture: true, output: 'out',
              command: [run, foo])
