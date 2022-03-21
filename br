#pip install pyautogui
#pip install opencv-python
#pip3 install keyboard
#pip3 install pydirectinput
#pip3 install pynput


from imports import *

timeStart = datetime.now()

timeFinish = timeStart + timedelta(seconds=60)

#  ======== settings ========
resume_key = Key.f1
pause_key = Key.f2
exit_key = Key.backspace
#  ==========================

pause = True
running = True

def on_press(key):
    global running, pause

    if key == resume_key:
        pause = False
        print("[Продолжение]")
    elif key == pause_key:
        pause = True
        print("[Пауза]")
    elif key == exit_key:
        running = False
        print("[Выход]")

def display_controls():
    print("Авто-Аморф")
    print("\t f1 = Продолжение")
    print("\t f2 = Пауза")
    print("\t backspace = Выход")
    print("-----------------------------------------------------")
    print('Нажмите f1, чтобы начать ...')
    

def loop1():
    lis = Listener(on_press=on_press)
    lis.start()

    display_controls()
    while running:
        if not pause:
            heal = pyautogui.locateOnScreen("BUTTON/heal.png", confidence = 0.93)
            heal2 = pyautogui.locateOnScreen("BUTTON/heal2.png", confidence = 0.93)
            amorfa_vix = pyautogui.locateOnScreen("BUTTON/amorfa_vix.png", confidence = 0.85)
            check = pyautogui.locateOnScreen("BUTTON/check.png", confidence = 0.95)
            navx = pyautogui.locateOnScreen("BUTTON/navx.png", confidence = 0.92)
            check2_1 = pyautogui.locateOnScreen("BUTTON/check2_1.png", confidence = 0.92)
            amorfa_dom = pyautogui.locateOnScreen("BUTTON/amorfa_dom.png", confidence = 0.92)
            check2_2 = pyautogui.locateOnScreen("BUTTON/check2_2.png", confidence = 0.92)
            fondruid = pyautogui.locateOnScreen("BUTTON/fondruid2.png", confidence = 0.92)
            peton2 = pyautogui.locateOnScreen("BUTTON/peton.png", region=(1800,990,1919,1079), confidence = 0.92)
            petoff2 = pyautogui.locateOnScreen("BUTTON/petoff.png", region=(1800,990,1919,1079), confidence = 0.92)
            utop = pyautogui.locateOnScreen("BUTTON/utop.png", region=(0,60,1250,1079), confidence = 0.84)
            utop1 = pyautogui.locateOnScreen("BUTTON/utop1.png", confidence = 0.94)
            boss = pyautogui.locateOnScreen("BUTTON/boss.png", confidence = 0.81)
            komar = pyautogui.locateOnScreen("BUTTON/komar.png", confidence = 0.85)
            vorota = pyautogui.locateOnScreen("BUTTON/vorota.png", confidence = 0.75)
            utat = pyautogui.locateOnScreen("BUTTON/utat.png", region=(1600,770,1919,900), confidence = 0.75)

        
        
            
            
            
            
        
                
            if check:
                if heal:
                    print("отхилился")
                    pydirectinput.keyDown('r')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('r') 
                    time.sleep(random.uniform(1,1.5))
                if amorfa_dom:
                    if amorfa_vix:
                        time.sleep(random.uniform(2.9,3.5))
                        if petoff2:
                            print("вкл пета")
                            pyautogui.moveTo(petoff2, duration=0.6)
                            time.sleep(random.uniform(0.3,0.8))
                            pyautogui.moveRel(-32, 0, duration=0.5)
                            time.sleep(random.uniform(0.3,0.8))
                            pyautogui.click(button='left')
                            time.sleep(random.uniform(2.2,3.5))
                            time.sleep(random.uniform(0.2,0.4))
                        if peton2:
                            print("выхожу с аморфы")
                            time.sleep(random.uniform(1,2.5))
                            pyautogui.moveTo(amorfa_vix, duration=1.2)
                            pyautogui.moveRel(-20, 55, duration=1.3)
                            time.sleep(random.uniform(1,2.5))
                            pyautogui.click(button='left')
                            pyautogui.click(button='right')
                            time.sleep(random.uniform(1,1.5))
                            pyautogui.moveRel(266, 211, duration=1.6)  
                            time.sleep(random.uniform(2,3.5))
                if check2_1:
                    if navx:
                        print("иду на переправу")
                        pyautogui.moveTo(navx, duration=0.4)
                        pyautogui.moveRel(20, 56, duration=0.7)
                        time.sleep(random.uniform(0.3,0.6))
                        pyautogui.click(button='left')
                        pyautogui.click(button='right')
                        pyautogui.moveRel(-61, -66, duration=0.4)
                        pyautogui.sleep(1)            
                if check2_2:
                    if navx:
                        print("иду на переправу")
                        pyautogui.moveTo(navx, duration=0.4)
                        pyautogui.moveRel(20, 56, duration=0.7)
                        pyautogui.sleep(0.4)
                        pyautogui.click(button='left')
                        pyautogui.click(button='right')
                        pyautogui.moveRel(-61, -66, duration=0.4)
                        pyautogui.sleep(1) 
                if navx:
                    if utop1:
                        if komar == None:
                            if vorota == None:
                                if utat == None:
                                    print("ищу утопленника")
                                    pyautogui.moveTo(116, 207, duration=0.28)
                                    keyboard.send("n")
                                    time.sleep(random.uniform(0.3,0.8))                
                    if utop:
                        print("атакую утопленника")
                        pyautogui.moveTo(utop, duration=0.5)
                        time.sleep(random.uniform(0.3,0.8))
                        pyautogui.moveRel(3, 2)
                        pyautogui.click(button='left')
                        time.sleep(random.uniform(0.3,0.7))   
                     
                
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.3,0.9))
            
            if fondruid:
                time.sleep(random.uniform(0.3,0.5))
                if peton2:
                    pyautogui.moveTo(peton2, duration=0.4)
                    time.sleep(random.uniform(0.2,0.5))
                    pyautogui.moveRel(-33, 0, duration=0.6)
                    time.sleep(random.uniform(0.2,0.6))
                    pyautogui.click(button='left')
                    time.sleep(random.uniform(0.9,1.5))
                if petoff2:
                    print("иду с болот к аморфе")
                    pyautogui.moveTo(fondruid)
                    pyautogui.moveRel(195, -85, duration=0.4)
                    pyautogui.click(button='left')
                    pyautogui.click(button='right')
                    pyautogui.sleep(0.4)
        
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.9,1.5))
            
            if check == None:
                if heal2:
                    print("отхил")
                    pyautogui.sleep(1)
                    keyboard.send("r")
                    pyautogui.sleep(1) 
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.3,0.9))
            
            if boss:
                pyautogui.moveTo(boss, duration=0.4)
                time.sleep(random.uniform(0.2,0.5))
                pyautogui.moveRel(-3, 2, duration=0.6)
                time.sleep(random.uniform(0.2,0.6))
                pyautogui.click(button='left')
                time.sleep(random.uniform(0.2,0.6))
                pyautogui.click(button='right')
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.3,0.9))
        
        
def loop2():
    while running:
        if not pause:
            button3 = pyautogui.locateOnScreen("BUTTON/close.png", confidence = 0.82)
            check = pyautogui.locateOnScreen("BUTTON/check.png", confidence = 0.85)
            check_vx = pyautogui.locateOnScreen("BUTTON/check_vx.png", confidence = 0.7)    
            amvx = pyautogui.locateOnScreen("BUTTON/amvx.png", confidence = 0.82) 
            utop2 = pyautogui.locateOnScreen("BUTTON/utop2.png", confidence = 0.82)
            ut22 = pyautogui.locateOnScreen("BUTTON/ut22.png", confidence = 0.82)
            navx = pyautogui.locateOnScreen("BUTTON/navx.png", confidence = 0.92)
            utop = pyautogui.locateOnScreen("BUTTON/utop.png", confidence = 0.85)
            amorfa_dom = pyautogui.locateOnScreen("BUTTON/amorfa_dom.png", confidence = 0.82)
            vorota = pyautogui.locateOnScreen("BUTTON/vorota.png", confidence = 0.75)
            utat = pyautogui.locateOnScreen("BUTTON/utat.png", region=(1600,770,1919,990), confidence = 0.75)

            
             

            

            if check:  
                if utop2:
                    if ut22:
                        print("бой с утопленником")
                        pyautogui.moveTo(utop2, duration=0.4)
                        pyautogui.moveRel(0, 3, duration=0.4)
                        pyautogui.click(button='left')
                    if ut22 == None:
                        print("закрываю окно")
                        time.sleep(random.uniform(0.3,0.6))
                        keyboard.send("esc")            
                if navx:
                    if utop == None: 
                        if amorfa_dom == None:
                            if vorota == None:
                                if utat == None:
                                    print("повт открытие") 
                                    pyautogui.moveTo(navx, duration=0.2)
                                    pyautogui.moveRel(20, 56, duration=0.3)
                                    time.sleep(random.uniform(0.3,0.5))
                                    pyautogui.click(button='right') 
                                    pyautogui.moveRel(-61, -63, duration=0.4)
                                    time.sleep(random.uniform(21.3,34.6)) 

                
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.3,0.9))
            
            
            if button3:
                if utop2 == None:
                    print("закрываю окно")
                    time.sleep(random.uniform(1,1.4))
                    keyboard.send("esc")
                
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(1,1.4))
     
     
    
def loop3():
    while running:
        if not pause:
            utop2 = pyautogui.locateOnScreen("BUTTON/utop2.png", confidence = 0.92)
            ut22 = pyautogui.locateOnScreen("BUTTON/ut22.png", confidence = 0.92)
            alV = pyautogui.locateOnScreen("BUTTON/alV.png", confidence = 0.92)
            alB = pyautogui.locateOnScreen("BUTTON/alB.png", confidence = 0.92)
            alK = pyautogui.locateOnScreen("BUTTON/alK.png", confidence = 0.92)
            alE = pyautogui.locateOnScreen("BUTTON/alE.png", confidence = 0.92)
            alK2 = pyautogui.locateOnScreen("BUTTON/alK2.png", confidence = 0.92)
            alVXB = pyautogui.locateOnScreen("BUTTON/alVXB.png", confidence = 0.92)
            alCheck1 = pyautogui.locateOnScreen("BUTTON/alCheck1.png", confidence = 0.92)
            kill_boloto1 = pyautogui.locateOnScreen("BUTTON/kill_boloto1.png", confidence = 0.92)
            kill_boloto2 = pyautogui.locateOnScreen("BUTTON/kill_boloto2.png", confidence = 0.92)
            kill_boloto3 = pyautogui.locateOnScreen("BUTTON/kill_boloto3.png", confidence = 0.92)
            kill_bolotoVV = pyautogui.locateOnScreen("BUTTON/kill_bolotoVV.png", confidence = 0.92)
            check = pyautogui.locateOnScreen("BUTTON/check.png", confidence = 0.85)
            navx = pyautogui.locateOnScreen("BUTTON/navx.png", confidence = 0.92)
            utop = pyautogui.locateOnScreen("BUTTON/utop.png", confidence = 0.85)
            amorfa_dom = pyautogui.locateOnScreen("BUTTON/amorfa_dom.png", confidence = 0.82)
            dead = pyautogui.locateOnScreen("BUTTON/dead.png", confidence = 0.82)
            
        
        
            
            
                   
                   
        
            
            if dead:
                time.sleep(random.uniform(5.3,8.6))
                pyautogui.moveTo(dead, duration=1.1)
                pyautogui.moveRel(36, 16, duration=0.4)
                pyautogui.click(button='left')
                time.sleep(random.uniform(7.4,9.3))
                
                
        
        
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.3,0.9))
            
            
        
            if check:
                if utop2:
                    if ut22:
                        print("бой с утопленником")
                        pyautogui.moveTo(utop2, duration=0.4)
                        pyautogui.moveRel(0, 3, duration=0.4)
                        pyautogui.click(button='left')
                    if ut22 == None:
                        print("закрываю окно")
                        time.sleep(random.uniform(0.3,0.6))
                        keyboard.send("esc")  
                if navx == None:                
                    if kill_bolotoVV:
                        if kill_boloto1:
                            time.sleep(random.uniform(0.3,0.6))
                            pyautogui.moveTo(kill_boloto1, duration=1.3)
                            pyautogui.moveRel(0, 200, duration=0.4)
                            pyautogui.click(button='left')
                            time.sleep(random.uniform(5.4,6.3))
                    if kill_boloto1:
                        if kill_boloto2:
                            time.sleep(random.uniform(0.3,0.6))
                            pyautogui.moveTo(kill_boloto2, duration=1.1)
                            pyautogui.moveRel(248, 171, duration=0.4)
                            pyautogui.click(button='left')
                            time.sleep(random.uniform(1.4,2.3))
                    if kill_boloto2:
                        if kill_boloto3:
                            time.sleep(random.uniform(0.3,0.6))
                            pyautogui.moveTo(kill_boloto3, duration=1.1)
                            pyautogui.moveRel(176, 66, duration=0.4)
                            pyautogui.click(button='left')
                            time.sleep(random.uniform(1.4,2.3))
                    if alV:
                        print("умер! выхожу c таверны")
                        time.sleep(random.uniform(600,1500))
                        pyautogui.moveTo(alV, duration=1.1)
                        pyautogui.click(button='right')
                        pyautogui.moveRel(226, 116, duration=0.4)
                        time.sleep(random.uniform(2.4,3.3))
                    if alCheck1:
                        if alB:
                            time.sleep(random.uniform(0.3,0.6))
                            pyautogui.moveTo(alB, duration=1.1)
                            pyautogui.moveRel(0, 246, duration=0.4)
                            pyautogui.click(button='left')
                            time.sleep(random.uniform(1.4,2.3))
                    if alB:
                        if alK:
                            time.sleep(random.uniform(0.3,0.6))
                            pyautogui.moveTo(alK, duration=1.1)
                            pyautogui.moveRel(-253, 27, duration=0.4)
                            pyautogui.click(button='left')
                            time.sleep(random.uniform(1.4,2.3))
                    if alK:
                        if alE:
                            time.sleep(random.uniform(0.3,0.6))
                            pyautogui.moveTo(alE, duration=1.1)
                            pyautogui.moveRel(-93, 177, duration=0.4)
                            pyautogui.click(button='left')
                            time.sleep(random.uniform(1.4,2.3))
                    if alE:
                        if alK2:
                            time.sleep(random.uniform(0.3,0.6))
                            pyautogui.moveTo(alK2, duration=1.1)
                            pyautogui.moveRel(-93, 97, duration=0.4)
                            pyautogui.click(button='left')
                            time.sleep(random.uniform(1.4,2.3))
                    if alVXB:
                        time.sleep(random.uniform(0.3,0.6))
                        pyautogui.moveTo(alVXB, duration=1.1)
                        pyautogui.moveRel(143, -97, duration=0.4)
                        pyautogui.click(button='right')
                        time.sleep(random.uniform(1.4,2.3))

        
        
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.3,0.9))
    





def loop4():
    while running:
        if not pause:
            check = pyautogui.locateOnScreen("BUTTON/check.png", confidence = 0.85)
            raund1 = pyautogui.locateOnScreen("BUTTON/raund1.png", confidence = 0.75)
            raund2 = pyautogui.locateOnScreen("BUTTON/raund2.png", confidence = 0.75)     
            vorota = pyautogui.locateOnScreen("BUTTON/vorota.png", confidence = 0.75)
            amvx = pyautogui.locateOnScreen("BUTTON/amvx.png", confidence = 0.82) 
            check_vx = pyautogui.locateOnScreen("BUTTON/check_vx.png", confidence = 0.7)
            
            
            if check:
                if vorota:
                    print("вор открыты")
                    if amvx:
                        print("нашел вход - иду")
                        pyautogui.moveTo(amvx, duration=0.2)
                        pyautogui.moveRel(-20, -18, duration=0.2)
                        pyautogui.click(button='right')
                        time.sleep(random.uniform(5.4,7.1))
                        pyautogui.moveRel(0, 25)
                if check_vx:
                    if amvx:
                        print("нашел вход - иду")
                        pyautogui.moveTo(amvx, duration=0.2)
                        pyautogui.moveRel(-20, -18, duration=0.4)
                        pyautogui.click(button='right')
                        time.sleep(random.uniform(9,11))
                        pyautogui.moveRel(0, 34, duration=0.2)
                        time.sleep(random.uniform(1.2,2.1))
                if raund1:
                    print("бой! 1 раунд Аморфа")
                    time.sleep(random.uniform(0.3,0.6))
                    keyboard.send("1")
                    time.sleep(random.uniform(0.3,0.6))
                    keyboard.send("1")
                    time.sleep(random.uniform(0.3,0.9))
                    keyboard.send("f1")
                    time.sleep(random.uniform(1.4,2.5))
                if raund1:
                    print("бой! 1 раунд")
                    time.sleep(random.uniform(0.3,0.9))
                    pydirectinput.keyDown('2')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('2')
                    time.sleep(random.uniform(1,1.5))
                    pydirectinput.keyDown('f1')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('f1')
                    time.sleep(random.uniform(1.4,2.5))
                if raund2:
                    print("бой! 2+ раунд")
                    time.sleep(random.uniform(0.3,0.9))
                    pydirectinput.keyDown('2')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('2')
                    time.sleep(random.uniform(1,1.5))
                    pydirectinput.keyDown('f1')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('f1')
                    time.sleep(random.uniform(1.4,2.5))
                    
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.3,0.9))
            
            if check == None:
                if raund1:
                    print("бой! 1 раунд Аморфа")
                    time.sleep(random.uniform(0.3,0.6))
                    keyboard.send("1")
                    time.sleep(random.uniform(0.3,0.6))
                    keyboard.send("1")
                    time.sleep(random.uniform(0.3,0.9))
                    keyboard.send("f1")
                    time.sleep(random.uniform(1.4,2.5))
                if raund1:
                    print("бой! 1 раунд")
                    time.sleep(random.uniform(0.3,0.9))
                    pydirectinput.keyDown('2')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('2')
                    time.sleep(random.uniform(1,1.5))
                    pydirectinput.keyDown('f1')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('f1')
                    time.sleep(random.uniform(1.4,2.5))
                if raund2:
                    print("бой! 2+ раунд")
                    time.sleep(random.uniform(0.3,0.9))
                    pydirectinput.keyDown('2')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('2')
                    time.sleep(random.uniform(1,1.5))
                    pydirectinput.keyDown('f1')
                    time.sleep(random.uniform(0.3,0.8))
                    pydirectinput.keyUp('f1')
                    time.sleep(random.uniform(1.4,2.5))
                
            timeStart = datetime.now()
            
            time.sleep(random.uniform(0.3,0.9))

Thread(target=loop1).start()
Thread(target=loop2).start()
Thread(target=loop3).start()
Thread(target=loop4).start()
