## README for ps_print.c

This is a homework assignment (#1) for COMP410 - Operating Systems at Loyola University. 

### Note:
This is a delicate program. It is my first exposure to writing C. There is essentially no error checking, nor are there any memory protections. If the output of PS changes, it will break. **Use with caution.**

### Usage
Can be compiled under Mac OS X or Minix-3, using the included makefile. 

Minix:

	make
	
Mac OS X:

	make MACOSX

Then run: 

	./ps_print

Code © 2011 Steven and Jeremy Chalmer 

---

Exampe Output (Minix-3):

	bash:~#./ps_print
		|->0
			|->-2
			|->-1
			|->-4
			|->-3
			|->1
				|->135
				|->134
				|->118
				|->176
				|->4
					|->17
					|->19
					|->8
					|->9
					|->25
					|->10
					|->34
					|->7
					|->5
					|->54
					|->67
					|->3
					|->39
					|->73
					|->80
					|->12
					|->95
					|->98
					|->23
					|->13
					|->101
					|->104
					|->6
				|->116
				|->132
					|->566
						|->568
							|->1324
								|->1325
									|->1326
									|->1327
									|->1328
					|->1318
						|->1320
					|->1321
						|->1323
				|->114
				|->136
				|->107
				|->109
		Done
