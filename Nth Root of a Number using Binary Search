

public class Solution {
    public static int NthRoot(int n, int m) {
        int low = 1  , high = m/2 ;
      
        while(high > low) {
              int mid = (high - low)/2 + low ;

              if(Math.pow(mid , n) == m) 
              return mid ;

              if(Math.pow(mid , n) > m) {
                  high = mid ;
              }
              else {
                  low = mid+1 ;
              }
        }

        return -1 ;
    }
}
