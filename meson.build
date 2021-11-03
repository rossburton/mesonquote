project('mesonquote')

foo = find_program('foo')
run = find_program('run.py')

custom_target('out', capture: true, output: 'out',
              command: [run, foo])
