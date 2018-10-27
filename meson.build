project('irpy', 'cpp')

llvm = dependency('llvm', version: '>= 5.0.0')
add_project_arguments('-DNDEBUG', language : 'cpp')

sources = ['compiler/Emitter.cc',
           'compiler/irpy.cc',
           'compiler/PyEmitter.cc',
           'compiler/PyLLVMEmitter.cc']

executable('irpy', sources, dependencies: llvm)