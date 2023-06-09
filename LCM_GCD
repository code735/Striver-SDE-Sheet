a = 5 , b = 10;

LCM Formula = (a*b)/GCD(a,b)

GCD Formula = while(a % b != 0) OR while (b % a != 0)


## Key Learnings : 

### We'll need to find GCD first because LCM is dependent on GCD.

### always sort both numbers before writing algo

## Pseudo Code optimal approach:

class Solution {
    static Long[] lcmAndGcd(Long A , Long B) {
        // code here
        
        Long x=Math.max(A,B);
        Long y=Math.min(A,B);
        
        Long rem = x;
        
        while(rem!=0){
            rem=x%y;
            x=y;
            if(rem==0) break;
            y=rem;
        }
        
        Long lcm = (A*B)/y;
        
        Long ans[] = new Long[2];
        ans[0]=lcm;
        ans[1]=y;
        
        
        return ans;
    }
};