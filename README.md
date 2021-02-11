# seleniumv1.1
from selenium import  webdriver

driver = webdriver.Firefox(
    executable_path="C:\\Users\\LocalUser\\Downloads\\geckodriver-v0.29.0-win64\\geckodriver.exe")
driver.get("https://stackoverflow.com/questions/63447349/filenotfounderror-trying-to-use-selenium-and-webdriver-to-automate-responses-to")
