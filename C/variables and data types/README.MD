# C Data Types in C99

## Integer Data Types
| C type | stdint.h type | Bits | Sign | Range |
|---|---|---|---|---|
| char | uint8_t | 8 | Unsigned | 0 .. 255 |
| signed | char	int8_t | 8 | Signed | -128 .. 127 |
| unsigned | short	uint16_t | 16 | Unsigned | 0 .. 65,535 |
| short | int16_t | 16 | Signed | -32,768 .. 32,767 |
| unsigned int | uint32_t | 32 | Unsigned | 0 .. 4,294,967,295 |
| int | int32_t | 32 | Signed | -2,147,483,648 .. 2,147,483,647 |
| unsigned long long | uint64_t | 64 | Unsigned | 0 .. 18,446,744,073,709,551,615 |
| long long | int64_t | 64 | Signed | -9,223,372,036,854,775,808 .. 9,223,372,036,854,775,807 |

## Floating Point Data Types
| C type |	IEE754 Name | Bits | Range|
|--|--|--|--|
| float |	Single Precision | 32 | -3.4E38 .. 3.4E38|
| double |	Double Precision | 64 | -1.7E308 .. 1.7E308|

[Credit](https://os.mbed.com/handbook/C-Data-Types#integer-data-types)