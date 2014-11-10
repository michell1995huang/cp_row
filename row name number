
def symbol1(row):
    s = [
        '***0***',
        '**00***',
        '***0***',
        '***0***',
        '***0***',
        '***0***',
        '***0***',
        '***0***',
        '*000000',
    ]
    return s[row]


def symbol2(row):
    """
    row is a positive int
    return None
    """
    s = [
        '*00000*',
        '*0****0',
        '******0',
        '******0',
        '******0',
        '**00000',
        '*0*****',
        '*0*****',
        '*000000',
    ]
    return s[row]


def symbol3(row):
    s = [
        '*00000*',
        '******0',
        '******0',
        '******0',
        '*00000*',
        '******0',
        '******0',
        '******0',
        '*00000*',
    ]
    return s[row]

def symbol4(row):
    s =[
      '*****0*',
      '****00*',
      '***0*0*',
      '**0**0*',
      '*0***0*',
      '*000000',
      '*****0*',
      '*****0*',
      '*****0*',
    ]
    return s[row]


def symbol6(row):
    s =[
      '**0000*',
      '*0****0',
      '*0*****',
      '*0*****',
      '*00000*',
      '*0****0',
      '*0****0',
      '*0****0',
      '**0000*',
     ]
    return s[row]

def symbol0(row):
     s =[
       '**0000*',
       '*0***00',
       '*0***00',
       '*0**0*0',
       '*0*00*0',
       '*0*0**0',
       '*00***0',
       '*00***0',
       '**0000*',
     ]
     return s[row]


def symbolm(row):
     s=[
       '*0****0',
       '*00**00',
       '*000000',
       '*0*00*0',
       '*0*00*0',
       '*0****0',
       '*0****0',
       '*0****0',
       '*0****0',
     ]
     return s[row]


def symboli(row):
     s=[
       '*000000',
       '***0***',
       '***0***',
       '***0***',
       '***0***',
       '***0***',
       '***0***',
       '***0***',
       '*000000',
     ]
     return s[row]


def symbolc(row):
     s=[
       '**0000*',
       '*0****0',
       '*0*****',
       '*0*****',
       '*0*****',
       '*0*****',
       '*0*****',
       '*0****0',
       '**0000*',
     ]
     return s[row]


def symbolh(row):
     s=[
       '*0****0',
       '*0****0',
       '*0****0',
       '*0****0',
       '*000000',
       '*0****0',
       '*0****0',
       '*0****0',
       '*0****0',
     ]
     return s[row]


def symbole(row):
     s=[
       '*000000',
       '*0*****',
       '*0*****',
       '*0*****',
       '*00000*',
       '*0*****',
       '*0*****',
       '*0*****',
       '*000000',
     ]
     return s[row]



def symboll(row):
     s=[
       '*0*****',
       '*0*****',
       '*0*****',
       '*0*****',
       '*0*****',
       '*0*****',
       '*0*****',
       '*0*****',
       '*000000',
     ]
     return s[row]



    


'''
# test symbol function is work correctly
symbol1(1)
symbol2(2)
'''

# dict map key:string value:function
# string->function
symbolDict = {"1": symbol1, "2": symbol2, "3": symbol3, "4":symbol4, "6":symbol6, "0":symbol0,  "m":symbolm,  "i":symboli,  "c":symbolc,  "h":symbolh,  "e":symbole,  "l":symboll}

row = 9

while True:
    inp = input("Enter a string to display or 'exit' to end program:")
    if inp == 'exit':
        break
    for r in range(row):
        for c in inp:
            print(symbolDict[c](r), end='')
        print()
print('game over')
