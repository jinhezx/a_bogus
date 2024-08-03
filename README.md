```
def gen_a_bogus(url, ua=''):
    abogus = ""
    try:
        abogus = os_a.call('generate_a_bogus', url, ua)
    except Exception as e:
        op_error(e)
    return abogus
```

##### Q:120525183
