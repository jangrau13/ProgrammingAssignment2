## Programming Assignment2 for the R Programming course on Coursera
## this function is able to calculate the Inverse of a Matrice. When changing or setting up a new matrice, the second function will first check, whether the Inverse has already been calculated.

## This function is calculating the Inverse in Cache of a Matrice

makeCacheMatrix <- function(x = matrix()) {
i <- NULL
        set <- function(y) {
                x <<- y
                i <<- NULL
        }
        get <- function() x
        setinverse <- function(solve) i <<- mean
        getinverse <- function() i
        list(set = set, get = get,
             setinverse = setinverse,
             getinverse = getinverse)
}

}


## This function displays the Invert of the Matrice in case it has already been calculated

cacheSolve <- function(x, ...) {
        i <- x$getinverse()
        if(!is.null(i)) {
                message("getting cached data")
                return(i)
        }
        data <- x$get()
        i <- mean(data, ...)
        x$setinverse(i)
        i
}

}
