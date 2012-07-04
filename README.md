Secure-Python-Guide
===================

This is a guide on how to write Secure Python code. 


Proper use of Python Stdlib
===========================

1. Don't use `eval`. If you need `eval` functionality use `ast.literal_eval` (http://docs.python.org/library/ast.html#ast.literal_eval)
1. `os.mkdir` will `chmod 777` every directory it creates unless you provide an alternative
1. Use Hmac
1. If you need to serialize data use the safe alternatives `yaml.safe_loads`

Insecure Examples of Stdlib 
===========================





