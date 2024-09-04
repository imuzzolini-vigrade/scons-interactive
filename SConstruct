env = DefaultEnvironment()

# add compiler arguements to trigger the generation of .lnk file
env.AppendUnique(CPPPATH=[f"any/random/include/directory{i}" for i in range(0,80)])

env.Program("hello.c")

# HOW TO REPRODUCE:
# 1. run "scons --interactive"
# 2. build everything by typing "b" and hitting Enter (everything works as expected)
# 4. edit "hello.c" (to retrigger the compilation)
# 5. try to build everything once again by hitting Enter
# 6. the build will fail because the .lnk is not regenerated
