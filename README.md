# 60_wrapBinarySearch

2. the exponent(y) to which 2 must be raised to yield x
   the graph is an increasing curve where x is greater than 0 and starts from negative infinity.
   
3. 0. Return the index of a specific Integer in an ArrayList.
   1. Return the index of a specific Integer in the upper half or the lower half of the current ArrayList.
   2. Boolean if( low > hi)
      Solution to base case return -2;
      Leftover
      int pageToCheck = (low + hi) / 2;
            int comparison =
              findMe.compareTo( list_iAS.get( pageToCheck));


            if( comparison == 0)   
                return pageToCheck; 
      Recursive abstraction
      return indexOf_recursive( findMe
                                             , low
                                             , pageToCheck -1);
      return indexOf_recursive( findMe
                                            , pageToCheck +1
                                            , hi);