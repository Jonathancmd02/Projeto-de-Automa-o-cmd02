# Projeto-de-Automa-o-cmd02
#Aprendi a fazer isso aí para entrar diretamente no curso do Senai

import pyautogui    
import time 

#Pausa geral de 0.3 segundos (300 milissegundos)
pyautogui.PAUSE = 0.3

#Espere um tempo para rodar
time.sleep(5)

#Pegar posição do mouse
print(pyautogui.position())

#Pegar o tamanho da tela/resolução
#print(pyautogui.size())

#Clicar com mouse
pyautogui.click(x=396, y=353)

#clicar com botão direito do mouse
#pyautogui.click(x=403, y=365, button="right")

#Dois clicks no Mouse
#pyautogui.click(x418, y=356, clicks="2")

#Mover o Mouse
pyautogui.moveTo(x=662, y=226, duration=0.5)

pyautogui.click(x=1172, y=315)

pyautogui.scroll(-1750)

pyautogui.click(x=1021, y=660)

pyautogui.click(x=449, y=385)

#Funções do teclado
pyautogui.write("Desenvolvimento de Sistemas")

