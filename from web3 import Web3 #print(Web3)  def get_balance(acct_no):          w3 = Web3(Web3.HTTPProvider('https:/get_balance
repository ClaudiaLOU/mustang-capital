from web3 import Web3
#print(Web3)

def get_balance(acct_no):
    
    w3 = Web3(Web3.HTTPProvider('https://data-seed-prebsc-1-s1.binance.org:8545')) # connect to test net
    my_balance = w3.eth.get_balance(acct_no) # my metamask account 0x0EB52e555C78d4f8Ac525147b5a0Fce39F21E77A
    return(my_balance)
    
my_acct_no = '0x0EB52e555C78d4f8Ac525147b5a0Fce39F21E77A'
get_balance(my_acct_no)
