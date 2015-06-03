# python-sid

Python library to convert Windows SIDs

## Example

String input
```python
import sid

mysid = sid.sid('S-1-5-21-2127521184-1604012920-1887927527-72713')
print mysid.base64()
```

Output
```
AQUAAAAAAAUVAAAAoGXPfnhLm1/nfIdwCRwBAA==
```

Base46 input
```python
import sid

mysid = sid.sid('AQUAAAAAAAUVAAAAoGXPfnhLm1/nfIdwCRwBAA==', sid.SID_BASE64)
print mysid
```

Output
```
S-1-5-21-2127521184-1604012920-1887927527-72713
```

## Changelog
* 0.1
  * Fix docstrings for documentation
  * Add setup.py
  * Add ldap filter feature
  * Fix sponsor links
  * Initial commit

## Sponsored by

* [Red Hat](http://www.redhat.com)
* [Baloise Group](http://www.baloise.com)
