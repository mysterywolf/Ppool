from building import *

cwd = GetCurrentDir()
src	= Glob('*.c')

CPPPATH = [cwd]

group = DefineGroup('Ppool', src, depend = ['PKG_USING_PPOOL'], CPPPATH = CPPPATH)

Return('group')
