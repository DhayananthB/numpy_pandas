# [Part 1](numpy_1.ipynb)

- `import numpy as np`
- `a = np.array([a,b,..])`
- `a.dtype #np.int32 np.float32`
- `a.ndim #dimension`
- `a.size`
- `a.shape`
- `np.arange()`
- `arr.reshape(a,b,c..)`
- `a.itemsize`
- `a.nbytes`
- `np.ones`
- `np.zeros`
- `np.random.seed(42)`
- `np.random.rand(4,5)`
- `np.random.randint(low,high,size=(a,b,c,...))`
- `np.random.random((a,b,c..))`
- `np.random.uniform(low,high,size=(a,b,c..))`
- `arr1.astype(<dtype>)`
- `np.identity(n)`
- `a*2; a**2 ; a*b ; a+b`
- `np.sum(a,axis=1) #sum,prod,max,min,mean,median,std,var`
- `np.round(a) #floor,ceil`
- `np.log() #exp`
- `for i in np.nditer(a):`
- `np.dot(a,b) ; a@b`
- `np.transpose(a); a.T`
- `a.ravel()`
- `np.hstack((a,b,c..)) # rows must be same`
- `np.vstack((a,b,c..)) # cols must be same`
- `np.hsplit(a,<no.of splits>)`
- `np.vsplit(a,<no.of splits>)`

# [Part 2](numpy_2_slicing.ipynb)

*Contains indexing and slicing of numpy arrays*