# Control logs of undetected-chromedriver

You can see the original project here:
[undetected-chromedriver](https://github.com/ultrafunkamsterdam/undetected-chromedriver)

## Installation

You can install the modified package directly from GitHub using pip:

```
pip install git+https://github.com/syntaxsurge/undetected-chromedriver-control-logs.git
```

## Usage

If `log_level=3`, it logs only errors, not warnings nor infos of the undetected-chromedriver itself and the browser.

You can use it like this:

```python
import undetected_chromedriver as uc
driver = uc.Chrome(options=options, log_level=3)
```
