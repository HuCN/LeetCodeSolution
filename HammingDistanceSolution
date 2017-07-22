public class Solution {
    public int hammingDistance(int x, int y) {
        //x和y 异或运算 结果转成二进制 计算二进制数里1的数量
        String bin=Integer.toBinaryString(x^y);
        char[] chars=bin.toCharArray();
        int result=0;
        for(int i=0;i<chars.length;i++){
            if(chars[i]=='1'){
                result=result+1;
            }
        }
        return result;
    }
}
