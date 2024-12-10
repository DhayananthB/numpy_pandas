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
- *rng = np.random.default_rng(seed=42)*
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
- `np.isnan(a)`

# [Part 2](numpy_2_slicing.ipynb)

- *Contains indexing and slicing of numpy arrays*
- *Broadcatsing*

# [Part 3](numpy_3.ipynb)

- `np.sort(a)`
- `np.append(a,97)`
- `np.concatenate((a,b))`
- `np.unique(a)`
- `np.expand_dims(a,axis=0/1)`
  
- *# replace values > 20 with 99*
- `np.where(dup>20,99,dup)`
  
- `np.argmax()`
- `np.cumsum(a); np.cumprod()`
- `np.percentile(a,50)`
- `np.histogram(a,bins=[0,10,20,30,40,50])`
- `np.corrcoef(s,y)`
- `np.isin(a,b)`
- `np.flip(a)`
- `np.put(a, [0, 2, 3 <index> ], [-41, -55,8148])`
- `np.delete(a,[0,2 <index>])`
  
- `np.union1d(m,n)`
- `np.intersect1d(m,n)`
- `np.setdiff1d(n,m)` and more there....
  
- `np.clip(a,a_min=25,a_max=30)`
- `np.full((3,5),5)`
- `np.count_nonzero(a)`
- `np.copyto(arr1,arr2) #must be of same dimension`
  
- `np.allclose(a, b)`
- `np.array_equal(a, b)`
- `a==b`
- 
- `np.swapaxes(a,0,2)`
  
- `np.tile(a,3)`
- `np.repeat(a,3)`
