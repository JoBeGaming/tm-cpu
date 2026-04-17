# ISA

## Instructions

| Index | Opcode | Operands |
|---|---|---|
| nop | 0000 | - |
| add | 0001 | r, r, r (dst) |
| sub | 0010 | r, r, r (dst) |
| and | 0011 | r, r, r (dst) |
| or | 0100 | r, r, r (dst) |
| xor | 0101 | r, r, r (dst) |
| ldi | 0110 | r (dst), imm |
| lod | 0111 | r (dst), ra |
| str | 1000 | r, ra (dst) |
| out | 1001 | r, p (dst) |
| in | 1010 | r (dst), p |
| cmp | 1011 | r, r, flg |
| jmp | 1100 | imm |
| brh | 1101 | imm, flg |
| - | 1110 | - |
| hlt | 1111 | - |

## Flags

| flag | name |
|-----|----|
| 000 | ze |
| 001 | ng |
| 010 | eq |
| 011 | ne |
| 100 | gt |
| 101 | lt |
| 110 | ge |
| 111 | le |
