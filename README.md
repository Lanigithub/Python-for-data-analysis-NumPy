# How to create a numpy array 
__Either by__\
__1. casting a list or tuple A to an array method arr=np.array(A)__\
__OR__\
__2. by using  one of the built in functions for a Numpy arrays such as np.array.zeros() and array.ones() arr.linspace() and eye() and__

__3. also use the random generation methods you call np.random.rand() and then np.random.randn() and or some of the other random methods  np.random.randint() to generate an array.__

__\***Useful methods and attributes for a numpy array:__\
__1. methods: reshape(), min(), max(), argmin(), argmax()__\
__2.attributes: shape, dtype, ndim, size__


# Numpy Array Indexing, slicing and selection
## Indexing:Array indexing is the same as accessing an array element.
__A= array[1,2,3,4] A[0]= 1, A[-1]=4(negative index from the end)__

__You can access an array element by referring to its index number.   A =array[[1,2,3,4], [5,6,7,8]  A[1, 2]=A[1][2]=A[row][column]=element on 2nd row and 3rd column= 7__

__The indexes in NumPy arrays start with 0, meaning that the first element has index 0, and the second has index 1 etc.__\

## Slicing:Slicing in python means taking elements from one given index to another given index.

__We pass slice instead of index like this: [start:end].__

__We can also define the step, like this: [start: end: step].__

__If we don't pass start its considered 0__

__If we don't pass end its considered length of array in that dimension__

__If we don't pass step its considered 1__\

__3.Selection:__\
__4. Amending:__

# Numpy Array operations
