# Example issue

After `parse_config()` reads a config file, `timeout=0` is ignored and replaced
with the default timeout. Expected behavior: an explicit zero should be preserved.

Environment: Python 3.11. The report author has not provided a minimal test case.
