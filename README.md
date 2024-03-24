def bin_to_dec(bin_num):
    return int(bin_num, 2)

def dec_to_bin(dec_num):
    return bin(dec_num)[2:]

def oct_to_dec(oct_num):
    return int(oct_num, 8)

def dec_to_oct(dec_num):
    return oct(dec_num)[2:]

def hex_to_dec(hex_num):
    return int(hex_num, 16)

def dec_to_hex(dec_num):
    return hex(dec_num)[2:]

# Contoh penggunaan
binary_number = "1010"
decimal_number = 42
octal_number = "52"
hexadecimal_number = "2A"

print(f"{binary_number} dalam desimal: {bin_to_dec(binary_number)}")
print(f"{decimal_number} dalam biner: {dec_to_bin(decimal_number)}")
print(f"{octal_number} dalam desimal: {oct_to_dec(octal_number)}")
print(f"{decimal_number} dalam oktal: {dec_to_oct(decimal_number)}")
print(f"{hexadecimal_number} dalam desimal: {hex_to_dec(hexadecimal_number)}")
print(f"{decimal_number} dalam heksadesimal: {dec_to_hex(decimal_number)}")
