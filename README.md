# Hellow_world
from selenium import webdriver
import time
driver = webdriver.Firefox()
driver.get('https://www.baidu.com/')
print(driver.title)
time.sleep(10)
#窗口调成最大，方便截图
driver.maximize_window()
