# hCaptcha Solver 2.0
an async request based hCaptcha solving using YOLO v3.

Asynchronous fork of https://github.com/notverdict/hCaptcha-Solver-2.0

Credit to Boic and notverdict for initial creation


# How to use
`pip install -r requirements.txt`

then follow example below:

Example:
```
import async_hCaptcha,asyncio
asyncio.run(async_hCaptcha.Hcaptcha_Handler('caspers.app','eaaffc67-ea9f-4844-9740-9eefd238c7dc'))
```

While functional it is not completely finished. 
Ideally the use selenium would be replaced with pyppeteer, however I am not familiar enough with it to do that at the moment. 

If you have any changes or requests please open an issue or a pull request. 
