This pool begins with an initial capacity and will continue creating new objects on request when none are available. pooled objects are returned to the pool on destruction .
If, during an attempted return, a pool already has maximum_capacity objects in the pool, the pool will throw away that object.
