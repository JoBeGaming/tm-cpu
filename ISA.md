# ISA

| Index | Opcode | Operands |
|---|---|---|
| - | 0000 | - |
| nop | 0001 | - |
| add | 0010 | r, r, r (dst) |
| sub | 0011 | r, r, r (dst) |
| and | 0100 | r, r, r (dst) |
| or | 0101 | r, r, r (dst) |
| xor | 0110 | r, r, r (dst) |
| ldi | 0111 | r (dst), imm |
| lod | 1000 | r (dst), ra |
| str | 1001 | r, ra (dst) |
| out | 1010 | r, p (dst) |
| in | 1011 | r (dst), p |
| cmp | 1100 | r, r, flg |
| jmp | 1101 | imm |
| brh | 1110 | imm, flg |
| hlt | 1111 | - |
