project('mesonquote')

run = find_program('run.py')
message('run is @0@'.format(run))
foo = find_program('foo')
message('foo is @0@'.format(foo))

custom_target('out', capture: true, output: 'out',
              command: [run, foo])
