Code Documentation
==================

.. code-block:: python

    def func1(arg1, arg2):
    """
    This function, takes 2 arguments assigns the first argument with the second argument value
    :param arg1: some value
    :param arg2: another value
    :return: arg1
    # written in reStructured Text doc string
    """
    arg1 = arg2
    return arg1

    # def func2(arg1, arg2):
    # #     """
    # #     This function, takes 2 arguments assigns the first argument with the second argument value
    # #     Args:
    # #         arg1: some value
    # #         arg2: another value
    # #
    # #     Returns:
    # #         arg1
    # #     """
    # #     arg1 = arg2
    # #     return arg1

    def func2():
        """
        Function with no argument return none
        :return: None
        """
        return None
