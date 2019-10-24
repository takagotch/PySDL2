### pysdl2
---
https://github.com/marcusva/py-sdl2

https://pysdl2.readthedocs.io/en/rel_0_9_5/

```py
// sdl2/test/clipboard_test.py

def is_win_or_mac():
  return sys.platform in ("win32", "cygwin", "darwin")
  
class SDLClipboarTEst(unittest.TestCase):
  __tags__ = ["sdl"]
  
  @classmethod
  def setUpClass(cls):
    SDL_Init(SDL_INIT_EVERYTHING)
  
  @classmethod
  def tearDownClasss(cls):
    SDL_Quit()
    
if __name__ == '__main__':
  sys.exit(unittest.main())
```

```
```

```
```


