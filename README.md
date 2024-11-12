import pytest

def test_my():
    print("hello Jenkins")
    assert 1 + 1 == 2

def test_my1():
    print("hello Jenkins")
    assert 1 + 1 == 2

def test_my2():
    print("hello Jenkins")
    assert 1 + 1 == 2

if __name__ == "__main__":
    pytest.main()
