public class Solution 
{
    public int[] Sum(int[] nums, int result) 
    {
        for (int i = 0; i < nums.Length; i++) 
        {
            for (int j = i + 1; j < nums.Length; j++) 
            {
                if (nums[j] == result - nums[i]) 
                {
                    return new int[] { i, j };
                }
            }
        }
        throw new System.InvalidOperationException("No solution");
    }
}
