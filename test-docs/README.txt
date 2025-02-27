Use this document to test `blacken-docs` for text extension types.

## Testing

To run, use the following command:

```bash
python3 blacken_docs.py test-docs/README.txt
```

This command does the following:

- `blacken_docs.py` runs the script and passes the file name.
- The file is formatted and saved to the same directory.

### Python

The following Python code will be formatted when the previous command is passed:

```python
def hello():
    print( f"hello world")
```

### Pycon

The following Pycon code will be formatted when the previous command is passed:

```pycon
>>> def hello():
...     print( f"hello world")
...

```

**Results**: The space between `print(` and the `f` string is eliminated.
