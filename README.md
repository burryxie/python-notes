# python-notes
*Notes on specific manipulation in Python. Personally I prefer R cause RStudio is such an awesome IDE. But for Python, the IDEs are awful! Here I take notes on some specific manipulations in Python, which maybe helpful.*

**adding a list to another**

`a = [1,2,3]
 b = [4,5,6]
 c = ['a','b','c']`

if the expected output is `c = [1,2,3,4,5,6]` , then the solution is `c = a + b`

if the expected output is `c =[[1,2,3],[4,5,6]]`, then the solution is `c = [a,b]` 

**saving lists to file**

`with open(filename,'w') as f:

   for item in lists:
   
      f.write('%s\n' % ietm)`
 
 
**creating dataframe**

`df = pd.DataFrame({'name1':a,'name2':b})`

