# Heartt
# This programs draws a heart which made of a character that you write as an input.
print('This program will make you smile.')
print('Please enter one character')
name=input()
print('And now please create a name. Your name must include 5 letters')
yourName=input() #it must be 5 letters long
def loops(z):
    
    first_row=  (' '*12 + name*6 + ' '*3 + name*6)
    if len(name)==1:
        print(first_row)
    else:
        print(' '*12+'0'*6+' '*3+'0'*6)
    second_row=(' '*11 +name + ' '*6 + name+ ' ' + name+ ' '*6+name)
    if len(name)==1:
        print(second_row)
    else:
        print(' '*11+'0'+' '*6+'0'+' '+'0'+' '*6+'0')
        
    
    third_row=(' '*10+name+ ' '*8 + name+ ' '*8+ name)
    if len(name)==1:
        print(third_row)
    else:
        print(' '*10+'0'+' '*8+'0'+' '*8+'0')

    
    fourth_row=(' '*9 +name+' '*19+name)
    if len(name)==1:
        print(fourth_row)
    else:
        print(' '*9+'0'+' '*19+'0')

    add0=(' '*9+name+' '*19+name)
    if len(name)==1:
        print(add0)
    else:
        print(' '*9+'0'+' '*19+'0')
    
    
    fifth_row=(' '*9+name+' '*7+ yourName+' '*7+name)
    if len(name)==1:
        print(fifth_row)
    else:
        print(' '*9+'0'+' '*7+yourName+' '*7+'0')
    
    sixth_row=(' '*9+name+' '*19+name)
    if len(name)==1:
        print(sixth_row)
    else:
        print(' '*9+'0'+' '*19+'0')

    
    add1=(' '*9+name+' '*19+name)
    if len(name)==1:
        print(add1)
    else:
        print(' '*9+'0'+' '*19+'0')

    seventh_row=(' '*10+name+' '*17+name)
    if len(name)==1:
        print(seventh_row)
    else:
        print(' '*10+'0'+' '*17+'0')
    
    eight_row=(' '*11+name+' '*15+name)
    if len(name)==1:
        print(eight_row)
    else:
        print(' '*11+'0'+' '*15+'0')
    
    ninth_row=(' '*12+name+' '*13+name)
    if len(name)==1:
        print(ninth_row)
    else:
        print(' '*12+'0'+' '*13+'0')
    
    tenth_row=(' '*13+name+' '*11+name)
    if len(name)==1:
        print(tenth_row)
    else:
        print(' '*13+'0'+' '*11+'0')
    eleventh_row=(' '*15+name+' '*7+name)
    if len(name)==1:
        print(eleventh_row)
    else:
        print(' '*15+'0'+' '*7+'0')
    
    twelveth_row=(' '*17+name+' '*3+name)
    if len(name)==1:
        print(twelveth_row)
    else:
        print(' '*17+'0'+' '*3+'0')
    
    thirteenth_row=(' '*19+name)
    if len(name)==1:
        print(thirteenth_row)
    else:
        print(' '*19+'0')
    
loops(name)
print(' '*5+ 'Never let anybody steal your smiles')




