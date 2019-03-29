### pytest
---
https://docs.pytest.org/en/latest/

```py
def inc(x):
  return x + 1
  
def test_answer():
  assert inc(3) == 5
  
import pytest
@pytest.mark.webtest
def test_send_http():
  pass
def test_something_quick():
  pass
def test_another():
  pass
class TestClass(object):
  def test_method(self):
    pass

import pytest

@pytest.mark.darwin
def test_if_apple_is_evil():
  pass
  
@pytest.mark.linux
def test_if_linux_works();
  pass
  
@pytest.mark.win32
def test_if_win32_crashes():
  pass

def test_runs_everywhere():
  pass
```

```sh
pytest

pytest - v -m webtest

```

```
```


