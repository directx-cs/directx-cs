Hey there my nickname is Aquiso. I love hacking, reserve engineering, operational security and coding.
<img align ="right" src = "https://raw.githubusercontent.com/pratik-kale20/pratik-kale20/main/linux.png" width="250" height="250">

```asm
	.file	"main.c"
	.text
	.section	.rodata
	.align 8
.LC0:
	.string	"Nickname: %s\nHobby: %s\nNationality: %s\nJabber: %s"
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
	subq	$96, %rsp
	movq	%fs:40, %rax
	movq	%rax, -8(%rbp)
	xorl	%eax, %eax
	movl	$7628154, -84(%rbp)
	movabsq	$5561777788738105155, %rax
	movabsq	$4909035135769734241, %rdx
	movq	%rax, -48(%rbp)
	movq	%rdx, -40(%rbp)
	movabsq	$7956013840588961381, %rax
	movabsq	$7809644454833168487, %rdx
	movq	%rax, -32(%rbp)
	movq	%rdx, -24(%rbp)
	movl	$1936290681, -16(%rbp)
	movb	$0, -12(%rbp)
	movabsq	$4639663587670190456, %rax
	movabsq	$8227644618978715763, %rdx
	movq	%rax, -80(%rbp)
	movq	%rdx, -72(%rbp)
	movw	$117, -64(%rbp)
	leaq	-80(%rbp), %rcx
	leaq	-48(%rbp), %rdx
	leaq	-84(%rbp), %rax
	movq	%rax, %rsi
	leaq	.LC0(%rip), %rdi
	movl	$0, %eax
	call	printf@PLT
	movl	$0, %eax
	movq	-8(%rbp), %rsi
	xorq	%fs:40, %rsi
	je	.L3
	call	__stack_chk_fail@PLT
.L3:
	leave
	.cfi_def_cfa 7, 8
	ret
	.cfi_endproc
```
![Github stats](https://github-readme-stats.vercel.app/api?username=zet-sec&show_icons=true&hide_border=true&icon_color=ffffff&bg_color=0000FF&title_color=fff&text_color=fff)
## Show ❤️ By Starring My Repos!
