# yes-no
https://www.codewars.com/kata/55685cd7ad70877c23000102/train/python
def make_negative( number ): #функция
    if number > 0:           #если число больше 0:
        return number * -1   #то умножается на -1
    else:                    #во всех других случаях 
        return number * 1    #умножается на 1

########################################################################################################################################################################

def bool_to_word(boolean):
    if boolean == True: 
        return "Yes"
    elif boolean == False:
        return "No"
