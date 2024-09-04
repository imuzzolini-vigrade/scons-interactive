env = DefaultEnvironment()

# add compiler arguements to trigger the generation of .lnk file
env.AppendUnique(CPPPATH=[f"any/random/include/directory{i}" for i in range(0,80)])

env.Program("hello.c")