BITS 64


global _main

section .rodata

	pathname db 'NASA.txt', 0

	mode: dw 777
section .text
	
_main:
	mov rax, 85
	mov rdi, pathname
	mov rsi, mode
	syscall
	jmp _exit


_exit:
	mov rax, 0x3C
	mov rdi, 0
	syscall	
