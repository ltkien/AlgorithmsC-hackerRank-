# AlgorithmsC-hackerRank-
Some solution

##1 Solve Me First

      static int solveMeFirst(int a, int b) { 
            // Hint: Type return a+b; below  
            int sum= a+b;
            return sum;
      }
    
##2 Simple Array Sum

 /*
     * Complete the 'simpleArraySum' function below.
     *
     * The function is expected to return an INTEGER.
     * The function accepts INTEGER_ARRAY ar as parameter.
     */

    public static int simpleArraySum(List<int> ar)
    {
        int sum= 0;
        
        foreach (int n in ar)
        {
            sum =n+ sum;
        }
        
       
        return sum;
    }   
    
##3 Simple Array Sum

 /*
     * Complete the 'compareTriplets' function below.
     *
     * The function is expected to return an INTEGER_ARRAY.
     * The function accepts following parameters:
     *  1. INTEGER_ARRAY a
     *  2. INTEGER_ARRAY b
     */

    public static List<int> compareTriplets(List<int> a, List<int> b)
    {
        int pointA = 0;
        int pointB = 0;
        List<int> point = new List<int>();
        for(int i=0; i<3; i++)
        {
            if(a[i]>b[i] )
            {
                pointA++;
            }
            else if(a[i]<b[i] )
            {
                pointB++;
            }
            
        }
        point.Add(pointA);
        point.Add(pointB);
        
        return point;
        
    }


