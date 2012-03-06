Very simple and easy to use timeouts library in Python.

To use it, simply import it:

    from timeouts import *

And whenever you want to set up a timeout:

    set_timeout(seconds)

Where "seconds" is the number of seconds till the library fires off the TimeoutException exception.  If after a call or something you want to clear the timeout, you would do a quick:

    clear_timeout()

And that's that.