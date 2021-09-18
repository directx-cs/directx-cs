Hey there my nickname is Aquiso. I love hacking, reserve engineering, operational security and coding.
<img align ="right" src = "https://raw.githubusercontent.com/pratik-kale20/pratik-kale20/main/linux.png" width="250" height="250">

```asm
	.text
	.section	.rodata
	.align 8
.LC0:
	.string	"Nickname: %s\nHobby: %s\nNationality: %s\nDiscord: %s"
	.text
	.globl	main
	.type	main, @function
main:
.LFB0:
	.cfi_startproc
	endbr64
	pushq	%rbp
	.cfi_def_cfa_offset 16
	.cfi_offset 6, -16
	movq	%rsp, %rbp
	.cfi_def_cfa_register 6
	subq	$912, %rsp
	movq	%fs:40, %rax
	movq	%rax, -8(%rbp)
	xorl	%eax, %eax
	leaq	-912(%rbp), %rax
	movl	$7628154, (%rax)
	leaq	-912(%rbp), %rax
	addq	$300, %rax
	movl	$1768189763, (%rax)
	movw	$26478, 4(%rax)
	movb	$0, 6(%rax)
	leaq	-912(%rbp), %rax
	addq	$600, %rax
	movabsq	$7656181180642375731, %rsi
	movabsq	$8462877718644679265, %rdi
	movq	%rsi, (%rax)
	movq	%rdi, 8(%rax)
	movb	$0, 16(%rax)
	leaq	-912(%rbp), %rax
	leaq	600(%rax), %rcx
	leaq	-912(%rbp), %rax
	leaq	300(%rax), %rdx
	leaq	-912(%rbp), %rax
	movq	%rax, %rsi
	leaq	.LC0(%rip), %rdi
	movl	$0, %eax
	call	printf@PLT
	movl	$0, %eax
	movq	-8(%rbp), %rdx
	xorq	%fs:40, %rdx
	je	.L3
	call	__stack_chk_fail@PLT
.L3:
	leave
	.cfi_def_cfa 7, 8
	ret
	.cfi_endproc
0:
	.string	 "GNU"
1:
	.align 8
	.long	 0xc0000002
	.long	 3f - 2f
2:
	.long	 0x3
3:
	.align 8
4:
```
![Github stats](https://github-readme-stats.vercel.app/api?username=zet-sec&show_icons=true&hide_border=true&icon_color=ffffff&bg_color=0000FF&title_color=fff&text_color=fff)
## Show ❤️ By Starring My Repos!
