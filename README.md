## Tsis_1_des_cipher_in_bash
This is my bash practice task. I'm learning to write bash scripts. So I thought writing a cipher would help me.
# How to use?
1. Clone this repository. Like " git clone https://github.com/baigazyev/Tsis_1_des_cipher_in_bash.git "
2. Then give execute permission. Like " sudo chmod +x des.sh "
3. You need to execute like this: ./des.sh <plain text 8 length> <your key also 8 length> <if you want to encrypt 0, if decrypt 1>
# How works DES encryption?
1. Plain text for 64 bit.
2. Convert to ascii.
3. Initial permutation.
4. Divide to two parts for 32 bit.
