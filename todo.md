## TODO
-[x] UXN CPU
	- [x] arithmetic.rom
	- [x] literals.rom
	- [x] jumps.rom
	- [x] memory.rom
	- [x] stack.rom
	- [x] tests.rom
-[x] Video
	-[x] Vector
	-[x] Sprites
	-[x] Auto mode
	-[x] Effects and blending
	-[x] Handle bg and fg properly
	-[x] Set background color at first
-[ ] Clean Up
	-[ ] Refactor stacks into their own classes
	-[ ] Resolve warnings
		- [x] Unused dependencies
		- [ ] UPPERCASE FUNCTIONS
-[ ] Mouse
-[ ] Controller
-[ ] Audio
-[ ] Midi
-[ ] QOL
	-[x] Change name and logo
	-[ ] Hide debug menu for final release
		-[ ] Maybe only maintain it in standalone mode
		-[ ] Debug mode inspired by https://github.com/randrew/uxn32
	-[ ] Replace all panics with warnings in the frontend
		-[ ] Underflow
		-[ ] Overflow
		-[ ] Division
		-[ ] No Instruction
	-[x] Window size changing implemented as an egui window
		-[ ] Update until baseview supports resizing
		-[ ] Figure out an approach that could work when resizing after drawing
			-[x] Check if this is even supported on the original uxn emulator (it is, e.g. launcher.rom)
	-[ ] Set-up inputs and outputs directly from egui
	-[ ] Custom parameters to be used in uxn