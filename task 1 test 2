import task1 as t1
import unittest

class TestSequenceFunctions(unittest.TestCase):
    def setup(self):
        t1.rates = [1, 2, 3, 4]
        
    def test1(self):
        assert(t1.rates[0] ==1) #test 1 fails pounds isn't 1
        
    def test2(self):
        assert(t1.conv(10,0,2)==30) #test 2 fails conversion to USD
        assert(t1.conv(10,0,1)==20) #test 2 fails converison to EUR
        
    def test3(self):
        assert(t1.conv(9,2,0)==3) #test 3 fails conversion USD to GBP
        assert(t1.conv(20,1,0)==10) #test 3 failsconversion EUR to GBP
        
    def test4(self):
        assert(t1.conv(9,2,3)==12) #task 4 fails conversion USD to JPY
        assert(t1.conv(20,1,3)==40) #task 4 fails conversion EUP to JPY 
    
   
if __name__ == '__main__':
    unittest.main()
