# python-function-accumulate

## try ... except 
    try:
    from setuptools import setup
    except ImportError:
    from distutils.core import setup   // when Error happen, execute the content in the module of except
    
    try:
    ...
    except:
    ...
    else:
    ...      //if there are not error,then execute the code in the try and else
    
    
    try:
    ...
    except:
    ...
    finally:
    ...       // not matter what happen, the code in the finally will be executed.
    
