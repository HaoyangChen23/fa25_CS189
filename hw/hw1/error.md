q2 - 9 result:
    ❌ Test case failed
    Trying:
        a = BearTensor('a', np.array([-1, 2, 3]))
    Expecting nothing
    ok
    Trying:
        c = a.mean()
    Expecting nothing
    ok
    Trying:
        c.backward()
    Expecting nothing
    ok
    Trying:
        assert np.array_equal(a.adjoint, np.array([1 / 3, 1 / 3, 1 / 3]))
    Expecting nothing
    **********************************************************************
    Line 4, in q2 8
    Failed example:
        assert np.array_equal(a.adjoint, np.array([1 / 3, 1 / 3, 1 / 3]))
    Exception raised:
        Traceback (most recent call last):
          File "/Users/leonchen/miniconda3/envs/CS189/lib/python3.10/doctest.py", line 1350, in __run
            exec(compile(example.source, filename, "single",
          File "", line 1, in 
            assert np.array_equal(a.adjoint, np.array([1 / 3, 1 / 3, 1 / 3]))
        AssertionError