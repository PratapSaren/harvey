objcopy(
	name="harvey",
	deps=[
		"//sys/src/9/amd64:harvey"
	],
	in="elf64-x86-64",
	out="elf32-i386",
)
kernel(
	name="kernel",
	deps=[
		":harvey",
		"//sys/src/9/amd64:init",
	],
)